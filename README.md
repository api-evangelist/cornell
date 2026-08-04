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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Cornell University is a private Ivy League and statutory land-grant research university in Ithaca, New York, ranked #16 in the QS World University Rankings 2025. Its public developer footprint is decentralized: a documented Class Roster API for course data, the eCommons DSpace repository (REST + OAI-PMH), the Cornell-hosted arXiv API, and the student-led Cornell Open Data Initiative (CODI).

- APIs.json: https://raw.githubusercontent.com/api-evangelist/cornell/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=cornell-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Open Data, Course Catalog, Library, Research, United States

## APIs

- **Cornell Class Roster API** — Course and scheduling data (v2.0, JSON/XML, GET only). Docs: https://classes.cornell.edu/content/FA25/api-details
- **eCommons Digital Repository (DSpace REST + OAI-PMH)** — Cornell University Library institutional repository. Docs: https://guides.library.cornell.edu/ecommons/syndication
- **arXiv API** — Cornell-hosted e-print search and metadata retrieval (Atom). Docs: https://info.arxiv.org/help/api/index.html
- **Cornell Open Data Initiative (CODI)** — Student-led open data for map, transit, dining, and events (partly archived). Site: https://codi.engineering.cornell.edu/ · GitHub: https://github.com/cornell-data

## Plans / Rate Limits / FinOps

- Plans: [plans/cornell-plans-pricing.yml](plans/cornell-plans-pricing.yml)
- Rate Limits: [rate-limits/cornell-rate-limits.yml](rate-limits/cornell-rate-limits.yml)
- FinOps: [finops/cornell-finops.yml](finops/cornell-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.cornell.edu/
- GitHub: https://github.com/cornell-data
- LinkedIn: https://www.linkedin.com/school/cornell-university/
- Authentication (Shibboleth/SAML IdP): https://shibidp.cit.cornell.edu/idp/shibboleth

## Notes

All endpoints in this profile were probed with curl on 2026-06-03. The Class Roster API, eCommons REST/OAI-PMH, and arXiv API resolved 200 (the arXiv query endpoint returned 429 on first probe due to rate limiting, then 200). CODI is real and live but several of its data repositories are archived and its platform is self-described as in revamp / likely outdated, so it is cataloged honestly rather than as a stable production API. The LinkedIn page returns HTTP 999 (LinkedIn anti-bot) but exists in a browser. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
