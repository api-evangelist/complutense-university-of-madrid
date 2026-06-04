# Complutense University of Madrid (complutense-university-of-madrid)

Complutense University of Madrid (Universidad Complutense de Madrid, UCM) is a major public research university in Spain, ranked #164 in the QS World University Rankings 2025. This repository catalogs UCM's public, machine-readable developer/API footprint as an APIs.json profile. UCM's footprint is centered on open data through UniversiDATA, the collaborative Spanish higher-education open-data platform in which it is a founding participant, plus the Docta Complutense institutional repository.

APIs.json: https://raw.githubusercontent.com/api-evangelist/complutense-university-of-madrid/refs/heads/main/apis.yml

Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=complutense-university-of-madrid-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Open Data, Research, Spain

## APIs

- **UniversiDATA DataStore API** — DataStore query API (DKAN), returns published data records in JSON/XML/JSONP. Docs: https://www.universidata.es/el-api
- **UniversiDATA CKAN Dataset API** — CKAN-compatible dataset/resource metadata API. Docs: https://www.universidata.es/el-api
- **UniversiDATA DCAT Catalog API** — DCAT catalog API per participating university (UCM by acronym). Docs: https://www.universidata.es/el-api
- **Docta Complutense Institutional Repository** — UCM open-access repository on DSpace 7; programmatic REST/OAI-PMH not confirmed at standard paths. Docs: https://docta.ucm.es/

## Plans / Rate Limits / FinOps

- Plans: [plans/complutense-university-of-madrid-plans-pricing.yml](plans/complutense-university-of-madrid-plans-pricing.yml)
- Rate Limits: [rate-limits/complutense-university-of-madrid-rate-limits.yml](rate-limits/complutense-university-of-madrid-rate-limits.yml)
- FinOps: [finops/complutense-university-of-madrid-finops.yml](finops/complutense-university-of-madrid-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ucm.es/
- GitHub: https://github.com/UniversidadComplutense
- LinkedIn: https://www.linkedin.com/school/universidad-complutense-de-madrid/
- Developer Portal: https://www.universidata.es/el-api
- Review: [review.yml](review.yml)

## Notes

All cataloged APIs and properties were verified live or against official documentation as of 2026-06-03. The UniversiDATA DataStore, CKAN, and DCAT APIs are documented at https://www.universidata.es/el-api and the CKAN dataset list endpoint resolved with HTTP 200. Docta Complutense is a DSpace 7 repository; its DSpace REST and OAI-PMH machine endpoints were not reachable at standard paths during review, so the repository is cataloged only at the human-facing level — no endpoints were fabricated. No dedicated UCM SIS, course/timetable, or library (Alma/Primo) developer API was found publicly documented.

## Maintainers

- Kin Lane — kin@apievangelist.com
