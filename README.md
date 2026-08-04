# Cycloid (cycloid)

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

Cycloid is a unified Internal Developer Portal & Platform combining self-service Service Catalogs (Stacks and StackForms), Infrastructure as Code orchestration, multi-cloud asset inventory (Asset Inventory and InfraView), CI/CD pipeline centralization, FinOps and GreenOps cost / carbon dashboards, RBAC governance, and an MCP server for natural-language interaction. Cycloid exposes a public HTTP REST API at http-api.cycloid.io for programmatic management of organizations, projects, environments, stacks, pipelines, credentials, config repositories, and cloud cost dashboards. Authentication is via API key or OAuth2 with token refresh; the canonical Swagger / Redoc reference is published at docs.cycloid.io.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cycloid/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cycloid/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Asset Inventory
- CI/CD
- Cloud Cost Management
- Cloud Management
- Developer Experience
- DevOps
- FinOps
- GitOps
- GreenOps
- Infrastructure as Code
- Internal Developer Platform
- Internal Developer Portal
- Multi-Cloud
- Platform Engineering
- RBAC
- Self-Service
- Service Catalog
- StackForms
- Terraform

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### Cycloid HTTP API

The Cycloid HTTP API is the programmatic surface of the Cycloid Internal Developer Portal & Platform. It manages organizations, members, teams, projects, environments, stacks (Service Catalog), pipelines, infrastructure resources, credentials, config repositories, cloud cost dashboards, and inventory. Authentication uses an API key or OAuth2 with token refresh.

- **Human URL:** [https://docs.cycloid.io/](https://docs.cycloid.io/)
- **Base URL:** `https://http-api.cycloid.io`

#### Tags

- API Key
- Cloud Cost
- Credentials
- Inventory
- OAuth2
- Organizations
- Pipelines
- Projects
- Service Catalog
- Stacks

#### Properties

- [Documentation](https://docs.cycloid.io/)
- [Getting Started](https://docs.cycloid.io/getting-started)
- [OpenAPI](openapi/cycloid-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cycloid-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cycloid-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Capabilities](capabilities/cycloid-api-capabilities.yml)
- [Rules](rules/cycloid-api-rules.yml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/cycloid)
- [Website](https://www.cycloid.io)
- [Documentation](https://docs.cycloid.io)
- [Pricing](https://www.cycloid.io/pricing)
- [GitHub Organization](https://github.com/cycloidio)
- [Blog](https://www.cycloid.io/blog)
- [Status Page](https://status.cycloid.io)
- [Login](https://console.cycloid.io)
- [Terms of Service](https://www.cycloid.io/legal/terms-and-conditions)
- [Privacy Policy](https://www.cycloid.io/legal/privacy-policy)
- [Contact](https://www.cycloid.io/contact)
- [JSON-LD](json-ld/cycloid-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/cycloid-organization-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cycloid-stack-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](vocabulary/cycloid-vocabulary.yml)
- [Capabilities](capabilities/cycloid-api-capabilities.yml)
- [Rules](rules/cycloid-api-rules.yml)
- [M C P Server](https://github.com/cycloidio/cycloid-mcp-server)
- [L L Ms Txt](https://docs.cycloid.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
