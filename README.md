# JustiFi

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

JustiFi is an embedded-payments and PayFac-as-a-service platform that lets SaaS companies add payment processing to their software. Its REST API (base https://api.justifi.ai/v1) plus StencilJS web components handle sub-merchant onboarding, card and bank-account tokenization, payments, refunds, disputes, payouts, proceeds, checkouts, and card-present terminals, while JustiFi carries the PCI-DSS Level 1, SOC 2, and GDPR compliance burden. Authentication is OAuth 2.0 client-credentials yielding 24-hour Bearer tokens, with idempotent money movement, cursor pagination, and webhook events. Backed by Emergence Capital.

**Areas:** Company · Fintech · Payments · Embedded Payments · Payment Facilitation · Payouts · Developers

## JustiFi on APIs.io

Everything profiled for JustiFi is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/justifi/](https://apis.io/providers/justifi/)** — or go straight to one of the APIs or properties below.

### APIs (28)

- [JustiFi Ach Return Fees API](https://apis.io/apis/justifi/justifi-ach-return-fees-api/) — ACH return fees are fees charged by financial institutions when an ACH (Automated Clearing House) transaction is returned due to insufficient funds or other…
- [JustiFi Address API](https://apis.io/apis/justifi/justifi-address-api/) — Creating an Address entity provides the necessary information to identify and locate a physical address. It may be associated with an Identity entity or…
- [JustiFi API Credentials API](https://apis.io/apis/justifi/justifi-api-credentials-api/) — The API Credentials API from JustiFi — 1 operation(s) for api credentials.
- [JustiFi Balance Transactions API](https://apis.io/apis/justifi/justifi-balance-transactions-api/) — Balance transactions are the reflection of any movement of funds that affects the balance of an account. Oftentimes, a single financial transaction (like a…
- [JustiFi Bank Account API](https://apis.io/apis/justifi/justifi-bank-account-api/) — Create/manage bank accounts for your businesses. These accounts are used for paying out earnings for usage of various products, for example card processing.
- [JustiFi Bind Insurance API](https://apis.io/apis/justifi/justifi-bind-insurance-api/) — The Bind Insurance API from JustiFi — 1 operation(s) for bind insurance.
- [JustiFi Business API](https://apis.io/apis/justifi/justifi-business-api/) — Creating a business entity is an essential step in integrating your business operations with JustiFi. It is also necessary to comply with local laws and…
- [JustiFi Checkouts API](https://apis.io/apis/justifi/justifi-checkouts-api/) — Checkouts can be used to collect payments directly via API, or using our Checkout component. You can use a checkout to complete a payment via JustiFi, via…
- [JustiFi Disputes API](https://apis.io/apis/justifi/justifi-disputes-api/) — A customer may dispute their payment with the card issuer/bank if they believe the charge is erroneous. When this happens, a dispute record is created and…
- [JustiFi Document API](https://apis.io/apis/justifi/justifi-document-api/) — Create/manage documents attached to your businesses and identities. When a document record is created using this API the response object returns a presigned…
- [JustiFi Fee Configurations API](https://apis.io/apis/justifi/justifi-fee-configurations-api/) — Standard Fee Configurations allow platforms to set per-sub-account fee rates that are automatically applied at payment time. Configurations are managed per…
- [JustiFi Identity API](https://apis.io/apis/justifi/justifi-identity-api/) — Creating an identity establishes a unique identification for people associated with your business. Accurately providing your information is crucial in…
- [JustiFi Payment Method Groups API](https://apis.io/apis/justifi/justifi-payment-method-groups-api/) — Payment method groups are a way to associate payment methods to a single group for easy access.
- [JustiFi Payment Methods API](https://apis.io/apis/justifi/justifi-payment-methods-api/) — Payment methods refer to the specific form of payment each customer uses (e.g. their credit card). Payment methods are tokenized, then charged at time of…
- [JustiFi Payments API](https://apis.io/apis/justifi/justifi-payments-api/) — To charge a payment method the desired amount, you'll use a payment. You can choose whether to charge a payment method that's already been tokenized or…
- [JustiFi Payout Holds API](https://apis.io/apis/justifi/justifi-payout-holds-api/) — A payout hold is a resource that temporarily hold or pause payouts for a sub account. This feature is used for risk management, compliance, or business rule…
- [JustiFi Payouts API](https://apis.io/apis/justifi/justifi-payouts-api/) — Each day, a payout containing that day's funds is automatically created for the purpose of distributing those funds to the active bank account. Payout…
- [JustiFi Proceeds API](https://apis.io/apis/justifi/justifi-proceeds-api/) — Proceeds represent your platform's take-home portion of the fees from your sub account's financial transactions. Proceeds are batched together according to…
- [JustiFi Provisioning API](https://apis.io/apis/justifi/justifi-provisioning-api/) — Provisioning API for Products serves as an automated interface to configure resources based on your current entities informations, for example creating an…
- [JustiFi Refunds API](https://apis.io/apis/justifi/justifi-refunds-api/) — When you refund a payment, a refund object is created. You can retrieve information about the refunds you've issued.
- [JustiFi Reports API](https://apis.io/apis/justifi/justifi-reports-api/) — Reports can be used to pull data for various different resources. They are CSV format, and can be filtered by date and sub account. Once a the create…
- [JustiFi Terminals API](https://apis.io/apis/justifi/justifi-terminals-api/) — JustiFi provides a card present solution which allows you to collect a payment via a terminal provider via one of our technology partners. To collect a…
- [JustiFi Terminals Orders API](https://apis.io/apis/justifi/justifi-terminals-orders-api/) — Terminals Orders API for order management
- [JustiFi Terms and Conditions API](https://apis.io/apis/justifi/justifi-terms-and-conditions-api/) — Legally binding rules and agreements that outline the rights, responsibilities, and limitations governing the use of the platform.
- [JustiFi Voids API](https://apis.io/apis/justifi/justifi-voids-api/) — The Voids API from JustiFi — 1 operation(s) for voids.
- [JustiFi Web Component Tokens API](https://apis.io/apis/justifi/justifi-web-component-tokens-api/) — The Web Component Tokens API from JustiFi — 1 operation(s) for web component tokens.
- [JustiFi Events API](https://apis.io/apis/justifi/justifi-events-api/) — The Events API from JustiFi — 0 operation(s) for events.
- [JustiFi Subaccounts API](https://apis.io/apis/justifi/justifi-subaccounts-api/) — Sub Accounts are the representation of your platform's customers for payment processing in JustiFi and are associated with your platform account.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Justifi Webhooks](https://apis.io/asyncapis/justifi/justifi-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [justifi](https://apis.io/servers/justifi/justifi/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Justifi Agentic Access](https://apis.io/agentic-access/justifi/justifi-agentic-access/)

#### Collections (27)

Postman and Open Collection request collections.

- [JustiFi API Documentation Ach Return Fees API](https://apis.io/collections/justifi/open-justifi-ach-return-fees-api/)
- [JustiFi API Documentation Ach Return Fees Address API](https://apis.io/collections/justifi/open-justifi-address-api/)
- [JustiFi API Documentation Ach Return Fees API Credentials API](https://apis.io/collections/justifi/open-justifi-api-credentials-api/)
- [JustiFi API Documentation Ach Return Fees Balance Transactions API](https://apis.io/collections/justifi/open-justifi-balance-transactions-api/)
- [JustiFi API Documentation Ach Return Fees Bank Account API](https://apis.io/collections/justifi/open-justifi-bank-account-api/)
- [JustiFi API Documentation Ach Return Fees Bind Insurance API](https://apis.io/collections/justifi/open-justifi-bind-insurance-api/)
- [JustiFi API Documentation Ach Return Fees Business API](https://apis.io/collections/justifi/open-justifi-business-api/)
- [JustiFi API Documentation Ach Return Fees Checkouts API](https://apis.io/collections/justifi/open-justifi-checkouts-api/)
- [JustiFi API Documentation Ach Return Fees Disputes API](https://apis.io/collections/justifi/open-justifi-disputes-api/)
- [JustiFi API Documentation Ach Return Fees Document API](https://apis.io/collections/justifi/open-justifi-document-api/)
- [JustiFi API Documentation Ach Return Fees Fee Configurations API](https://apis.io/collections/justifi/open-justifi-fee-configurations-api/)
- [JustiFi API Documentation Ach Return Fees Identity API](https://apis.io/collections/justifi/open-justifi-identity-api/)
- [JustiFi API Documentation Ach Return Fees Payment Method Groups API](https://apis.io/collections/justifi/open-justifi-payment-method-groups-api/)
- [JustiFi API Documentation Ach Return Fees Payment Methods API](https://apis.io/collections/justifi/open-justifi-payment-methods-api/)
- [JustiFi API Documentation Ach Return Fees Payments API](https://apis.io/collections/justifi/open-justifi-payments-api/)
- [JustiFi API Documentation Ach Return Fees Payout Holds API](https://apis.io/collections/justifi/open-justifi-payout-holds-api/)
- [JustiFi API Documentation Ach Return Fees Payouts API](https://apis.io/collections/justifi/open-justifi-payouts-api/)
- [JustiFi API Documentation Ach Return Fees Proceeds API](https://apis.io/collections/justifi/open-justifi-proceeds-api/)
- [JustiFi API Documentation Ach Return Fees Provisioning API](https://apis.io/collections/justifi/open-justifi-provisioning-api/)
- [JustiFi API Documentation Ach Return Fees Refunds API](https://apis.io/collections/justifi/open-justifi-refunds-api/)
- [JustiFi API Documentation Ach Return Fees Reports API](https://apis.io/collections/justifi/open-justifi-reports-api/)
- [JustiFi API Documentation Ach Return Fees Sub Accounts API](https://apis.io/collections/justifi/open-justifi-sub-accounts-api/)
- [JustiFi API Documentation Ach Return Fees Terminals API](https://apis.io/collections/justifi/open-justifi-terminals-api/)
- [JustiFi API Documentation Ach Return Fees Terminals Orders API](https://apis.io/collections/justifi/open-justifi-terminals-orders-api/)
- [JustiFi API Documentation Ach Return Fees Terms and Conditions API](https://apis.io/collections/justifi/open-justifi-terms-and-conditions-api/)
- …and 2 more published on APIs.io

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Justifi Openapi Overlay](https://apis.io/overlays/justifi/justifi-openapi-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Justifi Authentication](https://apis.io/security/justifi/justifi-authentication/)
- [Justifi Domain Security](https://apis.io/security/justifi/justifi-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.justifi.ai)
- [Documentation](https://docs.justifi.tech/)
- [Getting started](https://docs.justifi.tech/gettingStarted)
- [API reference](https://docs.justifi.tech/api-spec)
- [Pricing](https://justifi.ai/pricing)
- [Sign up](https://app.justifi.ai/signup)
- [Blog](https://justifi.ai/resources/posts)
- [Compliance](https://justifi.ai/security)
- [Privacy policy](https://justifi.ai/privacy-policy)
- [GitHub](https://github.com/justifi-tech)
- [Status](https://status.justifi.ai)

## API Evangelist rating

**Kin Score 47.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 51.0 |
| Contract governance | 18.2 |
| Operational transparency | 26.3 |
| Developer ergonomics | 75.6 |
| Access clarity | 28.9 |

**Agent readiness 37.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | verified |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | derived (partial credit) |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 30.4** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/justifi/](https://apis.io/providers/justifi/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for JustiFi: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/justifi/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
