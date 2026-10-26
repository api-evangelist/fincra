# Fincra (fincra)

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

Fincra is an African cross-border payments infrastructure provider whose REST API lets businesses collect, hold, convert, and disburse money across multiple currencies. The platform covers collections (virtual accounts and direct charges), payouts/disbursements to banks and mobile money, FX conversions with quotes, beneficiary management, and webhooks, secured with an api-key plus Bearer token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fincra/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fincra/refs/heads/main/apis.yml)

## Tags

- Payments
- Cross-Border
- Collections
- Payouts
- FX
- Fintech
- Africa

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Fincra Collections API

Receive payments from customers via virtual account bank transfers and the direct charge API (card, bank transfer, mobile money, EFT, pay-attitude), including charge authorization, verification, and deposit lookups.

- **Human URL:** [https://docs.fincra.com/docs/collections-overview](https://docs.fincra.com/docs/collections-overview)
- **Base URL:** `https://api.fincra.com`

#### Tags

- Collections
- Pay-ins
- Charges

#### Properties

- [Documentation](https://docs.fincra.com/docs/collections-overview)
- [API Reference](https://docs.fincra.com/reference/initiate-a-charge)
- [OpenAPI](openapi/fincra-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fincra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fincra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fincra Payouts / Disbursements API

Disburse funds to bank accounts, mobile money wallets, and other Fincra accounts in same-currency or cross-currency flows, with payout status lookups by transaction reference or customer reference.

- **Human URL:** [https://docs.fincra.com/docs/payout-overview](https://docs.fincra.com/docs/payout-overview)
- **Base URL:** `https://api.fincra.com`

#### Tags

- Payouts
- Disbursements
- Transfers

#### Properties

- [Documentation](https://docs.fincra.com/docs/payout-overview)
- [API Reference](https://docs.fincra.com/reference/initiate-payout)
- [OpenAPI](openapi/fincra-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fincra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fincra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fincra Conversions / FX API

Convert balances between supported currencies using a quote reference, list conversions, and verify conversion status. FX quotes are valid for 30 seconds on cross-currency flows.

- **Human URL:** [https://docs.fincra.com/docs/conversions](https://docs.fincra.com/docs/conversions)
- **Base URL:** `https://api.fincra.com`

#### Tags

- Conversions
- FX
- Currency Exchange

#### Properties

- [Documentation](https://docs.fincra.com/docs/conversions)
- [API Reference](https://docs.fincra.com/reference/initiate-currency-conversion)
- [OpenAPI](openapi/fincra-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fincra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fincra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fincra Quotes API

Generate a time-bound FX quote for a conversion or cross-currency payout; the returned quote reference is passed into the conversion or payout request.

- **Human URL:** [https://docs.fincra.com/reference/generate-quote](https://docs.fincra.com/reference/generate-quote)
- **Base URL:** `https://api.fincra.com`

#### Tags

- Quotes
- FX Rates
- Pricing

#### Properties

- [Documentation](https://docs.fincra.com/docs/conversions)
- [API Reference](https://docs.fincra.com/reference/generate-quote)
- [OpenAPI](openapi/fincra-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fincra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fincra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fincra Beneficiaries API

Create, list, fetch, update, and delete reusable payout beneficiaries scoped to a business, capturing bank, currency, and payment-destination details.

- **Human URL:** [https://docs.fincra.com/reference/create-a-beneficiary](https://docs.fincra.com/reference/create-a-beneficiary)
- **Base URL:** `https://api.fincra.com`

#### Tags

- Beneficiaries
- Recipients

#### Properties

- [Documentation](https://docs.fincra.com/docs/beneficiaries)
- [API Reference](https://docs.fincra.com/reference/create-a-beneficiary)
- [OpenAPI](openapi/fincra-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fincra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fincra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fincra Virtual Accounts API

Request and manage NGN and foreign-currency virtual accounts that let merchants receive bank-transfer payments, fetch account information, and list payins/deposits made into an account.

- **Human URL:** [https://docs.fincra.com/docs/fincra-virtual-accounts](https://docs.fincra.com/docs/fincra-virtual-accounts)
- **Base URL:** `https://api.fincra.com`

#### Tags

- Virtual Accounts
- Multicurrency
- Accounts

#### Properties

- [Documentation](https://docs.fincra.com/docs/fincra-virtual-accounts)
- [API Reference](https://docs.fincra.com/reference/ngn-virtual-account-api)
- [OpenAPI](openapi/fincra-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fincra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fincra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fincra Banks & Account Resolution API

List supported banks and mobile money providers and resolve/verify a bank account number to its account holder name before disbursing.

- **Human URL:** [https://docs.fincra.com/reference/list-banks](https://docs.fincra.com/reference/list-banks)
- **Base URL:** `https://api.fincra.com`

#### Tags

- Banks
- Account Verification
- Utilities

#### Properties

- [Documentation](https://docs.fincra.com/docs/verify-iban-and-account-numbers)
- [API Reference](https://docs.fincra.com/reference/list-banks)
- [OpenAPI](openapi/fincra-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fincra.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fincra.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fincra Webhooks

Signed event notifications delivered to a merchant-configured webhook URL for collections, payouts, conversions, and virtual account events, validated via an HMAC signature header.

- **Human URL:** [https://docs.fincra.com/docs/webhooks](https://docs.fincra.com/docs/webhooks)
- **Base URL:** `https://api.fincra.com`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.fincra.com/docs/webhooks)
- [Documentation](https://docs.fincra.com/docs/securing-your-webhook)
- [OpenAPI](openapi/fincra-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/fincra)
- [Website](https://www.fincra.com)
- [Documentation](https://docs.fincra.com)
- [Plans](plans/fincra-plans-pricing.yml)
- [Rate Limits](rate-limits/fincra-rate-limits.yml)
- [Fin Ops](finops/fincra-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
