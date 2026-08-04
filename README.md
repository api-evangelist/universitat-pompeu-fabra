# Universitat Pompeu Fabra (universitat-pompeu-fabra)

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

Universitat Pompeu Fabra (UPF) is a public research university in Barcelona, Spain, ranked #266 in the QS World University Rankings 2025. This repository catalogs UPF's public developer and API footprint as an APIs.json provider profile for the API Evangelist network. The confirmed footprint centers on the "UPF en Xifres 2.0" linked open data portal (CKAN + SPARQL) and the e-Repositori institutional repository (DSpace 7.6 REST API + OAI-PMH).

- APIs.json: https://raw.githubusercontent.com/api-evangelist/universitat-pompeu-fabra/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=universitat-pompeu-fabra-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Open Data, Research, Library, Repository, SPARQL, OAI-PMH, Spain, Barcelona

## APIs

- **UPF Open Data CKAN API** — CKAN action API for the UPF Open Data portal. Docs: https://data.upf.edu/about
- **UPF Open Data SPARQL Endpoint** — Virtuoso SPARQL endpoint for linked open data. Docs: https://data.upf.edu/about
- **UPF Digital Repository REST API (DSpace 7)** — DSpace 7.6 REST/HAL API for the e-Repositori. Docs: https://repositori.upf.edu/server/api
- **UPF Digital Repository OAI-PMH** — OAI-PMH 2.0 metadata harvesting endpoint. Docs: https://repositori-api.upf.edu/oai/request?verb=Identify

## Plans / Rate Limits / FinOps

- Plans: [plans/universitat-pompeu-fabra-plans-pricing.yml](plans/universitat-pompeu-fabra-plans-pricing.yml)
- Rate Limits: [rate-limits/universitat-pompeu-fabra-rate-limits.yml](rate-limits/universitat-pompeu-fabra-rate-limits.yml)
- FinOps: [finops/universitat-pompeu-fabra-finops.yml](finops/universitat-pompeu-fabra-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.upf.edu/en/home
- Developer Portal (Open Data): https://data.upf.edu/about
- GitHub (Music Technology Group): https://github.com/mtg
- LinkedIn: https://www.linkedin.com/school/universitat-pompeu-fabra/
- Authentication (Shibboleth SSO): https://repositori.upf.edu/shibboleth-login

## Notes

- The DSpace REST API and OAI-PMH endpoints were verified live (HTTP 200) on 2026-06-03; the REST root reports DSpace 7.6.8.
- The data.upf.edu open data portal is documented as CKAN + Virtuoso SPARQL but did not resolve from the test network (HTTP 000), likely due to geo/firewall restrictions. It is cataloged from official documentation, not a live probe.
- UPF identity uses adAS / Shibboleth SAML SSO and is gated. No public institutional API key program or unified developer portal was found.
- Research-group code (e.g. MTG, aig-upf, IPCV, wn-upf) lives on GitHub but is not an institutional API offering.
- No endpoints were fabricated; unverifiable items are noted as such in review.yml.

## Maintainers

- Kin Lane — kin@apievangelist.com
