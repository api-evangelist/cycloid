# Cycloid

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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

**Areas:** Asset Inventory · CI/CD · Cloud Cost Management · Cloud Management · Developer Experience · Developer Tools · DevOps · FinOps · GitOps · GreenOps · Infrastructure as Code · Internal Developer Platform

## Cycloid on APIs.io

Everything profiled for Cycloid is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cycloid/](https://apis.io/providers/cycloid/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Cycloid CloudCost API](https://apis.io/apis/cycloid/cycloid-cloudcost-api/) — Cloud cost provider accounts, dashboards, and tag mappings.
- [Cycloid ConfigRepositories API](https://apis.io/apis/cycloid/cycloid-configrepositories-api/) — Git config repositories used by stacks and pipelines.
- [Cycloid Credentials API](https://apis.io/apis/cycloid/cycloid-credentials-api/) — Credential storage and rotation.
- [Cycloid Inventory API](https://apis.io/apis/cycloid/cycloid-inventory-api/) — Inventory of cloud resources and state locking.
- [Cycloid Organizations API](https://apis.io/apis/cycloid/cycloid-organizations-api/) — Manage organizations, members, teams, and events.
- [Cycloid Pipelines API](https://apis.io/apis/cycloid/cycloid-pipelines-api/) — CI/CD pipelines, components, and build tracking.
- [Cycloid Projects API](https://apis.io/apis/cycloid/cycloid-projects-api/) — Projects and environments inside an organization.
- [Cycloid ServiceCatalogs API](https://apis.io/apis/cycloid/cycloid-servicecatalogs-api/) — Stacks (Service Catalog) and StackForms.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [MCP Server](https://apis.io/servers/cycloid/mcp-server/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cycloid Agentic Access](https://apis.io/agentic-access/cycloid/cycloid-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Organization](https://apis.io/schemas/cycloid/cycloid-organization/)
- [Stack](https://apis.io/schemas/cycloid/cycloid-stack/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cycloid Context](https://apis.io/jsonld/cycloid/cycloid-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Cycloid Vocabulary](https://apis.io/vocabularies/cycloid/cycloid-vocabulary/)

#### Collections (17)

Postman and Open Collection request collections.

- [Cycloid HTTP API](https://apis.io/collections/cycloid/open-cycloid-api/)
- [Cycloid HTTP CloudCost API](https://apis.io/collections/cycloid/open-cycloid-cloudcost-api/)
- [Cycloid HTTP CloudCost ConfigRepositories API](https://apis.io/collections/cycloid/open-cycloid-configrepositories-api/)
- [Cycloid HTTP CloudCost Credentials API](https://apis.io/collections/cycloid/open-cycloid-credentials-api/)
- [Cycloid HTTP CloudCost Inventory API](https://apis.io/collections/cycloid/open-cycloid-inventory-api/)
- [Cycloid HTTP CloudCost Organizations API](https://apis.io/collections/cycloid/open-cycloid-organizations-api/)
- [Cycloid HTTP CloudCost Pipelines API](https://apis.io/collections/cycloid/open-cycloid-pipelines-api/)
- [Cycloid HTTP CloudCost Projects API](https://apis.io/collections/cycloid/open-cycloid-projects-api/)
- [Cycloid HTTP CloudCost ServiceCatalogs API](https://apis.io/collections/cycloid/open-cycloid-servicecatalogs-api/)
- [Cycloid HTTP CloudCost API](https://apis.io/collections/cycloid/postman-cycloid-cloudcost-api/)
- [Cycloid HTTP CloudCost ConfigRepositories API](https://apis.io/collections/cycloid/postman-cycloid-configrepositories-api/)
- [Cycloid HTTP CloudCost Credentials API](https://apis.io/collections/cycloid/postman-cycloid-credentials-api/)
- [Cycloid HTTP CloudCost Inventory API](https://apis.io/collections/cycloid/postman-cycloid-inventory-api/)
- [Cycloid HTTP CloudCost Organizations API](https://apis.io/collections/cycloid/postman-cycloid-organizations-api/)
- [Cycloid HTTP CloudCost Pipelines API](https://apis.io/collections/cycloid/postman-cycloid-pipelines-api/)
- [Cycloid HTTP CloudCost Projects API](https://apis.io/collections/cycloid/postman-cycloid-projects-api/)
- [Cycloid HTTP CloudCost ServiceCatalogs API](https://apis.io/collections/cycloid/postman-cycloid-servicecatalogs-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Cycloid — api rules](https://apis.io/rules/cycloid/cycloid-api-rules/)
- [Cycloid — jsonschema rules](https://apis.io/rules/cycloid/cycloid-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Cycloid Authentication](https://apis.io/security/cycloid/cycloid-authentication/)
- [Cycloid Domain Security](https://apis.io/security/cycloid/cycloid-domain-security/)
- [Cycloid Trust Center](https://apis.io/security/cycloid/cycloid-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Cycloid Scopes](https://apis.io/scopes/cycloid/cycloid-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cycloid Plans Pricing](https://apis.io/plans/cycloid/cycloid-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cycloid Rate Limits](https://apis.io/rate-limits/cycloid/cycloid-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cycloid Finops](https://apis.io/finops/cycloid/cycloid-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.cycloid.io)
- [Documentation](https://docs.cycloid.io)
- [Pricing](https://www.cycloid.io/pricing)
- [Blog](https://www.cycloid.io/blog)
- [Terms of service](https://www.cycloid.io/legal/terms-and-conditions)
- [Privacy policy](https://www.cycloid.io/legal/privacy-policy)
- [GitHub](https://github.com/cycloidio)
- [Status](https://status.cycloid.io)

## API Evangelist rating

**Kin Score 37.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 49.5 |
| Contract governance | 27.3 |
| Operational transparency | 26.3 |
| Developer ergonomics | 13.1 |
| Access clarity | 32.9 |

**Agent readiness 23.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 31.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cycloid/](https://apis.io/providers/cycloid/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cycloid: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cycloid/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
