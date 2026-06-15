# statsig (statsig)

Statsig is a feature management and experimentation platform that helps product teams ship features safely with feature flags, run A/B tests, and measure the impact of every feature on key metrics.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Statsig HTTP API

The Statsig HTTP API allows developers to evaluate feature gates, dynamic configs, and experiments for users via server-side HTTP requests. It provides endpoints for checking gate values, fetching configuration data, and logging custom events. All requests use the POST method with JSON request bodies and require authentication via the statsig-api-key header.

- **Human URL:** [https://docs.statsig.com/http-api/](https://docs.statsig.com/http-api/)
- **Base URL:** `https://api.statsig.com`

#### Tags

- A/B Testing
- Analytics
- Dynamic Configuration
- Experimentation
- Feature Flags

#### Properties

- [Documentation](https://docs.statsig.com/http-api/)
- [OpenAPI](openapi/statsig-http-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/statsig-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/statsig-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Statsig Console API

The Statsig Console API enables developers to programmatically manage their Statsig project configuration. It supports full CRUD operations on feature gates, dynamic configs, experiments, segments, layers, and other entities. The API requires a Console API Key and uses versioned endpoints with the STATSIG-API-VERSION header.

- **Human URL:** [https://docs.statsig.com/console-api/](https://docs.statsig.com/console-api/)
- **Base URL:** `https://statsigapi.net/console/v1`

#### Tags

- Administration
- Automation
- Configuration Management
- Experimentation
- Feature Flags

#### Properties

- [Documentation](https://docs.statsig.com/console-api/)
- [OpenAPI](openapi/statsig-console-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/statsig-console-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/statsig-console-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Statsig Client SDK API

The Statsig Client SDK API provides endpoints that power Statsig's client-side SDKs for JavaScript, React, React Native, iOS, Android, Unity, and other platforms. Client SDKs use Client-SDK Keys that are safe to embed in mobile apps and front-end web applications. They access the initialize endpoint to retrieve all evaluated gates, configs, and experiments for a given user, and the log_event endpoint for sending analytics events.

- **Human URL:** [https://docs.statsig.com/client/introduction](https://docs.statsig.com/client/introduction)
- **Base URL:** `https://api.statsig.com`

#### Tags

- Client Side
- Feature Flags
- Mobile
- SDKs
- Web

#### Properties

- [Documentation](https://docs.statsig.com/client/introduction)
- [OpenAPI](openapi/statsig-client-sdk-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/statsig-client-sdk-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/statsig-client-sdk-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Statsig Server SDK API

The Statsig Server SDK API provides endpoints that power Statsig's server-side SDKs for Node.js, Python, Java, Ruby, Go, .NET, and other backend languages. Server SDKs use Server Secret Keys and access the download_config_specs endpoint to retrieve the full project configuration for local evaluation. This enables sub-millisecond feature gate checks without per-request network calls.

- **Human URL:** [https://docs.statsig.com/server/introduction](https://docs.statsig.com/server/introduction)
- **Base URL:** `https://api.statsig.com`

#### Tags

- Backend
- Evaluation
- Feature Flags
- SDKs
- Server Side

#### Properties

- [Documentation](https://docs.statsig.com/server/introduction)
- [OpenAPI](openapi/statsig-server-sdk-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/statsig-server-sdk-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/statsig-server-sdk-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Statsig Events API

The Statsig Events API handles the ingestion of event data from both client and server SDKs. It receives exposure events, custom events, and diagnostic data at the events.statsigapi.net endpoint. This data powers Statsig's experimentation analysis, product analytics, and metric computations. The Events API is optimized for high-throughput data ingestion, processing over a trillion events daily with high reliability and low latency, enabling real-time experiment monitoring and metric updates.

- **Human URL:** [https://docs.statsig.com/http-api/](https://docs.statsig.com/http-api/)
- **Base URL:** `https://events.statsigapi.net`

#### Tags

- Analytics
- Data Ingestion
- Events
- Logging
- Metrics

#### Properties

- [Documentation](https://docs.statsig.com/http-api/)
- [OpenAPI](openapi/statsig-events-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/statsig-events-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/statsig-events-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/statsig-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

## Common Properties

- [GitHub Organization](https://github.com/statsig-io)
- [LinkedIn](https://www.linkedin.com/company/statsig)
- [JSON-LD](json-ld/statsig-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/statsig-feature-gate-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/statsig-experiment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/statsig-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/statsig-feature-gate-structure.json)
- [JSON Structure](json-structure/statsig-experiment-structure.json)
- [JSON Structure](json-structure/statsig-event-structure.json)
- [Spectral Rules](rules/statsig-rules.yml)
- [Vocabulary](vocabulary/statsig-vocabulary.yml)
- [Integrations](https://docs.statsig.com/integrations/mcp/overview)
- [L L Ms Txt](https://docs.statsig.com/llms.txt)
