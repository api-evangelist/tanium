# Tanium

Tanium is a unified endpoint management and security platform that provides real-time visibility and control across all endpoints. It offers a suite of APIs including a GraphQL-based API Gateway and platform REST APIs for integrating with endpoint management, security, compliance, and threat response capabilities.

**Website:** https://www.tanium.com/  
**Developer Portal:** https://developer.tanium.com/  
**Documentation:** https://help.tanium.com/

## APIs

### Tanium API Gateway

A GraphQL interface for querying data and taking action in Tanium. The preferred integration method supporting asset queries, endpoint actions, and data retrieval.

**Documentation:** https://docs.tanium.com/api_gateway/api_gateway/overview.html

### Tanium Platform REST API

REST API for core platform functionality: endpoint information, action deployment, package management, sensors, saved questions, and audit logs.

**OpenAPI:** [openapi/tanium-platform-rest-api-openapi.yml](openapi/tanium-platform-rest-api-openapi.yml)

### Tanium Threat Response API

REST API for incident investigations, Recorder event viewing, evidence gathering, and file operations on endpoints.

**OpenAPI:** [openapi/tanium-threat-response-api-openapi.yml](openapi/tanium-threat-response-api-openapi.yml)

### Tanium Connect API

REST API for creating and managing data delivery connections that export endpoint data to downstream systems (SIEM, syslog, webhooks, databases).

**OpenAPI:** [openapi/tanium-connect-api-openapi.yml](openapi/tanium-connect-api-openapi.yml)

## Artifacts

### OpenAPI Specifications

| File | Description |
|------|-------------|
| [openapi/tanium-platform-rest-api-openapi.yml](openapi/tanium-platform-rest-api-openapi.yml) | Platform REST API — questions, actions, packages, sensors, groups |
| [openapi/tanium-threat-response-api-openapi.yml](openapi/tanium-threat-response-api-openapi.yml) | Threat Response API — alerts, investigations, events, processes |
| [openapi/tanium-connect-api-openapi.yml](openapi/tanium-connect-api-openapi.yml) | Connect API — data connections, destinations, schedules |

### JSON Schemas

| File | Description |
|------|-------------|
| [json-schema/tanium-endpoint-schema.json](json-schema/tanium-endpoint-schema.json) | Managed endpoint schema |
| [json-schema/tanium-question-schema.json](json-schema/tanium-question-schema.json) | Question schema |
| [json-schema/tanium-alert-schema.json](json-schema/tanium-alert-schema.json) | Threat alert schema |
| [json-schema/tanium-sensor-schema.json](json-schema/tanium-sensor-schema.json) | Sensor schema |
| [json-schema/tanium-package-schema.json](json-schema/tanium-package-schema.json) | Deployment package schema |
| [json-schema/tanium-action-schema.json](json-schema/tanium-action-schema.json) | Action schema |
| [json-schema/tanium-connection-schema.json](json-schema/tanium-connection-schema.json) | Connect connection schema |

### JSON Structures

| File | Description |
|------|-------------|
| [json-structure/tanium-endpoint-structure.json](json-structure/tanium-endpoint-structure.json) | Endpoint object structure documentation |
| [json-structure/tanium-action-structure.json](json-structure/tanium-action-structure.json) | Action object structure documentation |

### JSON-LD Context

| File | Description |
|------|-------------|
| [json-ld/tanium-context.jsonld](json-ld/tanium-context.jsonld) | JSON-LD context for Tanium domain concepts |

### Spectral Rules

| File | Description |
|------|-------------|
| [rules/tanium-rules.yml](rules/tanium-rules.yml) | Spectral ruleset enforcing Tanium API conventions |

### Naftiko Capabilities

| File | Description |
|------|-------------|
| [capabilities/endpoint-management.yaml](capabilities/endpoint-management.yaml) | Unified endpoint management workflow (14 tools) |
| [capabilities/shared/platform-rest-api.yaml](capabilities/shared/platform-rest-api.yaml) | Platform REST API consumed definition |
| [capabilities/shared/threat-response-api.yaml](capabilities/shared/threat-response-api.yaml) | Threat Response API consumed definition |
| [capabilities/shared/connect-api.yaml](capabilities/shared/connect-api.yaml) | Connect API consumed definition |

### Examples

| File | Description |
|------|-------------|
| [examples/tanium-ask-question-example.json](examples/tanium-ask-question-example.json) | Example: Ask a question to endpoints |
| [examples/tanium-deploy-action-example.json](examples/tanium-deploy-action-example.json) | Example: Deploy a package action |
| [examples/tanium-create-connection-example.json](examples/tanium-create-connection-example.json) | Example: Create a data delivery connection |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/tanium-vocabulary.yml](vocabulary/tanium-vocabulary.yml) | Tanium domain vocabulary and terminology |

## Tags

Compliance, Endpoint Management, Patch Management, Security, Threat Detection, Unified Endpoint Management

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
