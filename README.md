# Universitat Pompeu Fabra (universitat-pompeu-fabra)

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
