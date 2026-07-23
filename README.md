# Steinbach Credit Union (steinbach-credit-union)

Steinbach Credit Union (SCU) is a member-owned financial cooperative founded in 1941 and headquartered in Steinbach, Manitoba, Canada. With more than CA$10 billion in assets and over 115,000 consumer, business, and agricultural members, SCU is the largest credit union in Manitoba and among the ten largest in Canada. It is a provincially chartered co-operative regulated in Manitoba, with deposits guaranteed by the Manitoba Deposit Guarantee Corporation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/steinbach-credit-union/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/steinbach-credit-union/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Canada
- Credit Union
- Cooperative
- Manitoba
- Interac
- Data Aggregation
- Open Banking

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## Open Finance & API Posture

Steinbach Credit Union exposes **no public first-party developer API or developer portal**. Probes of `developer.scu.mb.ca` and `api.scu.mb.ca` do not resolve, and no OpenAPI/Swagger definition is publicly downloadable.

This is the honest, common posture for a Canadian credit union:

- **Consumer-Driven Banking (CDB):** Canada's federal open-banking / consumer-driven banking framework (Budget 2024 and the Fall Economic Statement 2024, overseen by the Financial Consumer Agency of Canada) is legislated but **not yet operational**. Open finance in Canada is therefore voluntary and fragmented, and SCU publishes no CDB or FDX participation statement.
- **Core banking platform:** SCU's digital banking (online portal `online.scu.mb.ca` and its mobile app) runs on the **Celero** core banking platform — the credit-union technology provider is where any integration surface would live, not a first-party SCU API.
- **Aggregator access:** Consumer-permissioned access to SCU account data today is **aggregator-mediated** (screen-scraping / credential-based), primarily via **Flinks** (the National Bank-owned Canadian aggregator) and **Plaid**, rather than a first-party API.
- **Canadian rails:** Interbank money movement uses the shared Canadian rails via **Interac e-Transfer**; SCU documents Interac e-Transfer as a consumer feature but does not expose an API around it.

## APIs

None. Steinbach Credit Union does not document a public API. See the posture notes above and `review.yml` for the full reviewer finding.

## Common Properties

- [Website](https://scu.mb.ca/)
- [LinkedIn](https://www.linkedin.com/company/steinbach-credit-union)
- [Privacy Policy](https://scu.mb.ca/privacy)
- [Terms of Service](https://scu.mb.ca/legal)
- [Support](https://scu.mb.ca/contact-us)
- [Interac e-Transfer](https://scu.mb.ca/ways-to-bank/interac-e-transfer)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
