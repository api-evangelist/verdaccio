# Verdaccio

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

Verdaccio is an open-source, lightweight private npm proxy registry built in Node.js that enables organizations to host, cache, and manage packages privately. It implements the CommonJS Compliant Package Registry specification and provides a REST API for publishing, searching, and managing npm packages in self-hosted or cloud-deployed environments. Verdaccio supports JWT and Basic Auth token authentication, rate limiting, pluggable storage backends, and seamless proxying of upstream registries such as npmjs.org.

**Areas:** npm · Registry · Package Manager · private-registry · Proxy · Node.js · Open Source · Self-Hosted · YARN · pnpm · Docker · Kubernetes

## Verdaccio on APIs.io

Everything profiled for Verdaccio is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/verdaccio/](https://apis.io/providers/verdaccio/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Verdaccio npm Registry API](https://apis.io/apis/verdaccio/verdaccio-npm-registry-api/) — The Verdaccio npm Registry REST API implements the CommonJS Compliant Package Registry specification, providing endpoints to publish, retrieve, search, and…
- [Verdaccio Dist Tags API](https://apis.io/apis/verdaccio/verdaccio-dist-tags-api/) — Manage dist-tags for packages
- [Verdaccio Packages API](https://apis.io/apis/verdaccio/verdaccio-packages-api/) — Retrieve package metadata and tarballs
- [Verdaccio Profile API](https://apis.io/apis/verdaccio/verdaccio-profile-api/) — User profile management
- [Verdaccio Publish API](https://apis.io/apis/verdaccio/verdaccio-publish-api/) — Publish, update, and unpublish packages
- [Verdaccio Search API](https://apis.io/apis/verdaccio/verdaccio-search-api/) — Search the registry
- [Verdaccio Tokens API](https://apis.io/apis/verdaccio/verdaccio-tokens-api/) — API token management
- [Verdaccio User API](https://apis.io/apis/verdaccio/verdaccio-user-api/) — User authentication and management
- [Verdaccio Utility API](https://apis.io/apis/verdaccio/verdaccio-utility-api/) — Utility endpoints

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Verdaccio Agentic Access](https://apis.io/agentic-access/verdaccio/verdaccio-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Verdaccio Package Manifest](https://apis.io/schemas/verdaccio/verdaccio-package-manifest/)
- [Verdaccio Publish Request](https://apis.io/schemas/verdaccio/verdaccio-publish-request/)
- [Verdaccio Search Results](https://apis.io/schemas/verdaccio/verdaccio-search-results/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Verdaccio Context](https://apis.io/jsonld/verdaccio/verdaccio-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Verdaccio npm Registry API Vocabulary](https://apis.io/vocabularies/verdaccio/verdaccio-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Verdaccio Login Request Example](https://apis.io/examples/verdaccio/verdaccio-login-request-example/)
- [Verdaccio Publish Package Example](https://apis.io/examples/verdaccio/verdaccio-publish-package-example/)
- [Verdaccio Search Results Example](https://apis.io/examples/verdaccio/verdaccio-search-results-example/)
- [Verdaccio Token Create Example](https://apis.io/examples/verdaccio/verdaccio-token-create-example/)

#### Collections (8)

Postman and Open Collection request collections.

- [Verdaccio npm Registry dist-tags API](https://apis.io/collections/verdaccio/open-verdaccio-dist-tags-api/)
- [Verdaccio npm Registry dist-tags packages API](https://apis.io/collections/verdaccio/open-verdaccio-packages-api/)
- [Verdaccio npm Registry dist-tags profile API](https://apis.io/collections/verdaccio/open-verdaccio-profile-api/)
- [Verdaccio npm Registry dist-tags publish API](https://apis.io/collections/verdaccio/open-verdaccio-publish-api/)
- [Verdaccio npm Registry dist-tags search API](https://apis.io/collections/verdaccio/open-verdaccio-search-api/)
- [Verdaccio npm Registry dist-tags tokens API](https://apis.io/collections/verdaccio/open-verdaccio-tokens-api/)
- [Verdaccio npm Registry dist-tags user API](https://apis.io/collections/verdaccio/open-verdaccio-user-api/)
- [Verdaccio npm Registry dist-tags utility API](https://apis.io/collections/verdaccio/open-verdaccio-utility-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Verdaccio — jsonschema rules](https://apis.io/rules/verdaccio/verdaccio-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Verdaccio Authentication](https://apis.io/security/verdaccio/verdaccio-authentication/)
- [Verdaccio Domain Security](https://apis.io/security/verdaccio/verdaccio-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Verdaccio Plans Pricing](https://apis.io/plans/verdaccio/verdaccio-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Verdaccio Rate Limits](https://apis.io/rate-limits/verdaccio/verdaccio-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Verdaccio Finops](https://apis.io/finops/verdaccio/verdaccio-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.verdaccio.org/)
- [Documentation](https://www.verdaccio.org/docs/)
- [Blog](https://www.verdaccio.org/blog/)

## API Evangelist rating

**Kin Score 36.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 51.8 |
| Contract governance | 9.8 |
| Operational transparency | 36.8 |
| Developer ergonomics | 19.0 |
| Access clarity | 5.3 |

**Agent readiness 22.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/verdaccio/](https://apis.io/providers/verdaccio/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Verdaccio: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/verdaccio/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
