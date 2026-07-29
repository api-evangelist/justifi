---
name: Accept a card payment with JustiFi
description: Tokenize a payment method and create, then optionally capture or refund, a payment.
api: openapi/justifi-openapi-original.yml
operations: [CreatePaymentMethod, CreatePayment, GetPayment, CapturePayment, CreateRefund]
---

# Accept a card payment

Use this flow to charge a customer through JustiFi. Raw card numbers are never
sent to the payments endpoint — tokenize first.

## Auth
1. POST client id + client secret to `https://api.justifi.ai/oauth/token`
   (client-credentials). Use a `test_` key for test mode.
2. Send the returned access token as `Authorization: Bearer <token>` on every call.
3. Platforms: scope to a merchant with the `Sub-Account` header.

## Steps
1. **Tokenize** — `CreatePaymentMethod` to turn card/bank details into a
   `pm_...` token. In browsers, prefer the JustiFi web component so the card
   never touches your server (keeps you out of PCI scope).
2. **Charge** — `CreatePayment` with the payment method token and amount. Send a
   unique `Idempotency-Key` header so a retry never double-charges.
3. **Confirm** — `GetPayment` to read status. Note the `fees` array is empty on
   the create response; it is populated asynchronously via the `payments`
   webhook or a later `GetPayment`.
4. **Capture** (if you authorized only) — `CapturePayment`.
5. **Refund** (if needed) — `CreateRefund`; you can selectively return specific
   fees to the merchant.

## Rules
- Idempotency-Key is required for safe retries on money-moving calls.
- A `402` with `error.decline_code` means the card was declined — surface a
  retry-with-another-method message, do not auto-retry on `do_not_retry`.
- See errors/justifi-problem-types.yml and errors/justifi-decline-codes.yml.
