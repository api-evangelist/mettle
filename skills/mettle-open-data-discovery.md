---
name: Discover Mettle published products and locations
description: >-
  Read Mettle's public Open Data (Product) API to list published business current
  accounts and other product/location reference data. No credentials required.
api: openapi/mettle-open-data-api-openapi.json
operations:
- GET /business-current-accounts
- GET /personal-current-accounts
- GET /commercial-credit-cards
- GET /unsecured-sme-loans
- GET /branches
- GET /atms
---

# Discover Mettle published products and locations

Mettle's Open Data (Product) API is a public, unsecured OBIE Open Data endpoint —
no OAuth token, mTLS certificate, or consent is needed. Use it to read reference
information about the products Mettle publishes.

## Base URL

```
https://api.openbanking.prd-mettle.co.uk/open-banking/v2.3
```

## Steps

1. **List business current accounts.** `GET /business-current-accounts` returns the
   published Mettle business current account products (features, eligibility, fees,
   rates). This is Mettle's marquee product for sole traders and limited companies.
2. **List other product families as needed** with `GET /personal-current-accounts`,
   `GET /commercial-credit-cards`, and `GET /unsecured-sme-loans`.
3. **List locations** with `GET /branches` and `GET /atms` (Mettle is branchless;
   these reflect the NatWest Group Open Data location model).
4. **Paginate** via the OBIE `Links` (`Self`/`Next`) and `Meta.TotalPages` blocks
   when a collection spans multiple pages.

## Conventions

- Read-only reference data; safe for agent exposure (`x-agentic-access: connected/read`).
- On `429 Too Many Requests`, back off and retry.
- For live customer account data, balances, transactions, or payments, use the
  FAPI-secured Read/Write APIs instead — those require OAuth2 + mTLS + PSD2 SCA
  (see authentication/mettle-authentication.yml).
