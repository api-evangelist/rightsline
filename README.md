# Rightsline

Rightsline is the leading rights and royalties software platform for media, entertainment, and content businesses. Its REST API enables real-time integration of contacts, product catalogs, revenue data, and workflow automation for rights tracking, availability, royalty calculations, and vendor delivery across the content lifecycle.

## APIs

### Rightsline Rights API
RESTful API for managing rights, licenses, and availability data. Supports creation, retrieval, modification, and deletion of up to 100 records per request. Enables automation of rights tracking, availability validation, vendor delivery requests, and workflow actions.

- **Base URL:** `https://app.rightsline.com/v4`
- **EU Base URL:** `https://app.rightsline.eu/v4`
- **Documentation:** https://api-docs.rightsline.com/
- **Authentication:** Three-part key exchange (Company API Key + Access Key + Secret Access Key)

### Rightsline Royalties API
RESTful API for managing royalties, revenue data, and financial workflows. Supports bulk loading of revenue, sales, and usage data.

- **Base URL:** `https://app.rightsline.com/v4`
- **Documentation:** https://api-docs.rightsline.com/

## OpenAPI Specifications

| API | Specification |
|-----|---------------|
| Rightsline API | [rightsline-openapi.yml](openapi/rightsline-openapi.yml) |

## Capabilities

Naftiko capability definitions for AI-assisted rights management workflows:

| Capability | Description |
|------------|-------------|
| [Rights and Royalties Management](capabilities/rights-royalties-management.yaml) | Rights CRUD, availability checking, workflow automation, audit trail |

### Shared Definitions

| Definition | API |
|------------|-----|
| [rights.yaml](capabilities/shared/rights.yaml) | Rightsline Rights and Workflows API |

## Rules

Spectral ruleset for validating Rightsline API conventions:

- [rightsline-rules.yml](rules/rightsline-rules.yml)

## JSON Schemas

| Schema | Description |
|--------|-------------|
| [rightsline-right-schema.json](json-schema/rightsline-right-schema.json) | Rights/license record |
| [rightsline-royalty-schema.json](json-schema/rightsline-royalty-schema.json) | Royalty/revenue record |

## JSON Structures

| Structure | Description |
|-----------|-------------|
| [rightsline-right-structure.json](json-structure/rightsline-right-structure.json) | Field-level documentation for rights records |

## JSON-LD

| Context | Description |
|---------|-------------|
| [rightsline-context.jsonld](json-ld/rightsline-context.jsonld) | Linked data context for rights, royalties, and availability entities |

## Examples

| Example | Description |
|---------|-------------|
| [rightsline-list-rights-example.json](examples/rightsline-list-rights-example.json) | List rights records |
| [rightsline-check-availability-example.json](examples/rightsline-check-availability-example.json) | Check content availability |

## Vocabulary

- [rightsline-vocabulary.yml](vocabulary/rightsline-vocabulary.yml) — Domain vocabulary for rights management, availability, royalties, and distribution

## Links

- **Website:** https://www.rightsline.com
- **API Documentation:** https://api-docs.rightsline.com/
- **Postman Workspace:** https://postman.rightsline.com/
- **Portal (US):** https://app.rightsline.com
- **Portal (EU):** https://app.rightsline.eu
- **Getting Started:** https://api-docs.rightsline.com/getting-started
