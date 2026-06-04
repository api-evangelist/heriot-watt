# Heriot-Watt University (heriot-watt)

Heriot-Watt University is a public research university based in Edinburgh, Scotland, with additional campuses in the Scottish Borders, Orkney, Dubai, and Malaysia, ranked #257 in the QS World University Rankings 2025. This repository catalogs the university's public, machine-readable footprint as an APIs.json provider profile. Heriot-Watt does not run a public developer portal; its programmatic surface comes from platform products — the Research Portal (Elsevier Pure), Library Discovery (Ex Libris Alma/Primo), and Springshare LibCal — whose APIs exist as platform features but are gated rather than openly self-service.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/heriot-watt/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=heriot-watt-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Scotland, United Kingdom, Research, Library, Open Access

## APIs

- **Heriot-Watt Research Portal (Pure)** — Public research information portal (publications, projects, data, profiles) powered by Elsevier Pure. Docs: https://www.hw.ac.uk/uk/research/research-portal.htm — Portal: https://researchportal.hw.ac.uk/
- **Heriot-Watt Library Discovery (Ex Libris Primo / Alma)** — Library catalogue and resource discovery on the Ex Libris Alma platform with the Primo interface. Docs: https://www.hw.ac.uk/about/professional-services/information-services/find-resources
- **Heriot-Watt LibCal (Springshare)** — Library room bookings, events, and hours. Docs: https://hw.ac.libcal.com/

Note: The Pure OAI-PMH/REST, Primo/Alma REST, and LibCal REST APIs are platform capabilities that require credentials, an API key, or institutional arrangement. No openly self-service public API endpoints were confirmed.

## Plans, Rate Limits & FinOps

- Plans: [plans/heriot-watt-plans-pricing.yml](plans/heriot-watt-plans-pricing.yml)
- Rate Limits: [rate-limits/heriot-watt-rate-limits.yml](rate-limits/heriot-watt-rate-limits.yml)
- FinOps: [finops/heriot-watt-finops.yml](finops/heriot-watt-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.hw.ac.uk/
- Status: https://www.hwstatus.info/
- LinkedIn: https://uk.linkedin.com/school/heriot-watt-university/
- Review: [review.yml](review.yml)

## Notes

- No public developer portal was found (`https://www.hw.ac.uk/developers` returns 404).
- No official Heriot-Watt GitHub organization exists; the `HerriotWatt` GitHub org is an unrelated student course-project account and is intentionally excluded.
- The Research Portal is publicly browsable, but its Pure OAI-PMH endpoint (`/ws/oai`) redirects to an error and is not openly available.
- Library Discovery (Alma/Primo) and LibCal expose vendor REST APIs that require credentials/API keys; no open endpoints were cataloged.
- All listed URLs were verified by live HTTP probing on 2026-06-03; see [review.yml](review.yml) for status codes. No endpoints or schemas were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
