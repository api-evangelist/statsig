# Statsig

Statsig is a feature management and experimentation platform that enables teams to ship features safely with feature flags, run A/B tests, and analyze product metrics. Their developer platform provides HTTP APIs, Console APIs, and client and server SDKs for evaluating feature gates, managing experiments, and ingesting event data at scale.

**Website:** [https://statsig.com/](https://statsig.com/)

**Documentation:** [https://docs.statsig.com/](https://docs.statsig.com/)

**Pricing:** [https://statsig.com/pricing](https://statsig.com/pricing)

**Support:** [https://statsig.com/support](https://statsig.com/support)

## APIs

### Statsig HTTP API
Server-side HTTP API for evaluating feature gates, dynamic configs, and experiments. Supports checking gate values, fetching configurations, and logging custom events.

**Human URL:** [https://docs.statsig.com/http-api/](https://docs.statsig.com/http-api/)

#### Properties
- [Documentation](https://docs.statsig.com/http-api/)
- [OpenAPI](openapi/statsig-http-api-openapi.yml)

### Statsig Console API
Management API for full CRUD operations on feature gates, experiments, dynamic configs, segments, layers, holdouts, metrics, keys, users, tags, target apps, and audit logs.

**Human URL:** [https://docs.statsig.com/console-api/](https://docs.statsig.com/console-api/)

#### Properties
- [Documentation](https://docs.statsig.com/console-api/)
- [OpenAPI](openapi/statsig-console-api-openapi.yml)

### Statsig Client SDK API
Endpoints powering client-side SDKs for JavaScript, React, React Native, iOS, Android, and Unity. Uses Client-SDK Keys safe to embed in front-end code.

**Human URL:** [https://docs.statsig.com/client/introduction](https://docs.statsig.com/client/introduction)

#### Properties
- [Documentation](https://docs.statsig.com/client/introduction)
- [OpenAPI](openapi/statsig-client-sdk-api-openapi.yml)

### Statsig Server SDK API
Endpoints powering server-side SDKs for Node.js, Python, Java, Ruby, Go, and .NET. Downloads config specs for sub-millisecond local evaluation.

**Human URL:** [https://docs.statsig.com/server/introduction](https://docs.statsig.com/server/introduction)

#### Properties
- [Documentation](https://docs.statsig.com/server/introduction)
- [OpenAPI](openapi/statsig-server-sdk-api-openapi.yml)

### Statsig Events API
High-throughput event ingestion API processing over a trillion events daily. Accepts exposure events, custom events, and diagnostic data for experimentation and analytics.

**Human URL:** [https://docs.statsig.com/http-api/](https://docs.statsig.com/http-api/)

#### Properties
- [Documentation](https://docs.statsig.com/http-api/)
- [OpenAPI](openapi/statsig-events-api-openapi.yml)
- [AsyncAPI](asyncapi/statsig-webhooks-asyncapi.yml)

## Common Properties

- [Portal](https://docs.statsig.com/)
- [Documentation](https://docs.statsig.com/)
- [Pricing](https://statsig.com/pricing)
- [Blog](https://statsig.com/blog)
- [Website](https://statsig.com/)
- [Login](https://console.statsig.com/)
- [PrivacyPolicy](https://statsig.com/privacy)
- [TermsOfService](https://statsig.com/terms)
- [Support](https://statsig.com/support)

## Artifacts

### Spectral Rules
- [Statsig Rules](rules/statsig-rules.yml)

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [Feature Management](capabilities/feature-management.yaml) | Gate evaluation, experiment management, event logging, and administration (15 tools) |

**Shared Definitions:**
- [HTTP API](capabilities/shared/http-api.yaml)
- [Console API](capabilities/shared/console-api.yaml)

### JSON Schema
- [Feature Gate Schema](json-schema/statsig-feature-gate-schema.json)
- [Experiment Schema](json-schema/statsig-experiment-schema.json)
- [Event Schema](json-schema/statsig-event-schema.json)

### JSON Structure
- [Feature Gate Structure](json-structure/statsig-feature-gate-structure.json)
- [Experiment Structure](json-structure/statsig-experiment-structure.json)
- [Event Structure](json-structure/statsig-event-structure.json)

### JSON-LD
- [Statsig Context](json-ld/statsig-context.jsonld)

### Examples
- [Check Gate](examples/statsig-check-gate-example.json)
- [Create Gate](examples/statsig-create-gate-example.json)
- [Create Experiment](examples/statsig-create-experiment-example.json)
- [Log Events](examples/statsig-log-events-example.json)
- [List Gates](examples/statsig-list-gates-example.json)

### Vocabulary
- [Statsig Vocabulary](vocabulary/statsig-vocabulary.yml)

## Authentication

| API | Key Type | Header |
|-----|----------|--------|
| HTTP API | Server Secret Key | `statsig-api-key` |
| Client SDK API | Client SDK Key | `statsig-api-key` |
| Server SDK API | Server Secret Key | `statsig-api-key` |
| Events API | SDK Key | `statsig-api-key` |
| Console API | Console API Key | `STATSIG-API-KEY` |

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
