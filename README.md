# Cornell University

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

Cornell University is a private Ivy League and statutory land-grant research university in Ithaca, New York. It operates no central developer portal, no API gateway and no published API program, and this profile records that plainly. What it does operate, directly and on its own hosts, is a small set of real machine-readable surfaces: the Class Roster API on classes.cornell.edu (public, read-only, version 2.0, maintained behind the scenes by the Office of the University Registrar), the Cornell University Library's self-hosted Blacklight catalog and CUGIR geospatial repository, both of which answer JSON on every route, its own Shibboleth identity provider published as SAML 2.0 metadata and registered with InCommon/eduGAIN, and — through the Cornell Lab of Ornithology — the token-gated eBird API 2.0. Everything else that looks like a Cornell API belongs to somebody else: the events calendar at events.cornell.edu is a Localist tenancy, eCommons is a 4Science-managed DSpace instance, and arXiv, hosted at Cornell for twenty-five years, spun out as an independent nonprofit on 2026-07-01 and is no longer a Cornell surface at all. The Cornell Open Data Initiative specs that once padded this profile described a dining API, a campus-map API and a Cornell Days API that are all dead as of 2026-08-19.

**Areas:** University · Higher Education · Education · Ivy League · United States · Course Catalog · Library · Research Data · Geospatial · Identity Federation

## Cornell University on APIs.io

Everything profiled for Cornell University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cornell/](https://apis.io/providers/cornell/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Cornell University Library Catalog Search API](https://apis.io/apis/cornell/library-catalog/) — JSON search over Cornell University Library's catalog. The catalog is the library's own Blacklight deployment; appending .json to any catalog route returns…
- [eBird API 2.0](https://apis.io/apis/cornell/ebird/) — Global bird-observation API run by the Cornell Lab of Ornithology, a unit of Cornell University. Free but token-gated: requests without a valid…
- [eCommons Institutional Repository (DSpace REST + OAI-PMH) — tenant](https://apis.io/apis/cornell/ecommons/) — eCommons is Cornell University Library's institutional repository: Cornell's content, Cornell's DOIs, Cornell's host. The interface is not Cornell's…
- [Cornell Events Calendar API (Localist) — tenant](https://apis.io/apis/cornell/events-calendar/) — The Cornell events calendar at events.cornell.edu answers a live JSON API at /api/2/events, and the data is Cornell's. The platform is Localist (Concept3D):…
- [Cornell University Cugir API](https://apis.io/apis/cornell/cornell-cugir-api/) — Search and retrieve Cornell geospatial datasets and historical maps.
- [Cornell University Config API](https://apis.io/apis/cornell/cornell-config-api/) — The config API from Cornell University — 5 operation(s) for config.
- [Cornell University Search API](https://apis.io/apis/cornell/cornell-search-api/) — The search API from Cornell University — 1 operation(s) for search.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cornell Agentic Access](https://apis.io/agentic-access/cornell/cornell-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Cornell Class](https://apis.io/schemas/cornell/cornell-class/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Cornell Class Structure](https://apis.io/json-structure/cornell/cornell-class-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cornell Context](https://apis.io/jsonld/cornell/cornell-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Cornell Open Data Initiative Vocabulary](https://apis.io/vocabularies/cornell/cornell-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Cornell Class Roster Rosters Example](https://apis.io/examples/cornell/cornell-class-roster-rosters-example/)
- [Cornell Ecommons Dspace Root Example](https://apis.io/examples/cornell/cornell-ecommons-dspace-root-example/)
- [Cornell Library Catalog Search Example](https://apis.io/examples/cornell/cornell-library-catalog-search-example/)
- [Cornell Search Classes Example](https://apis.io/examples/cornell/cornell-search-classes-example/)
- [Cugir Record Example](https://apis.io/examples/cornell/cugir-record-example/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Cornell University — jsonschema rules](https://apis.io/rules/cornell/cornell-jsonschema-spectral-rules/)
- [Cornell University API Rules](https://apis.io/rules/cornell/cornell-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Cornell Authentication](https://apis.io/security/cornell/cornell-authentication/)
- [Cornell Domain Security](https://apis.io/security/cornell/cornell-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cornell Plans Pricing](https://apis.io/plans/cornell/cornell-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cornell Rate Limits](https://apis.io/rate-limits/cornell/cornell-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cornell Finops](https://apis.io/finops/cornell/cornell-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.cornell.edu/)
- [Documentation](https://classes.cornell.edu/content/FA26/api-details)
- [API reference](https://classes.cornell.edu/content/FA26/api-details)
- [Support](https://it.cornell.edu/support)
- [Terms of service](https://policy.cornell.edu/)
- [Privacy policy](https://privacy.cornell.edu/university-privacy-statement)
- [GitHub](https://github.com/cul)

## API Evangelist rating

**Kin Score 32.6** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 39.2 |
| Contract governance | 17.4 |
| Operational transparency | 23.7 |
| Developer ergonomics | 21.4 |
| Access clarity | 26.3 |

**Agent readiness 25.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cornell/](https://apis.io/providers/cornell/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cornell University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cornell/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
