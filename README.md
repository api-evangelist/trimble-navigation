# Trimble Navigation

Trimble Navigation Limited (now Trimble Inc.) is a global technology company founded in 1978 that pioneered commercial GPS technology. Trimble develops positioning, navigation, and geospatial solutions spanning construction, agriculture, transportation, and surveying industries. Its developer APIs cover GPS/GNSS positioning through Trimble Mobile Manager, high-accuracy survey integration via the Trimble Precision SDK, and geospatial data services. The positioning technology integrates GPS, laser, optical, and inertial technologies to deliver centimeter-level accuracy for professional applications.

**URL:** [View APIs.yml](https://raw.githubusercontent.com/api-evangelist/trimble-navigation/refs/heads/main/apis.yml)

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

### Trimble Mobile Manager API

Local REST API and WebSocket interface for integrating high-accuracy GNSS positioning from connected Trimble receivers into custom mobile applications.

**Human URL:** [https://developer.trimble.com/docs/mobile-manager/](https://developer.trimble.com/docs/mobile-manager/)

#### Tags

- GPS, GNSS, Positioning, Surveying, Mobile, WebSocket

#### Properties

- [Documentation](https://developer.trimble.com/docs/mobile-manager/)
- [Getting Started](https://developer.trimble.com/docs/mobile-manager/guides/integrate/)
- [OpenAPI](openapi/trimble-mobile-manager-openapi.yml)

### Trimble Positioning Services API

REST-based eCommerce API for purchasing and managing Trimble RTX correction service subscriptions.

**Human URL:** [https://www.trimble.com/en/developer/docs](https://www.trimble.com/en/developer/docs)

## OpenAPI Specifications

| Specification | Description |
|---|---|
| [Trimble Mobile Manager API](openapi/trimble-mobile-manager-openapi.yml) | Full TMM API covering system info, position streaming, receiver management, corrections, and Catalyst licenses |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [Trimble Mobile Manager Rules](rules/trimble-mobile-manager-rules.yml) | Spectral ruleset enforcing Trimble Navigation API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/trimble-mobile-manager.yaml](capabilities/shared/trimble-mobile-manager.yaml) | Per-API consumed definition for Trimble Mobile Manager |

### Workflow Capabilities

| Capability | Description |
|---|---|
| [capabilities/gnss-positioning.yaml](capabilities/gnss-positioning.yaml) | GNSS positioning workflow: system info, position streaming, receiver management, corrections, Catalyst licenses (8 tools) |

## JSON Schema

| Schema | Description |
|---|---|
| [json-schema/trimble-navigation-position-schema.json](json-schema/trimble-navigation-position-schema.json) | JSON Schema for GNSS position fix entities |

## JSON Structure

| Structure | Description |
|---|---|
| [json-structure/trimble-navigation-position-structure.json](json-structure/trimble-navigation-position-structure.json) | Structure documentation for GNSS position data |

## JSON-LD Context

| Context | Description |
|---|---|
| [json-ld/trimble-navigation-context.jsonld](json-ld/trimble-navigation-context.jsonld) | JSON-LD context mapping Trimble Navigation vocabulary to W3C GEO, SOSA, and schema.org |

## Examples

| Example | Description |
|---|---|
| [examples/trimble-mobile-manager-get-tmm-info-example.json](examples/trimble-mobile-manager-get-tmm-info-example.json) | Get TMM system info |
| [examples/trimble-mobile-manager-position-stream-example.json](examples/trimble-mobile-manager-position-stream-example.json) | Start GNSS position streaming with sample WebSocket message |

## Vocabulary

| File | Description |
|---|---|
| [vocabulary/trimble-navigation-vocabulary.yml](vocabulary/trimble-navigation-vocabulary.yml) | Domain vocabulary for GPS, GNSS, and positioning technology |

## Common Links

- **Website:** [https://www.trimble.com](https://www.trimble.com)
- **Developer Portal:** [https://www.trimble.com/en/developer/docs](https://www.trimble.com/en/developer/docs)
- **Mobile Manager Docs:** [https://developer.trimble.com/docs/mobile-manager/](https://developer.trimble.com/docs/mobile-manager/)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
