# Confluent Schema Registry (confluent-schema-registry)

Confluent Schema Registry is the open-source serving layer for schema metadata used in Apache Kafka data pipelines. It exposes a RESTful interface for storing and retrieving Avro, JSON Schema, and Protobuf schemas, manages schema evolution through configurable compatibility rules (BACKWARD, FORWARD, FULL, and transitive variants), supports schema references and contexts, and integrates with Kafka producers and consumers via shipped serializers and deserializers. Schema Registry is distributed under the Confluent Community License and is a core component of both Confluent Platform and Confluent Cloud.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/confluent-schema-registry/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/confluent-schema-registry/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Open Source

## Tags

- Apache Kafka
- Avro
- Compatibility
- Confluent
- Data Governance
- Data Streaming
- JSON Schema
- Open Source
- Protobuf
- REST
- Schema Evolution
- Schema Registry

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### Confluent Schema Registry REST API

The Confluent Schema Registry REST API provides programmatic management of schemas, subjects, schema versions, schema references, compatibility modes, and operating mode. Producers and consumers use it to register and look up Avro, JSON Schema, and Protobuf schemas, while platform teams use it to enforce schema evolution policies through subject- and cluster-level compatibility settings. The API uses the application/vnd.schemaregistry.v1+json content type and supports authentication via HTTP Basic, mTLS, or OAuth depending on deployment.

- **Human URL:** [https://docs.confluent.io/platform/current/schema-registry/develop/api.html](https://docs.confluent.io/platform/current/schema-registry/develop/api.html)
- **Base URL:** `http://localhost:8081`

#### Tags

- Compatibility
- REST
- Schemas
- Subjects

#### Properties

- [Documentation](https://docs.confluent.io/platform/current/schema-registry/develop/api.html)
- [OpenAPI](openapi/schema-registry.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/schema-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/schema-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/schema-registry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/confluent-schema-registry-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/confluent-schema-registry-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Git Hub](https://github.com/confluentinc/schema-registry)

## Common Properties

- [Website](https://www.confluent.io/)
- [Documentation](https://docs.confluent.io/platform/current/schema-registry/)
- [Getting Started](https://docs.confluent.io/platform/current/schema-registry/develop/using.html)
- [API Reference](https://docs.confluent.io/platform/current/schema-registry/develop/api.html)
- [Git Hub](https://github.com/confluentinc/schema-registry)
- [License](https://www.confluent.io/confluent-community-license/)
- [Blog](https://www.confluent.io/blog/)
- [Pricing](https://www.confluent.io/pricing/)
- [JSON-LD](json-ld/confluent-schema-registry-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/confluent-schema-registry-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Integrations](https://www.confluent.io/partner/)
- [L L Ms Txt](https://docs.confluent.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
