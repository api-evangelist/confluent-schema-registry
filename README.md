# Confluent Schema Registry (confluent-schema-registry)

Confluent Schema Registry is the open-source serving layer for schema metadata used in Apache Kafka data pipelines. It exposes a RESTful interface for storing and retrieving Avro, JSON Schema, and Protobuf schemas, manages schema evolution through configurable compatibility rules (BACKWARD, FORWARD, FULL, and transitive variants), supports schema references and contexts, and integrates with Kafka producers and consumers via shipped serializers and deserializers. Schema Registry is distributed under the Confluent Community License and is a core component of both Confluent Platform and Confluent Cloud.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/confluent-schema-registry/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Open Source
- **Classification:** Open Source

## Tags

- Apache Kafka, Avro, Compatibility, Confluent, Data Governance, Data Streaming, JSON Schema, Open Source, Protobuf, REST, Schema Evolution, Schema Registry

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-28

## APIs

### Confluent Schema Registry REST API

The Confluent Schema Registry REST API provides programmatic management of schemas, subjects, schema versions, schema references, compatibility modes, and operating mode. Producers and consumers use it to register and look up Avro, JSON Schema, and Protobuf schemas, while platform teams use it to enforce schema evolution policies through subject- and cluster-level compatibility settings. The API uses the application/vnd.schemaregistry.v1+json content type and supports authentication via HTTP Basic, mTLS, or OAuth depending on deployment.

**Human URL:** [https://docs.confluent.io/platform/current/schema-registry/develop/api.html](https://docs.confluent.io/platform/current/schema-registry/develop/api.html)

#### Tags

- Compatibility, REST, Schemas, Subjects

#### Properties

- [Documentation](https://docs.confluent.io/platform/current/schema-registry/develop/api.html)
- [OpenAPI](openapi/schema-registry.yml)
- [JSON Schema](json-schema/schema-registry-schema.json)
- [JSON-LD Context](json-ld/confluent-schema-registry-context.jsonld)
- [Spectral Ruleset](rules/confluent-schema-registry-rules.yml)
- [Naftiko Capabilities](capabilities/confluent-schema-registry-capabilities.yml)
- [GitHub](https://github.com/confluentinc/schema-registry)

#### Features

- Avro Schema Support
- JSON Schema Support
- Protobuf Schema Support
- Schema Versioning
- Compatibility Levels (BACKWARD, FORWARD, FULL)
- Transitive Compatibility
- Schema References
- Schema Contexts
- Schema Normalization
- Soft and Hard Delete
- Subject-Level and Global Configuration
- Operating Modes (READWRITE, READONLY, IMPORT)
- Schema Linking via Exporters
- HTTP Basic, mTLS, and OAuth Auth

#### Use Cases

- Register schemas for Kafka producers and consumers
- Evolve schemas safely with compatibility checks
- Reference shared schemas across subjects
- Migrate schemas between clusters with Schema Linking
- Govern data contracts in streaming pipelines

## Common Properties

- [Website](https://www.confluent.io/)
- [Documentation](https://docs.confluent.io/platform/current/schema-registry/)
- [Getting Started](https://docs.confluent.io/platform/current/schema-registry/develop/using.html)
- [API Reference](https://docs.confluent.io/platform/current/schema-registry/develop/api.html)
- [GitHub](https://github.com/confluentinc/schema-registry)
- [License](https://www.confluent.io/confluent-community-license/)
- [Blog](https://www.confluent.io/blog/)
- [Pricing](https://www.confluent.io/pricing/)
- [JSON-LD Context](json-ld/confluent-schema-registry-context.jsonld)
- [Spectral Ruleset](rules/confluent-schema-registry-rules.yml)
- [Naftiko Capabilities](capabilities/confluent-schema-registry-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
