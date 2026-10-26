# Cornell University (cornell)

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

Cornell University is a private Ivy League and statutory land-grant research university in Ithaca, New York. It runs no developer portal and no API gateway. The surfaces it genuinely operates, all verified live on 2026-08-19, are the Class Roster API (classes.cornell.edu), Cornell University Library's self-hosted Blacklight catalog and CUGIR geospatial repository, its own Shibboleth/InCommon SAML identity metadata, and — through the Cornell Lab of Ornithology — the token-gated eBird API 2.0. Two further surfaces are tenant relationships on vendor platforms (eCommons on 4Science-managed DSpace, the events calendar on Localist) and their contracts belong to those vendors, not to Cornell.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/cornell/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=cornell-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

University, Higher Education, Education, Ivy League, United States, Course Catalog, Library, Research Data, Geospatial, Identity Federation

## APIs

Every entry carries an operator: `institution` means Cornell runs the thing the contract describes; `tenant` means Cornell's data on someone else's platform, so the contract is not credited to Cornell.

- **Cornell Class Roster API** — `institution`. Course and scheduling data (v2.0, JSON/XML, GET only, no auth, 1 req/sec). Docs: https://classes.cornell.edu/content/FA26/api-details
- **Cornell University Library Catalog Search API** — `institution`. The library's own Blacklight deployment; JSON on every catalog route. Contract derived from live probes — Cornell publishes no API reference.
- **CUGIR — Cornell University Geospatial Information Repository API** — `institution`. GeoBlacklight JSON:API search and records. Contract derived from live probes.
- **eBird API 2.0** — `institution` (affiliate domain). Run by the Cornell Lab of Ornithology; free but token-gated. Docs: https://documenter.getpostman.com/view/664302/S1ENwy59
- **eCommons Institutional Repository (DSpace REST + OAI-PMH)** — `tenant`. Cornell's repository and Cornell's data on a 4Science-managed DSpace 8.2 platform. Docs: https://guides.library.cornell.edu/ecommons/syndication
- **Cornell Events Calendar API** — `tenant`. Live JSON at events.cornell.edu/api/2, but a Localist (Concept3D) product API — response header `x-slzr-platform: cornell`.

### Removed 2026-08-19

- **arXiv API** — arXiv spun out of Cornell as an independent nonprofit on 2026-07-01. No longer a Cornell surface.
- **Cornell Dining, Cornell Days and campus map APIs** — all dead: identical SPA shell on every dining path, a 301 to admissions.cornell.edu, and a 404 on the map overlay endpoint.
- **Seven refined OpenAPIs** — they had welded five Cornell Open Data Initiative specs, describing five different hosts, onto one servers[] entry (`https://classes.cornell.edu/api/2.0`).

## Plans / Rate Limits / FinOps

- Plans: [plans/cornell-plans-pricing.yml](plans/cornell-plans-pricing.yml)
- Rate Limits: [rate-limits/cornell-rate-limits.yml](rate-limits/cornell-rate-limits.yml)
- FinOps: [finops/cornell-finops.yml](finops/cornell-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.cornell.edu/
- Course Catalog: https://classes.cornell.edu/
- Library Catalog: https://catalog.library.cornell.edu/
- Research Repository: https://ecommons.cornell.edu/
- Open Data (geospatial): https://cugir.library.cornell.edu/
- Identity Federation (Shibboleth IdP metadata): https://shibidp.cit.cornell.edu/idp/shibboleth
- Identity Federation (InCommon MDQ entry): https://mdq.incommon.org/entities/https:%2F%2Fshibidp.cit.cornell.edu%2Fidp%2Fshibboleth
- Research Computing: https://www.cac.cornell.edu/services/
- AI Policy: https://it.cornell.edu/ai/ai-guidelines
- GitHub (Cornell University Library): https://github.com/cul
- GitHub (Cornell Open Data Initiative): https://github.com/cornell-data
- LinkedIn: https://www.linkedin.com/school/cornell-university/

## Notes

Re-profiled on 2026-08-19 under the API Evangelist university pipeline, which settles WHO OPERATES a surface
before saving any contract. Every URL in this profile was probed with curl on that date and the status codes are
recorded in `apis.yml` under `x-coverage.evidence` and in `review.yml`. The re-profile removes more than it adds
and should lower this institution's score: that is the correction working. Education-regime conformance found on
Cornell's own surfaces — Shibboleth, SAML (InCommon/eduGAIN) and OAI-PMH — is recorded with per-URL evidence in
[conformance/cornell-education-standards-conformance.yml](conformance/cornell-education-standards-conformance.yml).
No endpoints were fabricated. The LinkedIn page returns HTTP 999 (LinkedIn anti-bot) but exists in a browser.

## Maintainers

- Kin Lane — kin@apievangelist.com
