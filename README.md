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

Universitat Pompeu Fabra (UPF) is a public research university in Barcelona, Catalonia, Spain, founded in 1990 and ranked #266 in the QS World University Rankings 2025. This repository catalogs UPF's public developer and API footprint as an APIs.json provider profile for the API Evangelist network. Re-profiled 2026-09-01 under the university pipeline, which settles **who operates each surface** before saving anything. UPF operates no developer portal and publishes no OpenAPI, AsyncAPI or SDK of its own. What it does operate, verified live, is the e-Repositori institutional repository on its own domain (DSpace 7.6.8 REST/HAL API + OAI-PMH 2.0 + a deployed Shibboleth SP), alongside a SAML identity in eduGAIN via RedIRIS SIR and Crossref/ROR registry memberships.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/universitat-pompeu-fabra/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=universitat-pompeu-fabra-api-evangelist&utm_content=repo

## Type

- university / Public Research University
- Index
- Consumer
- 3rd-Party

## Tags

University, Higher Education, Education, Public Research University, Spain, Catalonia, Barcelona, Institutional Repository, Research Data, Identity Federation, OAI-PMH, DSpace, Shibboleth, Crossref

## Surfaces (each carries an operator)

| Surface | Operator | Base |
|---|---|---|
| UPF Digital Repository REST API (DSpace 7.6.8) | `institution` | https://repositori.upf.edu/server/api |
| UPF Digital Repository OAI-PMH | `institution` | https://repositori-api.upf.edu/oai/request |
| UPF SAML 2.0 Identity Provider (RedIRIS SIR / eduGAIN) | `federation` | https://www.rediris.es/sir/upfidp |
| Crossref membership (member 14960, prefix 10.31009) | `registry` | https://api.crossref.org/members/14960 |
| ROR registration (04n0g0b29) | `registry` | https://api.ror.org/v2/organizations/04n0g0b29 |
| Guies BibTIC (Springshare LibGuides tenant) | `tenant` | https://guiesbibtic.upf.edu/iag |

No specification is saved for the DSpace REST API: the deployment and the content are UPF's, but the contract is the DSpace project's generic open-source one and belongs with DSpace, not with UPF.

## Conformance (education regime)

- [conformance/universitat-pompeu-fabra-conformance.yml](conformance/universitat-pompeu-fabra-conformance.yml)
- Live-evidenced: `oai-pmh`, `shibboleth`, `saml`, `crossref`. Recorded false with evidence: `datacite`, `scim`, `lti`, `orcid`, `oneroster`, `ed-fi`, `caliper`, `qti`.

## Plans / Rate Limits / FinOps

- Plans: [plans/universitat-pompeu-fabra-plans-pricing.yml](plans/universitat-pompeu-fabra-plans-pricing.yml)
- Rate Limits: [rate-limits/universitat-pompeu-fabra-rate-limits.yml](rate-limits/universitat-pompeu-fabra-rate-limits.yml)
- FinOps: [finops/universitat-pompeu-fabra-finops.yml](finops/universitat-pompeu-fabra-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://www.upf.edu/en/home (HTTP 403 — Cloudflare bot challenge; live but unreadable by us)
- API Reference: https://repositori.upf.edu/server/api
- Research Repository: https://repositori.upf.edu
- Identity Federation: https://www.rediris.es/sir/upfidp
- AI Policy / AI Tooling: https://guiesbibtic.upf.edu/iag
- GitHub (Music Technology Group): https://github.com/MTG
- LinkedIn: https://www.linkedin.com/school/universitat-pompeu-fabra/

## Notes

- **The `data.upf.edu` open data portal is gone.** The June 2026 profile was built around "UPF en Xifres 2.0" — a CKAN action API and a Virtuoso SPARQL endpoint at `data.upf.edu` — and recorded both as APIs. That host now returns an authoritative NXDOMAIN from UPF's own nameservers (ns1-ns6.upf.edu), reproduced against 8.8.8.8 and 1.1.1.1. The June profile had itself observed HTTP 000 and excused it as "likely geo/firewall restrictions", cataloging the portal from documentation rather than a live probe. Both API entries and the DeveloperPortal pointer have been removed as dead.
- The DSpace REST API and OAI-PMH endpoints were re-verified live on 2026-09-01: 78 communities, 1,022 collections, 43,503 discoverable objects, 13 OAI metadata formats, 100 sets, earliest datestamp 2009-01-23.
- `repositori.upf.edu` advertises a real Shibboleth SP: the REST API answers with `WWW-Authenticate: shibboleth ... location="https://repositori.upf.edu/Shibboleth.sso/Login?..."`.
- `guiesbibtic.upf.edu` is a vendor tenancy behind an institution hostname — it CNAMEs to `secure-eu.libguides.com` (Springshare). The content is UPF's; the platform is not.
- Every `www.upf.edu` URL, including `/llms.txt` and `/robots.txt`, returns HTTP 403 from a Cloudflare bot challenge. That is a finding about the edge, not a gap in UPF.
- No course catalog, timetable, registrar, library discovery, research-computing or campus-life API was found on any upf.edu host. `api.upf.edu` resolves but resets the TLS connection.
- Research-group code (MTG, aig-upf, IPCV, wn-upf, TalnUPF, decolab) lives on GitHub but is not an institutional API offering.
- No endpoints were fabricated; every claim above is backed by a status code recorded in `x-coverage.evidence` in apis.yml.

## Maintainers

- Kin Lane — kin@apievangelist.com
