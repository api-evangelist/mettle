# Mettle (mettle)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Mettle is a digital-only business bank account brand for UK sole traders, freelancers, and small limited companies, wholly owned by NatWest Group and originally built with Capco. It has no physical branches and runs on separate technology from the core NatWest bank. As a NatWest Group brand, Mettle participates in UK Open Banking through NatWest Group's "Bank of APIs" developer platform, publishing PSD2 / OBIE-conformant APIs: a public, unsecured Open Data (Product) API plus the FAPI-secured Read/Write family (Account & Transaction Information, Payment Initiation, and Confirmation of Funds).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mettle/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mettle/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Business Banking
- Open Banking
- PSD2
- OBIE
- FAPI
- United Kingdom
- Payments
- Account Information
- Challenger Bank
- Fintech

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### Mettle Open Data Product API

Mettle's public, unsecured UK Open Banking Open Data (Product) API, exposing reference information about the business current accounts Mettle offers to sole traders and limited companies. Conforms to the OBIE Open Data API standard; no credentials required to read.

- **Human URL:** [https://www.bankofapis.com/products/natwest-group-open-banking/products-and-locations/documentation/mettle](https://www.bankofapis.com/products/natwest-group-open-banking/products-and-locations/documentation/mettle)
- **Base URL:** `https://api.openbanking.prd-mettle.co.uk/open-banking/v2.3`

#### Tags

- Open Data
- Business Current Accounts
- Products

#### Properties

- [OpenAPI](openapi/mettle-open-data-api-openapi.json) — shared OBIE Open Data API standard (Swagger 2.0, v1.3), not a Mettle-proprietary contract
- [Documentation](https://www.bankofapis.com/products/natwest-group-open-banking/products-and-locations/documentation/mettle)
- [API Reference](https://www.bankofapis.com/products/natwest-group-open-banking/products-and-locations/documentation/mettle)

### Mettle Account and Transaction API

OBIE Read/Write Account & Transaction Information (AIS) API for Mettle business current accounts, exposing accounts, balances, transactions, and related resources to FCA-authorised third parties. FAPI-secured with OAuth2/OIDC, mTLS, and PSD2 strong customer authentication.

- **Human URL:** [https://www.bankofapis.com/products/accounts/documentation/mettle](https://www.bankofapis.com/products/accounts/documentation/mettle)
- **Base URL:** `https://api.openbanking.prd-mettle.co.uk/open-banking/v3.1/aisp`

#### Tags

- Account Information
- Transactions
- AIS

#### Properties

- [Documentation](https://www.bankofapis.com/products/accounts/documentation/mettle)
- [API Reference](https://www.bankofapis.com/products/accounts/documentation/mettle)

### Mettle Payment Initiation API

OBIE Read/Write Payment Initiation Services (PIS) API for Mettle, allowing FCA-authorised third parties to initiate payments from a customer's Mettle account with their consent. FAPI-secured with OAuth2/OIDC, mTLS, and PSD2 strong customer authentication.

- **Human URL:** [https://www.bankofapis.com/products/payments/documentation/mettle](https://www.bankofapis.com/products/payments/documentation/mettle)
- **Base URL:** `https://api.openbanking.prd-mettle.co.uk/open-banking/v3.1/pisp`

#### Tags

- Payment Initiation
- Payments
- PIS

#### Properties

- [Documentation](https://www.bankofapis.com/products/payments/documentation/mettle)
- [API Reference](https://www.bankofapis.com/products/payments/documentation/mettle)

### Mettle Confirmation of Funds API

OBIE Read/Write Confirmation of Funds (CBPII) API for Mettle, letting card-based payment instrument issuers confirm whether funds are available on a customer's Mettle account. FAPI-secured with OAuth2/OIDC, mTLS, and PSD2 strong customer authentication.

- **Human URL:** [https://www.bankofapis.com/products/card-based-payments/documentation/mettle](https://www.bankofapis.com/products/card-based-payments/documentation/mettle)
- **Base URL:** `https://api.openbanking.prd-mettle.co.uk/open-banking/v3.1/cbpii`

#### Tags

- Confirmation of Funds
- CBPII
- Funds Check

#### Properties

- [Documentation](https://www.bankofapis.com/products/card-based-payments/documentation/mettle)
- [API Reference](https://www.bankofapis.com/products/card-based-payments/documentation/mettle)

## Common Properties

- [Website](https://www.mettle.co.uk/)
- [Developer Portal](https://www.bankofapis.com/)
- [Documentation](https://www.bankofapis.com/products/natwest-group-open-banking/products-and-locations/documentation/mettle)
- [Status Page](https://www.bankofapis.com/performance/service-interruptions)
- [Blog](https://www.mettle.co.uk/blog/)
- [LinkedIn](https://www.linkedin.com/company/join-mettle)
- [Support](https://www.mettle.co.uk/contact-us/)
- [Terms of Service](https://www.mettle.co.uk/docs/terms-and-conditions/1.5.pdf)
- [Privacy Policy](https://www.mettle.co.uk/privacy-notice/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
