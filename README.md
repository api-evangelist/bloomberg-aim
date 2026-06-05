# Bloomberg AIM (bloomberg-aim)

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
