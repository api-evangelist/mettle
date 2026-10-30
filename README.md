# Mettle

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

Mettle is a digital-only business bank account brand for UK sole traders, freelancers, and small limited companies, wholly owned by NatWest Group and originally built with Capco. It has no physical branches and is run on separate technology from the core NatWest bank, offering an app-based current account with a UK sort code and account number, invoicing, bookkeeping, tax tools, and a free FreeAgent accounting integration. As a NatWest Group brand, Mettle participates in UK Open Banking through NatWest Group's "Bank of APIs" developer platform, publishing PSD2 / OBIE-conformant APIs - a public, unsecured Open Data (Product) API describing its business current accounts, plus the FAPI-secured Read/Write family (Account & Transaction Information, Payment Initiation, and Confirmation of Funds). Read/Write access runs against a live production gateway (api.openbanking.prd-mettle.co.uk) secured with OAuth2/OIDC, mutual-TLS client authentication, and PSD2 strong customer authentication using OBIE/eIDAS certificates, onboarded via the Bank of APIs portal. Mettle is delivered under NatWest Group's FCA-authorised banking group and is a challenger/digital proposition rather than one of the CMA9 mandated brands.

**Areas:** Financial Services · Banking · Business Banking · Open Banking · PSD2 · OBIE · FAPI · United Kingdom · Payments · Account Information · Challenger Bank · Fintech

## Mettle on APIs.io

Everything profiled for Mettle is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/mettle/](https://apis.io/providers/mettle/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Mettle Account and Transaction API](https://apis.io/apis/mettle/mettle-account-transaction-api/) — OBIE Read/Write Account & Transaction Information (AIS) API for Mettle business current accounts, exposing accounts, balances, transactions, and related…
- [Mettle Payment Initiation API](https://apis.io/apis/mettle/mettle-payment-initiation-api/) — OBIE Read/Write Payment Initiation Services (PIS) API for Mettle, allowing FCA-authorised third parties to initiate domestic and other payments from a…
- [Mettle Confirmation of Funds API](https://apis.io/apis/mettle/mettle-confirmation-of-funds-api/) — OBIE Read/Write Confirmation of Funds (CBPII) API for Mettle, letting card-based payment instrument issuers confirm whether funds are available on a…
- [Mettle ATM API](https://apis.io/apis/mettle/mettle-atm-api/) — Endpoint for getting ATM data
- [Mettle BCA API](https://apis.io/apis/mettle/mettle-bca-api/) — Endpoint for getting Business Current Account data
- [Mettle Branch API](https://apis.io/apis/mettle/mettle-branch-api/) — Endpoint for getting Branch data
- [Mettle CCC API](https://apis.io/apis/mettle/mettle-ccc-api/) — Endpoint for getting Commercial Credit Card data
- [Mettle PCA API](https://apis.io/apis/mettle/mettle-pca-api/) — Endpoint for getting Personal Current Account data
- [Mettle SME API](https://apis.io/apis/mettle/mettle-sme-api/) — Endpoint for getting Unsecured SME Loan data

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [mettle-open-data](https://apis.io/servers/mettle/mettle-open-data/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Mettle Agentic Access](https://apis.io/agentic-access/mettle/mettle-agentic-access/)

#### Collections (1)

Postman and Open Collection request collections.

- [Open Data API](https://apis.io/collections/mettle/open-mettle-open-data-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Mettle Open Data Api Overlay](https://apis.io/overlays/mettle/mettle-open-data-api-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Mettle Authentication](https://apis.io/security/mettle/mettle-authentication/)
- [Mettle Domain Security](https://apis.io/security/mettle/mettle-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Mettle Scopes](https://apis.io/scopes/mettle/mettle-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.mettle.co.uk/)
- [Documentation](https://www.bankofapis.com/products/natwest-group-open-banking/products-and-locations/documentation/mettle)
- [Support](https://www.mettle.co.uk/contact-us/)
- [Blog](https://www.mettle.co.uk/blog/)
- [Compliance](https://www.bankofapis.com/products/natwest-group-open-banking)
- [Terms of service](https://www.mettle.co.uk/docs/terms-and-conditions/1.5.pdf)
- [Privacy policy](https://www.mettle.co.uk/privacy-notice/)
- [Status](https://www.bankofapis.com/performance/service-interruptions)

## API Evangelist rating

**Kin Score 37.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 35.5 |
| Contract governance | 18.2 |
| Operational transparency | 0.0 |
| Developer ergonomics | 20.8 |
| Access clarity | 57.1 |

**Agent readiness 36.5** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | na |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |

**Regulatory alignment 44.1** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/mettle/](https://apis.io/providers/mettle/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Mettle: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/mettle/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
