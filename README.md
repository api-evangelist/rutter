# Rutter

Rutter is the leading unified RESTful API for B2B financial products that connects to over 60 commerce, payments, accounting, and ads platforms through a single API. Trusted by companies like Airwallex, Mercury, and Ramp, Rutter enables developers to read, update, write, and remove data across major business platforms with a unified data model and idempotency guarantees for financial data. The API uses Basic authentication with client_id/client_secret plus per-connection access tokens.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/apis.yml)

## Tags

- Accounting
- B2B
- Commerce
- Financial Data
- Payments
- Unified API

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-02

## APIs

### Rutter Unified API

The primary REST API providing a single interface to 60+ commerce, payments, and accounting platforms. Supports connections, accounting data (accounts, transactions, invoices, bills, expenses), commerce data (orders, products, customers), banking, ads, and webhooks. Uses cursor-based pagination and versioning via X-Rutter-Version header.

**Human URL:** [docs.rutter.com](https://docs.rutter.com/)

**Base URL:** `https://production.rutterapi.com/versioned`

#### Properties

- [Documentation](https://docs.rutter.com/)
- [OpenAPI](openapi/rutter-unified-api-openapi.yml)
- [Sign Up](https://dashboard.rutterapi.com/sign-up)

### Rutter Commerce API

Unified interface for reading and writing data to all major commerce platforms (Shopify, WooCommerce, Amazon, and more).

**Human URL:** [rutter.com/product/commerce-api](https://www.rutter.com/product/commerce-api)

### Rutter Accounting API

Unified interface for reading and writing data to all major accounting platforms (QuickBooks, Xero, Freshbooks, Zoho Books).

**Human URL:** [rutter.com/product/accounting-api](https://www.rutter.com/product/accounting-api)

### Rutter Payments API

Unified interface for reading and writing data to all major payment platforms.

**Human URL:** [rutter.com/product/payments-api](https://www.rutter.com/product/payments-api)

## Artifacts

### OpenAPI

- [Rutter Unified API](openapi/rutter-unified-api-openapi.yml)

### Spectral Rules

- [Rutter API Rules](rules/rutter-spectral-rules.yml)

### Capabilities

- [Financial Data Sync](capabilities/financial-data-sync.yaml)
- [Commerce Operations](capabilities/commerce-operations.yaml)

#### Shared Definitions

- [Unified API](capabilities/shared/unified-api.yaml)

### JSON Schema

- [Connection](json-schema/rutter-connection-schema.json)
- [Invoice](json-schema/rutter-invoice-schema.json)
- [Order](json-schema/rutter-order-schema.json)

### JSON Structure

- [Connection](json-structure/rutter-connection-structure.json)
- [Order](json-structure/rutter-order-structure.json)

### Examples

- [List Connections](examples/rutter-list-connections-example.json)
- [List Invoices](examples/rutter-list-invoices-example.json)
- [List Orders](examples/rutter-list-orders-example.json)

### JSON-LD Context

- [Rutter Context](json-ld/rutter-context.jsonld)

### Vocabulary

- [Rutter Vocabulary](vocabulary/rutter-vocabulary.yml)

## Common Properties

- [Website](https://www.rutter.com/)
- [Documentation](https://docs.rutter.com/)
- [Pricing](https://www.rutter.com/pricing)
- [Blog](https://www.rutter.com/blog)
- [Integrations](https://www.rutter.com/integrations)
- [GitHub](https://github.com/rutter)
- [SDK](https://github.com/rutter/react-rutter-link)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
