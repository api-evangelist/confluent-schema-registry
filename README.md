# Confluent Schema Registry (confluent-schema-registry)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
