# Statsig (statsig)
Statsig is a feature management and experimentation platform that enables teams to ship features safely with feature flags, run A/B tests, and analyze product metrics. Their developer platform provides HTTP APIs, Console APIs, and client and server SDKs for evaluating feature gates, managing experiments, and ingesting event data at scale.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Feature Flags, Experimentation, A/B Testing, Analytics, Configuration Management

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-03-20

## APIs

### Statsig HTTP API
The Statsig HTTP API allows developers to evaluate feature gates, dynamic configs, and experiments for users via server-side HTTP requests. It provides endpoints for checking gate values, fetching configuration data, and logging custom events. All requests use the POST method with JSON request bodies and require authentication via the statsig-api-key header. While Statsig recommends using their official SDKs for most use cases, the HTTP API is available for environments where an SDK is not available or when direct HTTP integration is preferred.

**Human URL:** [https://docs.statsig.com/http-api/](https://docs.statsig.com/http-api/)


#### Tags:

 - Feature Flags, Experimentation, A/B Testing, Dynamic Configuration, Analytics

#### Properties

- [Documentation](https://docs.statsig.com/http-api/)
- [OpenAPI](openapi/statsig-http-api-openapi.yml)

### Statsig Console API
The Statsig Console API enables developers to programmatically manage their Statsig project configuration. It supports full CRUD operations on feature gates, dynamic configs, experiments, segments, layers, and other entities. The API requires a Console API Key and uses versioned endpoints with the STATSIG-API-VERSION header. It is designed for automation workflows such as bulk configuration edits, syncing definitions into Statsig from external systems, and integrating Statsig management into CI/CD pipelines.

**Human URL:** [https://docs.statsig.com/console-api/](https://docs.statsig.com/console-api/)


#### Tags:

 - Feature Flags, Experimentation, Configuration Management, Administration, Automation

#### Properties

- [Documentation](https://docs.statsig.com/console-api/)
- [OpenAPI](openapi/statsig-console-api-openapi.yml)

### Statsig Client SDK API
The Statsig Client SDK API provides endpoints that power Statsig's client-side SDKs for JavaScript, React, React Native, iOS, Android, Unity, and other platforms. Client SDKs use Client-SDK Keys that are safe to embed in mobile apps and front-end web applications. They access the initialize endpoint to retrieve all evaluated gates, configs, and experiments for a given user, and the log_event endpoint for sending analytics events. The SDKs handle local evaluation, caching, and automatic error handling for performant client-side feature flagging.

**Human URL:** [https://docs.statsig.com/client/introduction](https://docs.statsig.com/client/introduction)


#### Tags:

 - Feature Flags, Client Side, Mobile, Web, SDKs

#### Properties

- [Documentation](https://docs.statsig.com/client/introduction)
- [OpenAPI](openapi/statsig-client-sdk-api-openapi.yml)

### Statsig Server SDK API
The Statsig Server SDK API provides endpoints that power Statsig's server-side SDKs for Node.js, Python, Java, Ruby, Go, .NET, and other backend languages. Server SDKs use Server Secret Keys and access the download_config_specs endpoint to retrieve the full project configuration for local evaluation. This enables sub-millisecond feature gate checks without per-request network calls. The server SDKs also use the log_event endpoint for sending exposure and custom event data back to Statsig for analytics and experiment analysis.

**Human URL:** [https://docs.statsig.com/server/introduction](https://docs.statsig.com/server/introduction)


#### Tags:

 - Feature Flags, Server Side, SDKs, Backend, Evaluation

#### Properties

- [Documentation](https://docs.statsig.com/server/introduction)
- [OpenAPI](openapi/statsig-server-sdk-api-openapi.yml)

### Statsig Events API
The Statsig Events API handles the ingestion of event data from both client and server SDKs. It receives exposure events, custom events, and diagnostic data at the events.statsigapi.net endpoint. This data powers Statsig's experimentation analysis, product analytics, and metric computations. The Events API is optimized for high-throughput data ingestion, processing over a trillion events daily with high reliability and low latency, enabling real-time experiment monitoring and metric updates.

**Human URL:** [https://docs.statsig.com/http-api/](https://docs.statsig.com/http-api/)


#### Tags:

 - Events, Analytics, Data Ingestion, Metrics, Logging

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

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
