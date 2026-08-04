# Bloomberg AIM (bloomberg-aim)

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

Bloomberg's Asset and Investment Manager (AIM) is a comprehensive buy-side solution offering global, multi-asset capabilities for portfolio management, trading, compliance, and operations. Bloomberg provides a suite of developer APIs including BLPAPI, Server API, and the Hypermedia API for programmatic access to market data, analytics, and enterprise services.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bloomberg-aim/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bloomberg-aim/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Financial Data
- Market Data
- Order Management
- Portfolio Management
- Trading

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Bloomberg Data License API

Provides programmatic access to Bloomberg's comprehensive financial, pricing, reference, regulatory, and alternative data covering over 50 million securities and 56,000 fields via the Hypermedia API (HAPI).

- **Human URL:** [https://www.bloomberg.com/professional/products/data/data-management/data-license/](https://www.bloomberg.com/professional/products/data/data-management/data-license/)
- **Base URL:** `https://api.bloomberg.com/eap`

#### Tags

- Financial Data
- Market Data
- Pricing Data
- Reference Data

#### Properties

- [Documentation](https://www.bloomberg.com/professional/support/api-library/)
- [Authentication](https://console.bloomberg.com/about/82)
- [OpenAPI](openapi/bloomberg-data-license-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomberg-data-license-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomberg-data-license-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bloomberg Server API (SAPI)

Server API delivers real-time market data, historical data, premium reference data, and calculation tools from the Bloomberg Terminal into front-office applications.

- **Human URL:** [https://www.bloomberg.com/professional/products/data/data-connectivity/server-api/](https://www.bloomberg.com/professional/products/data/data-connectivity/server-api/)

#### Tags

- Financial Analytics
- Market Data
- Real-Time Data
- Server API

#### Properties

- [Documentation](https://bloomberg.github.io/blpapi-docs/)
- [Postman Collection](collections/bloomberg-data-license-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomberg-data-license-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/bloomberg-emsx-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomberg-emsx-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/bloomberg-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomberg-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bloomberg EMSX API

The Execution Management System API allows developers to manage and automate trading for equities, futures, and options.

- **Human URL:** [https://www.bloomberg.com/professional/products/trading/execution-management-system/](https://www.bloomberg.com/professional/products/trading/execution-management-system/)
- **Base URL:** `https://localhost:3000`

#### Tags

- Equities
- Execution Management
- Order Management
- Trading

#### Properties

- [Documentation](https://emsx-api-doc.readthedocs.io/)
- [OpenAPI](openapi/bloomberg-emsx-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomberg-emsx-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomberg-emsx-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bloomberg HTTP API

Makes the Bloomberg Open API available via HTTP and WebSockets, allowing clients to access reference and historical request-response data as well as subscribe to live streaming market data.

- **Human URL:** [https://github.com/bloomberg/blpapi-http](https://github.com/bloomberg/blpapi-http)
- **Base URL:** `https://localhost:3000`

#### Tags

- Historical Data
- HTTP API
- Market Data
- Reference Data
- Streaming

#### Properties

- [Documentation](https://github.com/bloomberg/blpapi-http)
- [OpenAPI](openapi/bloomberg-http-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomberg-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomberg-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub Repository](https://github.com/bloomberg/blpapi-http)

## Common Properties

- [Portal](https://developer.bloomberg.com/)
- [Documentation](https://bloomberg.github.io/blpapi-docs/)
- [Getting Started](https://data.bloomberglp.com/professional/sites/10/2017/03/BLPAPI-Core-Developer-Guide.pdf)
- [Console](https://console.bloomberg.com/)
- [Terms of Service](https://www.bloomberg.com/notices/tos/)
- [Privacy Policy](https://www.bloomberg.com/notices/)
- [Blog](https://www.bloomberg.com/company/stories/category/tech-at-bloomberg/)
- [GitHub Organization](https://github.com/bloomberg)
- [SDK](https://github.com/bloomberg/blpapi-node)
- [SDK](https://github.com/bloomberg/blpapi-python)
- [SDK](https://github.com/bloomberg/blpapi-java)
- [Features](https://www.bloomberg.com/professional/products/data/)
- [Use Cases](https://www.bloomberg.com/professional/)
- [Integrations](https://www.bloomberg.com/professional/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
