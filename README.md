# Complutense University of Madrid

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

Universidad Complutense de Madrid (UCM) is Spain's largest public research university, founded 1499 and ranked #164 in the QS World University Rankings 2025. UCM operates no central developer portal and publishes no OpenAPI, AsyncAPI or SDK of its own — a re-profile on 2026-08-30 probed every candidate host and found none. What it does operate, verified live, is two things. First, Docta Complutense (docta.ucm.es), its institutional repository, self-hosted on UCM's own domain running DSpace 7.6.5: the DSpace REST/HAL API answers at /rest/api and an OAI-PMH 2.0 endpoint answers verb=Identify at /rest/oai/request with twelve metadata formats. The repository is UCM's; the API contract is DSpace's open-source one and is not saved here. Second, UCM is registered in eduGAIN through the Spanish RedIRIS SIR federation as a SAML 2.0 Identity Provider (entityID https://www.rediris.es/sir/ucmidp, scope ucm.es, Sirtfi asserted) — machine-readable, institution-scoped, but hosted on RedIRIS infrastructure, so recorded as a tenant relationship. UCM's open data is not self-hosted either: it is published through UniversiDATA, a five-university DKAN consortium portal (UAM, UCM, UHU, UVa, URJC) that exposes DataStore, CKAN and DCAT APIs. Thirteen of the portal's seventy-one datasets are UCM's — degree programmes, faculties, departments, budgets, mobility and procurement. UCM's data, the consortium's platform, so every UniversiDATA surface below is x-operator tenant, not institution. No course/timetable API, no library discovery API, no research-computing or campus-life API was found on any ucm.es host.

**Areas:** University · Higher Education · Education · Public Research University · Spain · Madrid · Open Data · Research Data · Institutional Repository · Identity Federation · OAI-PMH · DSpace

## Complutense University of Madrid on APIs.io

Everything profiled for Complutense University of Madrid is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/complutense-university-of-madrid/](https://apis.io/providers/complutense-university-of-madrid/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Docta Complutense Repository API (DSpace 7)](https://apis.io/apis/complutense-university-of-madrid/docta-complutense/) — Docta Complutense is UCM's open-access institutional repository, migrated in 2023 to DSpace 7 and self-hosted on UCM's own domain. Probed 2026-08-30: GET…
- [Docta Complutense OAI-PMH Endpoint](https://apis.io/apis/complutense-university-of-madrid/docta-oai-pmh/) — OAI-PMH 2.0 harvesting endpoint for Docta Complutense, on UCM's own host. Probed 2026-08-30: verb=Identify returns HTTP 200 text/xml with repositoryName…
- [UCM SAML 2.0 Identity Provider (RedIRIS SIR / eduGAIN)](https://apis.io/apis/complutense-university-of-madrid/identity-federation/) — UCM's institutional single sign-on, registered in eduGAIN through RedIRIS SIR, the Spanish national research and education federation. entityID…
- [UniversiDATA DataStore API](https://apis.io/apis/complutense-university-of-madrid/universidata-datastore/) — DataStore query API of UniversiDATA, the DKAN open-data platform shared by five Spanish public universities (UAM, UCM, UHU, UVa, URJC) of which UCM is a…
- [UniversiDATA CKAN Dataset API](https://apis.io/apis/complutense-university-of-madrid/universidata-ckan/) — CKAN-compatible metadata API of the UniversiDATA consortium platform, supporting current_package_list_with_resources, package_show and resource_show. Probed…
- [UniversiDATA DCAT Catalog API](https://apis.io/apis/complutense-university-of-madrid/universidata-dcat/) — DCAT catalogue endpoint of UniversiDATA, addressed per participating university by acronym. The UCM catalogue is the only UCM-specific path on this host.…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Complutense University Of Madrid Context](https://apis.io/jsonld/complutense-university-of-madrid/complutense-university-of-madrid-context/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Complutense University Of Madrid Domain Security](https://apis.io/security/complutense-university-of-madrid/complutense-university-of-madrid-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Complutense University Of Madrid Plans Pricing](https://apis.io/plans/complutense-university-of-madrid/complutense-university-of-madrid-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Complutense University Of Madrid Rate Limits](https://apis.io/rate-limits/complutense-university-of-madrid/complutense-university-of-madrid-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Complutense University Of Madrid Finops](https://apis.io/finops/complutense-university-of-madrid/complutense-university-of-madrid-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ucm.es/)
- [Documentation](https://www.universidata.es/el-api)
- [API reference](https://docta.ucm.es/rest)
- [Blog](https://www.ucm.es/news/)
- [Terms of service](https://www.ucm.es/aviso-legal)

## API Evangelist rating

**Kin Score 21.4** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 14.3 |
| Contract governance | 4.5 |
| Operational transparency | 10.5 |
| Developer ergonomics | 25.0 |
| Access clarity | 15.8 |

**Agent readiness 0.6** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
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
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 22.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/complutense-university-of-madrid/](https://apis.io/providers/complutense-university-of-madrid/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Complutense University of Madrid: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/complutense-university-of-madrid/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
