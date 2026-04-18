# Bloomberg AIM (bloomberg-aim)

Bloomberg's Asset and Investment Manager (AIM) is a comprehensive buy-side solution offering global, multi-asset capabilities for portfolio management, trading, compliance, and operations. Bloomberg provides a suite of developer APIs including BLPAPI, Server API, and the Hypermedia API for programmatic access to market data, analytics, and enterprise services.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/bloomberg-aim/refs/heads/main/apis.yml)

## Tags

Financial Data, Market Data, Order Management, Portfolio Management, Trading

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-18

## APIs

### Bloomberg Data License API
Provides programmatic access to Bloomberg's comprehensive financial, pricing, reference, regulatory, and alternative data covering over 50 million securities and 56,000 fields via the Hypermedia API (HAPI).

**Human URL:** [https://www.bloomberg.com/professional/products/data/data-management/data-license/](https://www.bloomberg.com/professional/products/data/data-management/data-license/)

#### Tags

Financial Data, Market Data, Pricing Data, Reference Data

#### Properties

- [Documentation](https://www.bloomberg.com/professional/support/api-library/)
- [OpenAPI](openapi/bloomberg-data-license-api.yml)
- [Authentication](https://console.bloomberg.com/about/82)

### Bloomberg Server API (SAPI)
Server API delivers real-time market data, historical data, premium reference data, and calculation tools from the Bloomberg Terminal into front-office applications.

**Human URL:** [https://www.bloomberg.com/professional/products/data/data-connectivity/server-api/](https://www.bloomberg.com/professional/products/data/data-connectivity/server-api/)

#### Tags

Financial Analytics, Market Data, Real-Time Data, Server API

#### Properties

- [Documentation](https://bloomberg.github.io/blpapi-docs/)

### Bloomberg EMSX API
The Execution Management System API allows developers to manage and automate trading for equities, futures, and options.

**Human URL:** [https://www.bloomberg.com/professional/products/trading/execution-management-system/](https://www.bloomberg.com/professional/products/trading/execution-management-system/)

#### Tags

Equities, Execution Management, Order Management, Trading

#### Properties

- [Documentation](https://emsx-api-doc.readthedocs.io/)
- [OpenAPI](openapi/bloomberg-emsx-api.yml)

### Bloomberg HTTP API
Makes the Bloomberg Open API available via HTTP and WebSockets for reference data, historical data, and live streaming market data.

**Human URL:** [https://github.com/bloomberg/blpapi-http](https://github.com/bloomberg/blpapi-http)

#### Tags

Historical Data, HTTP API, Market Data, Reference Data, Streaming

#### Properties

- [Documentation](https://github.com/bloomberg/blpapi-http)
- [OpenAPI](openapi/bloomberg-http-api.yml)
- [GitHubRepository](https://github.com/bloomberg/blpapi-http)

## Capabilities

### Shared Per-API Definitions (capabilities/shared/)

| File | API |
|------|-----|
| [data-license.yaml](capabilities/shared/data-license.yaml) | Bloomberg Data License API (HAPI) |
| [emsx.yaml](capabilities/shared/emsx.yaml) | Bloomberg EMSX API |
| [http-api.yaml](capabilities/shared/http-api.yaml) | Bloomberg HTTP API |

### Workflow Capabilities

| File | Workflow | APIs Combined |
|------|----------|---------------|
| [market-data-and-analytics.yaml](capabilities/market-data-and-analytics.yaml) | Market Data and Analytics | Data License + HTTP API |
| [trading-and-execution.yaml](capabilities/trading-and-execution.yaml) | Trading and Execution | EMSX + HTTP API |

## Artifacts

### OpenAPI Specifications (openapi/)

- [bloomberg-data-license-api.yml](openapi/bloomberg-data-license-api.yml)
- [bloomberg-emsx-api.yml](openapi/bloomberg-emsx-api.yml)
- [bloomberg-http-api.yml](openapi/bloomberg-http-api.yml)

### Spectral Rules (rules/)

- [bloomberg-aim-spectral-rules.yml](rules/bloomberg-aim-spectral-rules.yml)

### JSON Schema (json-schema/)

- [order.json](json-schema/order.json)
- [portfolio.json](json-schema/portfolio.json)
- [position.json](json-schema/position.json)
- [security.json](json-schema/security.json)
- [trade.json](json-schema/trade.json)
- Plus 73 API-specific schema files

### JSON-LD (json-ld/)

- [context.jsonld](json-ld/context.jsonld)
- Plus 3 API-specific context files

### Examples (examples/)

- 79 example files covering all API schemas

### Vocabulary (vocabulary/)

- [bloomberg-aim-vocabulary.yaml](vocabulary/bloomberg-aim-vocabulary.yaml)

## Common Properties

- [Portal](https://developer.bloomberg.com/)
- [Documentation](https://bloomberg.github.io/blpapi-docs/)
- [Console](https://console.bloomberg.com/)
- [GitHub Organization](https://github.com/bloomberg)
- [SDK (Python)](https://github.com/bloomberg/blpapi-python)
- [SDK (Java)](https://github.com/bloomberg/blpapi-java)
- [SDK (Node.js)](https://github.com/bloomberg/blpapi-node)
- [Blog](https://www.bloomberg.com/company/stories/category/tech-at-bloomberg/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
