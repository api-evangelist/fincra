# Fincra (fincra)

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
