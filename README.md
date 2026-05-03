# Tesla Motors

Tesla, Inc. (formerly Tesla Motors, Inc.) is an American electric vehicle and clean energy company that designs and manufactures electric cars, battery energy storage systems, solar panels, and related products. The Tesla Owner API provides programmatic access to Tesla vehicles for monitoring state, controlling climate, managing charging, and executing remote commands.

**Type:** Company  
**Website:** https://www.tesla.com  
**Developer Portal:** https://developer.tesla.com  
**GitHub:** https://github.com/teslamotors  

## APIs

### Tesla Motors Owner API
The Tesla Owner API (documented by the community) provides access to Tesla vehicle telemetry and remote command capabilities. Supports vehicle listing, state retrieval (charge, climate, drive, vehicle state), and 30+ commands.

- **Base URL:** `https://owner-api.teslamotors.com`
- **Authentication:** Bearer token (OAuth)
- **Documentation:** https://tesla-api.timdorr.com/
- **OpenAPI Spec:** [openapi/tesla-motors-owner-openapi.yml](openapi/tesla-motors-owner-openapi.yml)

## Artifacts

| Type | Files |
|------|-------|
| OpenAPI Specs | [openapi/](openapi/) |
| Spectral Rules | [rules/tesla-motors-rules.yml](rules/tesla-motors-rules.yml) |
| Capabilities | [capabilities/](capabilities/) |
| JSON Schema | [json-schema/](json-schema/) |
| JSON Structure | [json-structure/](json-structure/) |
| JSON-LD | [json-ld/tesla-motors-context.jsonld](json-ld/tesla-motors-context.jsonld) |
| Examples | [examples/](examples/) |
| Vocabulary | [vocabulary/tesla-motors-vocabulary.yml](vocabulary/tesla-motors-vocabulary.yml) |

## Capabilities

### Workflow Capabilities
- **[vehicle-management.yaml](capabilities/vehicle-management.yaml)** — Tesla vehicle telemetry monitoring and remote command management (17 tools)

### Shared Per-API Definitions
- **[shared/tesla-motors.yaml](capabilities/shared/tesla-motors.yaml)** — Tesla Motors Owner API: vehicle listing, telemetry, and remote commands (16 tools)

## Tags

Automobiles, Electric Vehicles, Cars, Smart Vehicles, IoT, Tesla, Remote Commands, Telemetry, Charging

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
