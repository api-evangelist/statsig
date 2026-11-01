# Statsig

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

Statsig is a product development platform that combines feature management, experimentation and analytics in one system. Teams gate releases behind feature flags, run A/B, A/B/n, switchback, holdout and multi-armed-bandit experiments, and read the impact of every change against their own metrics — in Statsig Cloud, which ingests and stores the event data, or Warehouse Native, which runs the same analysis directly against the customer's Snowflake, BigQuery, Databricks or Athena warehouse without moving user-level data out of it. Around that core it ships product analytics, web analytics, session replay, infra analytics, dynamic configs, parameter stores and 30+ SDKs. Its programmable surface is unusually complete: a first-party OpenAPI covering 324 Console API operations, a low-latency HTTP evaluation API, gRPC protobufs for the self-hosted Forward Proxy, an authenticated remote MCP server with OAuth, a public documentation MCP server, published Agent Skills, a Terraform provider and a CLI. Statsig is based in Bellevue, Washington.

**Areas:** Feature Flags · Experimentation · A/B Testing · Product Analytics · Session Replay · Developer Tools · Data Warehouse · Configuration Management

## Statsig on APIs.io

Everything profiled for Statsig is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/statsig/](https://apis.io/providers/statsig/)** — or go straight to one of the APIs or properties below.

### APIs (38)

- [Statsig Events API](https://apis.io/apis/statsig/events-api/) — The Statsig Events API handles the ingestion of event data from both client and server SDKs. It receives exposure events, custom events, and diagnostic data…
- [statsig Audit Logs API](https://apis.io/apis/statsig/statsig-audit-logs-api/) — Access audit log entries tracking changes made to project configuration through the console or API.
- [statsig Autotunes API](https://apis.io/apis/statsig/statsig-autotunes-api/) — Manage autotune configurations that automatically optimize parameter values based on a target metric.
- [statsig Configuration API](https://apis.io/apis/statsig/statsig-configuration-api/) — Endpoints for downloading full project configuration specs for server-side local evaluation.
- [statsig Dynamic Configs API](https://apis.io/apis/statsig/statsig-dynamic-configs-api/) — Manage dynamic configurations with full CRUD operations for server-driven configuration values.
- [statsig Experiments API](https://apis.io/apis/statsig/statsig-experiments-api/) — Manage A/B test experiments including creation, configuration, starting, resetting, and analysis.
- [statsig Feature Gates API](https://apis.io/apis/statsig/statsig-feature-gates-api/) — Endpoints for evaluating feature gates for users, returning boolean pass/fail values along with rule identification.
- [statsig Gates API](https://apis.io/apis/statsig/statsig-gates-api/) — Manage feature gates including creation, updates, rules, overrides, enabling, disabling, launching, and archiving.
- [statsig Holdouts API](https://apis.io/apis/statsig/statsig-holdouts-api/) — Manage holdout groups that exclude users from receiving specific features for measuring long-term impact.
- [statsig Initialization API](https://apis.io/apis/statsig/statsig-initialization-api/) — Endpoints for initializing client SDKs with all evaluated feature gates, configs, experiments, and layers for a given user.
- [statsig Keys API](https://apis.io/apis/statsig/statsig-keys-api/) — Manage API keys for the project including server secret keys, client SDK keys, and console API keys.
- [statsig Layers API](https://apis.io/apis/statsig/statsig-layers-api/) — Manage layers that enable sharing parameters across multiple experiments while maintaining mutual exclusivity.
- [statsig Metrics API](https://apis.io/apis/statsig/statsig-metrics-api/) — Access and manage metric definitions and metric sources used in experiment analysis.
- [statsig Segments API](https://apis.io/apis/statsig/statsig-segments-api/) — Manage user segments for targeting rules across gates, configs, and experiments.
- [statsig Tags API](https://apis.io/apis/statsig/statsig-tags-api/) — The Tags API from statsig — 1 operation(s) for tags.
- [statsig Target Apps API](https://apis.io/apis/statsig/statsig-target-apps-api/) — Manage target application definitions that scope feature configurations to specific applications.
- [statsig Users API](https://apis.io/apis/statsig/statsig-users-api/) — Manage user data and lookup user properties within the Statsig project.
- [Statsig Alerts API](https://apis.io/apis/statsig/statsig-alerts-api/) — The Alerts API from Statsig — 6 operation(s) for alerts.
- [Statsig Change Validation API](https://apis.io/apis/statsig/statsig-change-validation-api/) — The Change Validation API from Statsig — 2 operation(s) for change validation.
- [Statsig Company API](https://apis.io/apis/statsig/statsig-company-api/) — The Company API from Statsig — 1 operation(s) for company.
- [Statsig Configs API](https://apis.io/apis/statsig/statsig-configs-api/) — The Configs API from Statsig — 1 operation(s) for configs.
- [Statsig Dashboards API](https://apis.io/apis/statsig/statsig-dashboards-api/) — The Dashboards API from Statsig — 4 operation(s) for dashboards.
- [Statsig Environments API](https://apis.io/apis/statsig/statsig-environments-api/) — The Environments API from Statsig — 1 operation(s) for environments.
- [Statsig Experiments (Warehouse Native) API](https://apis.io/apis/statsig/statsig-experiments-warehouse-native-api/) — The Experiments (Warehouse Native) API from Statsig — 10 operation(s) for experiments (warehouse native).
- [Statsig Ingestions API](https://apis.io/apis/statsig/statsig-ingestions-api/) — The Ingestions API from Statsig — 9 operation(s) for ingestions.
- [Statsig Logs API](https://apis.io/apis/statsig/statsig-logs-api/) — The Logs API from Statsig — 1 operation(s) for logs.
- [Statsig Overrides API](https://apis.io/apis/statsig/statsig-overrides-api/) — The Overrides API from Statsig — 1 operation(s) for overrides.
- [Statsig Param Store API](https://apis.io/apis/statsig/statsig-param-store-api/) — The Param Store API from Statsig — 2 operation(s) for param store.
- [Statsig Project API](https://apis.io/apis/statsig/statsig-project-api/) — The Project API from Statsig — 1 operation(s) for project.
- [Statsig Prompts API](https://apis.io/apis/statsig/statsig-prompts-api/) — The Prompts API from Statsig — 4 operation(s) for prompts.
- [Statsig Release Pipelines API](https://apis.io/apis/statsig/statsig-release-pipelines-api/) — The Release Pipelines API from Statsig — 10 operation(s) for release pipelines.
- [Statsig Reports API](https://apis.io/apis/statsig/statsig-reports-api/) — The Reports API from Statsig — 1 operation(s) for reports.
- [Statsig Roles API](https://apis.io/apis/statsig/statsig-roles-api/) — The Roles API from Statsig — 2 operation(s) for roles.
- [Statsig Settings API](https://apis.io/apis/statsig/statsig-settings-api/) — The Settings API from Statsig — 4 operation(s) for settings.
- [Statsig Target App API](https://apis.io/apis/statsig/statsig-target-app-api/) — The Target App API from Statsig — 2 operation(s) for target app.
- [Statsig Unit ID Types API](https://apis.io/apis/statsig/statsig-unit-id-types-api/) — The Unit ID Types API from Statsig — 2 operation(s) for unit id types.
- [Statsig Usage API](https://apis.io/apis/statsig/statsig-usage-api/) — The Usage API from Statsig — 1 operation(s) for usage.
- [Statsig Warehouse Connections API](https://apis.io/apis/statsig/statsig-warehouse-connections-api/) — The Warehouse Connections API from Statsig — 1 operation(s) for warehouse connections.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Statsig Webhook Events](https://apis.io/asyncapis/statsig/statsig-webhooks-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/webhook](https://apis.io/channels/statsig/webhook/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Statsig MCP](https://apis.io/servers/statsig/statsig-mcp/)

#### Agent skills (3)

Agent skills built on the API.

- [statsig](https://apis.io/agent-skills/statsig/statsig/)
- [statsig-create-cloud-metric](https://apis.io/agent-skills/statsig/statsig-create-cloud-metric/)
- [statsig-dashboard](https://apis.io/agent-skills/statsig/statsig-dashboard/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Statsig Agentic Access](https://apis.io/agentic-access/statsig/statsig-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Statsig Event](https://apis.io/schemas/statsig/statsig-event/)
- [Statsig Experiment](https://apis.io/schemas/statsig/statsig-experiment/)
- [Statsig Feature Gate](https://apis.io/schemas/statsig/statsig-feature-gate/)

#### JSON Structure (3)

Data models expressed in JSON Structure.

- [Statsig Event Structure](https://apis.io/json-structure/statsig/statsig-event-structure/)
- [Statsig Experiment Structure](https://apis.io/json-structure/statsig/statsig-experiment-structure/)
- [Statsig Feature Gate Structure](https://apis.io/json-structure/statsig/statsig-feature-gate-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Statsig Context](https://apis.io/jsonld/statsig/statsig-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Statsig Vocabulary](https://apis.io/vocabularies/statsig/statsig-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Statsig Check Gate Example](https://apis.io/examples/statsig/statsig-check-gate-example/)
- [Statsig Create Experiment Example](https://apis.io/examples/statsig/statsig-create-experiment-example/)
- [Statsig Create Gate Example](https://apis.io/examples/statsig/statsig-create-gate-example/)
- [Statsig List Gates Example](https://apis.io/examples/statsig/statsig-list-gates-example/)
- [Statsig Log Events Example](https://apis.io/examples/statsig/statsig-log-events-example/)

#### Collections (22)

Postman and Open Collection request collections.

- [Statsig Client SDK Audit Logs API](https://apis.io/collections/statsig/open-statsig-audit-logs-api/)
- [Statsig Client SDK Audit Logs Autotunes API](https://apis.io/collections/statsig/open-statsig-autotunes-api/)
- [Statsig Client SDK API](https://apis.io/collections/statsig/open-statsig-client-sdk-api/)
- [Statsig Client SDK Audit Logs Configuration API](https://apis.io/collections/statsig/open-statsig-configuration-api/)
- [Statsig Console API](https://apis.io/collections/statsig/open-statsig-console-api/)
- [Statsig Client SDK Audit Logs Dynamic Configs API](https://apis.io/collections/statsig/open-statsig-dynamic-configs-api/)
- [Statsig Client SDK Audit Logs Events API](https://apis.io/collections/statsig/open-statsig-events-api/)
- [Statsig Client SDK Audit Logs Experiments API](https://apis.io/collections/statsig/open-statsig-experiments-api/)
- [Statsig Client SDK Audit Logs Feature Gates API](https://apis.io/collections/statsig/open-statsig-feature-gates-api/)
- [Statsig Client SDK Audit Logs Gates API](https://apis.io/collections/statsig/open-statsig-gates-api/)
- [Statsig Client SDK Audit Logs Holdouts API](https://apis.io/collections/statsig/open-statsig-holdouts-api/)
- [Statsig HTTP API](https://apis.io/collections/statsig/open-statsig-http-api/)
- [Statsig Client SDK Audit Logs Initialization API](https://apis.io/collections/statsig/open-statsig-initialization-api/)
- [Statsig Client SDK Audit Logs Keys API](https://apis.io/collections/statsig/open-statsig-keys-api/)
- [Statsig Client SDK Audit Logs Layers API](https://apis.io/collections/statsig/open-statsig-layers-api/)
- [Statsig Client SDK Audit Logs Metrics API](https://apis.io/collections/statsig/open-statsig-metrics-api/)
- [Statsig Client SDK Audit Logs Segments API](https://apis.io/collections/statsig/open-statsig-segments-api/)
- [Statsig Server SDK API](https://apis.io/collections/statsig/open-statsig-server-sdk-api/)
- [Statsig Client SDK Audit Logs Tags API](https://apis.io/collections/statsig/open-statsig-tags-api/)
- [Statsig Client SDK Audit Logs Target Apps API](https://apis.io/collections/statsig/open-statsig-target-apps-api/)
- [Statsig Client SDK Audit Logs Users API](https://apis.io/collections/statsig/open-statsig-users-api/)
- [Statsig Client SDK Audit Logs Webhooks API](https://apis.io/collections/statsig/open-statsig-webhooks-api/)

#### Overlays (40)

OpenAPI overlays, including conversational phrasing for each operation.

- [Statsig Alerts Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-alerts-api-phrasing-overlay/)
- [Statsig Audit Logs Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-audit-logs-api-phrasing-overlay/)
- [Statsig Autotunes Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-autotunes-api-phrasing-overlay/)
- [Statsig Change Validation Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-change-validation-api-phrasing-overlay/)
- [Statsig Company Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-company-api-phrasing-overlay/)
- [Statsig Configs Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-configs-api-phrasing-overlay/)
- [Statsig Configuration Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-configuration-api-phrasing-overlay/)
- [Statsig Console Api Overlay](https://apis.io/overlays/statsig/statsig-console-api-overlay/)
- [Statsig Dashboards Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-dashboards-api-phrasing-overlay/)
- [Statsig Dynamic Configs Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-dynamic-configs-api-phrasing-overlay/)
- [Statsig Environments Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-environments-api-phrasing-overlay/)
- [Statsig Events Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-events-api-phrasing-overlay/)
- [Statsig Experiments Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-experiments-api-phrasing-overlay/)
- [Statsig Experiments Warehouse Native Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-experiments-warehouse-native-api-phrasing-overlay/)
- [Statsig Feature Gates Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-feature-gates-api-phrasing-overlay/)
- [Statsig Gates Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-gates-api-phrasing-overlay/)
- [Statsig Holdouts Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-holdouts-api-phrasing-overlay/)
- [Statsig Ingestions Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-ingestions-api-phrasing-overlay/)
- [Statsig Initialization Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-initialization-api-phrasing-overlay/)
- [Statsig Keys Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-keys-api-phrasing-overlay/)
- [Statsig Layers Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-layers-api-phrasing-overlay/)
- [Statsig Logs Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-logs-api-phrasing-overlay/)
- [Statsig Metrics Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-metrics-api-phrasing-overlay/)
- [Statsig Metrics Warehouse Native Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-metrics-warehouse-native-api-phrasing-overlay/)
- [Statsig Overrides Api Phrasing Overlay](https://apis.io/overlays/statsig/statsig-overrides-api-phrasing-overlay/)
- …and 15 more published on APIs.io

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Statsig — asyncapi rules](https://apis.io/rules/statsig/statsig-asyncapi-spectral-rules/)
- [Statsig — jsonschema rules](https://apis.io/rules/statsig/statsig-jsonschema-spectral-rules/)
- [Statsig API Rules](https://apis.io/rules/statsig/statsig-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Statsig Authentication](https://apis.io/security/statsig/statsig-authentication/)
- [Statsig Domain Security](https://apis.io/security/statsig/statsig-domain-security/)
- [Statsig Trust Center](https://apis.io/security/statsig/statsig-trust-center/)
- [Statsig Vulnerability Disclosure](https://apis.io/security/statsig/statsig-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Statsig Plans Pricing](https://apis.io/plans/statsig/statsig-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Statsig Rate Limits](https://apis.io/rate-limits/statsig/statsig-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Statsig Finops](https://apis.io/finops/statsig/statsig-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.statsig.com/)
- [Documentation](https://docs.statsig.com/)
- [Getting started](https://docs.statsig.com/sdks/quickstart)
- [API reference](https://docs.statsig.com/console-api/introduction)
- [Pricing](https://www.statsig.com/pricing)
- [Sign up](https://console.statsig.com/login)
- [Support](https://www.statsig.com/contact)
- [Blog](https://www.statsig.com/blog)
- [Security](https://www.statsig.com/legal/security)
- [Terms of service](https://www.statsig.com/terms)
- [GitHub](https://github.com/statsig-io)
- [Status](https://status.statsig.com/)

## API Evangelist rating

**Kin Score 75.2** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 67.6 |
| Contract governance | 45.5 |
| Operational transparency | 84.2 |
| Developer ergonomics | 78.6 |
| Access clarity | 68.4 |

**Agent readiness 55.6** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | verified |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | — |

**Regulatory alignment 31.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/statsig/](https://apis.io/providers/statsig/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Statsig: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/statsig/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
