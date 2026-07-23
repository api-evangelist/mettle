# Mettle (mettle)

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
