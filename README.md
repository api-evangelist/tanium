# Tanium (tanium)

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

Tanium is a unified endpoint management and security platform that provides real-time visibility and control across all endpoints. It offers a suite of APIs including a GraphQL-based API Gateway and platform REST APIs for integrating with endpoint management, security, compliance, and threat response capabilities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Compliance
- Endpoint Management
- Patch Management
- Security
- Threat Detection
- Unified Endpoint Management

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-19

## APIs

### Tanium API Gateway

The Tanium API Gateway is a GraphQL interface for querying data and taking action in Tanium. It is the preferred method for integrating with Tanium, supporting asset queries, endpoint actions, and data retrieval across the platform.

- **Human URL:** [https://docs.tanium.com/api_gateway/api_gateway/overview.html](https://docs.tanium.com/api_gateway/api_gateway/overview.html)

#### Tags

- API Gateway
- Endpoints
- GraphQL
- Integration
- Queries

#### Properties

- [Documentation](https://docs.tanium.com/api_gateway/api_gateway/overview.html)
- [Reference](https://docs.tanium.com/api_gateway/api_gateway/api_gateway_examples.html)
- [Getting Started](https://docs.tanium.com/api_gateway/api_gateway/api_gateway.html)
- [Graph Q L Schema](https://developer.tanium.com/site/global/apis/graphql/schema/)
- [Postman Collection](collections/tanium-connect-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tanium-connect-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tanium-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tanium-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tanium-threat-response-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tanium-threat-response-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tanium Platform REST API

The Tanium Platform REST API provides access to core platform functionality including gathering endpoint information, deploying actions, evaluating deployment health, managing certificates, updating packages, and downloading audit logs.

- **Human URL:** [https://developer.tanium.com/apis/api_intro](https://developer.tanium.com/apis/api_intro)

#### Tags

- Actions
- Endpoints
- Platform
- REST API
- Security

#### Properties

- [Documentation](https://developer.tanium.com/apis/api_intro)
- [Integration Guide](https://developer.tanium.com/guides/core-platform/integration_methods)
- [Authentication](https://docs.tanium.com/platform_user/platform_user/console_api_tokens.html)
- [OpenAPI](openapi/tanium-platform-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tanium-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tanium-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tanium Threat Response API

The Tanium Threat Response REST API enables starting investigations, viewing Recorder events, gathering evidence, and performing file and directory operations on endpoints for threat detection and incident response.

- **Human URL:** [https://developer.tanium.com/site/global/docs/how_tos/tr_actions/index.gsp](https://developer.tanium.com/site/global/docs/how_tos/tr_actions/index.gsp)

#### Tags

- Incident Response
- Investigations
- Security
- Threat Detection
- Threat Response

#### Properties

- [Documentation](https://developer.tanium.com/site/global/docs/how_tos/tr_actions/index.gsp)
- [Getting Started](https://help.tanium.com/bundle/ug_threat_response_cloud/page/threat_response/gettingstarted.html)
- [OpenAPI](openapi/tanium-threat-response-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tanium-threat-response-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tanium-threat-response-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tanium Connect API

The Tanium Connect REST API allows creating, editing, and managing connections for delivering endpoint data to downstream systems via files, syslog, webhooks, and other destination types on a schedule or triggered by events.

- **Human URL:** [https://docs.tanium.com/connect/connect/index.html](https://docs.tanium.com/connect/connect/index.html)

#### Tags

- Connections
- Data Delivery
- Integration
- Syslog
- Webhooks

#### Properties

- [Documentation](https://docs.tanium.com/connect/connect/index.html)
- [OpenAPI](openapi/tanium-connect-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tanium-connect-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tanium-connect-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/tanium)
- [JSON Schema](json-schema/tanium-endpoint-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tanium-question-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tanium-alert-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tanium-sensor-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tanium-package-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tanium-action-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tanium-connection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/tanium-endpoint-structure.json)
- [JSON Structure](json-structure/tanium-action-structure.json)
- [JSON-LD](json-ld/tanium-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/tanium-rules.yml)
- [Vocabulary](vocabulary/tanium-vocabulary.yml)
- [Portal](https://developer.tanium.com/)
- [Documentation](https://help.tanium.com/)
- [Getting Started](https://developer.tanium.com/apis/api_intro)
- [Authentication](https://docs.tanium.com/platform_user/platform_user/console_api_tokens.html)
- [Blog](https://www.tanium.com/p/tanium-blog/)
- [Support](https://community.tanium.com/s/)
- [Terms of Service](https://www.tanium.com/terms-of-use/)
- [Privacy Policy](https://www.tanium.com/privacy/)
- [GitHub Organization](https://github.com/tanium)
- [Community](https://community.tanium.com/s/)
- [Website](https://www.tanium.com/)
- [Login](https://community.tanium.com/s/login/)
- [Sign Up](https://community.tanium.com/CommunitiesSelfReg)
- [S D Ks](https://tanium.github.io/pytan/)
- [Integration Guide](https://developer.tanium.com/guides/core-platform/integration_methods)
- [Use Cases](https://developer.tanium.com/use_cases)
- [Changelog](https://help.tanium.com/bundle/releasenotes/page/releasenotes/index.html)
- [Contact](https://www.tanium.com/contact/)
- [Integrations](https://www.tanium.com/partners)
- [L L Ms Txt](https://developer.tanium.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
