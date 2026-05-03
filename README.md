# Toys R Us

Toys 'R' Us is a leading toys and juvenile-products retailer offering a vast selection of toys, games, baby products, and children's apparel through retail stores and e-commerce sites. The brand integrates with suppliers and dropship vendors via the LogicBroker commerce platform.

**URL:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/toys-r-us/refs/heads/main/apis.yml)

## Tags

- Commerce
- Dropship
- E-Commerce
- Retail
- Supply Chain

## APIs

### Toys R Us Commerce API

The Toys R Us Commerce API, powered by LogicBroker, enables supplier and dropship vendor integrations for the complete order lifecycle including purchase orders (EDI 850), acknowledgements (EDI 855), shipments (EDI 856), invoices (EDI 810), and product catalog synchronization.

**Human URL:** [https://toysrus.logicbroker.com/hc/en-us/articles/9357008230164-API-Documentation](https://toysrus.logicbroker.com/hc/en-us/articles/9357008230164-API-Documentation)

**Base URL:** https://commerceapi.io

#### Tags

- Commerce
- Dropship
- E-Commerce
- Invoices
- Order Management
- Retail
- Shipments
- Supplier Integration

#### Properties

| Type | URL |
|------|-----|
| Documentation | [https://toysrus.logicbroker.com/hc/en-us/articles/9357008230164-API-Documentation](https://toysrus.logicbroker.com/hc/en-us/articles/9357008230164-API-Documentation) |
| OpenAPI | [openapi/toys-r-us-commerce-openapi.yml](openapi/toys-r-us-commerce-openapi.yml) |
| JSON Schema | [json-schema/toys-r-us-order-schema.json](json-schema/toys-r-us-order-schema.json) |
| JSON Structure | [json-structure/toys-r-us-order-structure.json](json-structure/toys-r-us-order-structure.json) |
| JSON-LD | [json-ld/toys-r-us-context.jsonld](json-ld/toys-r-us-context.jsonld) |
| Spectral Rules | [rules/toys-r-us-rules.yml](rules/toys-r-us-rules.yml) |
| Vocabulary | [vocabulary/toys-r-us-vocabulary.yml](vocabulary/toys-r-us-vocabulary.yml) |

## Capabilities

### Dropship Fulfillment

Unified dropship fulfillment workflow combining order retrieval, acknowledgement, shipment notification, invoice submission, and product catalog synchronization for end-to-end Toys R Us supplier operations.

| File | Description |
|------|-------------|
| [capabilities/dropship-fulfillment.yaml](capabilities/dropship-fulfillment.yaml) | Workflow capability: 9 MCP tools covering full order lifecycle |
| [capabilities/shared/toys-r-us-commerce.yaml](capabilities/shared/toys-r-us-commerce.yaml) | Shared per-API consumed definition |

## Examples

| File | Description |
|------|-------------|
| [examples/toys-r-us-get-orders-example.json](examples/toys-r-us-get-orders-example.json) | Get Orders request/response example |
| [examples/toys-r-us-create-shipment-example.json](examples/toys-r-us-create-shipment-example.json) | Create Shipment request/response example |

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://www.toysrus.com](https://www.toysrus.com) |
| Supplier Portal | [https://toysrus.logicbroker.com](https://toysrus.logicbroker.com) |
| Documentation | [https://toysrus.logicbroker.com/hc/en-us/articles/9357008230164-API-Documentation](https://toysrus.logicbroker.com/hc/en-us/articles/9357008230164-API-Documentation) |
| Developer Portal | [https://dev.logicbroker.com](https://dev.logicbroker.com) |

---
*Maintained by Kin Lane (kin@apievangelist.com)*
