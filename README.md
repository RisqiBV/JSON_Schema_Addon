# JSON Schema Addon

This repository contains a collection of structured JSON Schema files intended for API integration purposes. Each schema represents a standardized format for data exchange between systems, designed to improve consistency, validation, and interoperability during development and integration processes.

## 📦 Purpose

These JSON Schemas are primarily used to:

- Define the expected structure of JSON data in API communication
- Validate incoming and outgoing API payloads
- Serve as a reference for developers during integration
- Support system automation and documentation generation

## 📁 Schema List

The repository includes the following schema files:

- `buyer.json` – Buyer information schema
- `dispatch.json` – Dispatch and delivery-related data
- `masterItem.json` – Master item catalog or product reference
- `order.json` – Main order structure
- `orderBom.json` – Bill of materials for orders
- `orderSize.json` – Order details per size breakdown
- `purchaseOrder.json` – Purchase order schema
- `received.json` – Goods or items received schema
- `sizeMaster.json` – Master data for sizes
- `supplier.json` – Supplier or vendor reference
- `unitMaster.json` – Master unit of measurement

## 📌 Usage

You can use these schemas to validate your JSON payloads using your preferred validation tool or framework. Here's an example using a Node.js validator:

```bash
npm install ajv
