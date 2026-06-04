# Cornell University (cornell)

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
