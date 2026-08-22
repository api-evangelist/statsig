# statsig (statsig)

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
