# Rutter (rutter)

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

Rutter is the leading unified RESTful API for B2B financial products that connects to over 60 commerce, payments, accounting, and ads platforms through a single API. Trusted by companies like Airwallex, Mercury, and Ramp, Rutter enables developers to read, update, write, and remove data across major business platforms with a unified data model and idempotency guarantees for financial data. The API supports OAuth2 and Basic authentication, versioning via the X-Rutter-Version header, cursor-based pagination, and asynchronous request processing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Accounting
- B2B
- Commerce
- Financial Data
- Payments
- Unified API

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Rutter Unified API

The Rutter Unified API provides a single RESTful interface to over 60 commerce, payments, and accounting platforms. It supports connection management, accounting data (accounts, transactions, invoices, bills, expenses), commerce data (orders, products, customers), payments data, ads data, and banking data through a versioned API with cursor pagination and idempotent writes.

- **Human URL:** [https://docs.rutter.com/](https://docs.rutter.com/)
- **Base URL:** `https://production.rutterapi.com/versioned`

#### Tags

- Accounting
- B2B
- Commerce
- Financial Data
- Payments
- Unified API

#### Properties

- [Documentation](https://docs.rutter.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/openapi/rutter-unified-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rutter-unified-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rutter-unified-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rutter Commerce API

The Rutter Commerce API enables reading and writing data to all major commerce platforms through a unified API, supporting platforms like Shopify, WooCommerce, Amazon, and more.

- **Human URL:** [https://www.rutter.com/product/commerce-api](https://www.rutter.com/product/commerce-api)

#### Tags

- Commerce
- E-Commerce
- Unified API

#### Properties

- [Documentation](https://docs.rutter.com/)
- [Product Page](https://www.rutter.com/product/commerce-api)
- [Postman Collection](collections/rutter-unified-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rutter-unified-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rutter Accounting API

The Rutter Accounting API provides a unified interface to read and write data to all major accounting platforms including QuickBooks, Xero, Freshbooks, and Zoho Books.

- **Human URL:** [https://www.rutter.com/product/accounting-api](https://www.rutter.com/product/accounting-api)

#### Tags

- Accounting
- Financial Data
- Unified API

#### Properties

- [Documentation](https://docs.rutter.com/)
- [Product Page](https://www.rutter.com/product/accounting-api)
- [Postman Collection](collections/rutter-unified-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rutter-unified-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rutter Payments API

The Rutter Payments API provides a unified interface to read and write data to all major payment platforms through a single REST API.

- **Human URL:** [https://www.rutter.com/product/payments-api](https://www.rutter.com/product/payments-api)

#### Tags

- Financial Data
- Payments
- Unified API

#### Properties

- [Documentation](https://docs.rutter.com/)
- [Product Page](https://www.rutter.com/product/payments-api)
- [Postman Collection](collections/rutter-unified-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rutter-unified-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rutterapi)
- [Website](https://www.rutter.com/)
- [Documentation](https://docs.rutter.com/)
- [Pricing](https://www.rutter.com/pricing)
- [Blog](https://www.rutter.com/blog)
- [Integrations](https://www.rutter.com/integrations)
- [A P Is](https://www.rutter.com/our-features/apis)
- [Sign Up](https://dashboard.rutterapi.com/sign-up)
- [Git Hub](https://github.com/rutter)
- [SDK](https://github.com/rutter/react-rutter-link)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/vocabulary/rutter-vocabulary.yml)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-ld/rutter-context.jsonld)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/rules/rutter-spectral-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-schema/rutter-connection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-schema/rutter-invoice-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-schema/rutter-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [L L Ms Txt](https://dashboard.rutterapi.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
