# Tanium (tanium)

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
