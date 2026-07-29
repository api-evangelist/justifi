---
name: Onboard a merchant sub account with JustiFi
description: Create a platform sub account, provision products, and configure fees.
api: openapi/justifi-openapi-original.yml
operations: [CreateSubAccount, ListSubAccounts, GetSubAccount, CreateBusiness, ProductProvisioning, CreateFeeConfiguration, GetPayoutAccount]
---

# Onboard a merchant (sub account)

Platforms use this flow to bring a new merchant onto JustiFi under PayFac Direct.

## Auth
OAuth client-credentials -> `Authorization: Bearer <token>` (see
authentication/justifi-authentication.yml).

## Steps
1. **Create the sub account** — `CreateSubAccount` for the merchant.
2. **Capture business identity** — `CreateBusiness` (with identities, addresses,
   bank accounts, documents) for KYC/underwriting. In the browser, the hosted
   onboarding / provisioning web components collect this.
3. **Provision products** — `ProductProvisioning` to enable payments/payouts on
   the sub account.
4. **Configure fees** — `CreateFeeConfiguration` on the sub account for the fee
   types your platform charges.
5. **Verify** — `GetSubAccount` and `GetPayoutAccount` to confirm status before
   going live.

## Rules
- Pass the merchant's sub account id in the `Sub-Account` header on scoped calls.
- List calls are cursor-paginated (limit/before_cursor/after_cursor + page_info).
- Subscribe to the `sub_accounts` webhook to track provisioning state changes
  (see asyncapi/justifi-webhooks.yml).
