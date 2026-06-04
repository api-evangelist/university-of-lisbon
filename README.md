# University of Lisbon (university-of-lisbon)

The University of Lisbon (Universidade de Lisboa, ULisboa) is Portugal's largest public university and is ranked #260 in the QS World University Rankings 2025. This repository catalogs its public developer and API footprint as an APIs.json provider profile. ULisboa has no single institutional developer portal; its programmable interfaces are decentralized across schools and services, the most prominent being the FenixEdu academic API at Instituto Superior Tecnico and the OAI-PMH metadata interface of the DSpace institutional repository.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-lisbon/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-lisbon-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Portugal, Open Data, Repository, Metadata

## APIs

- **FenixEdu Academic API (Instituto Superior Tecnico)** — Public REST API of the FenixEdu academic information system (people, spaces, degrees, courses, terms). Base URL `https://fenix.tecnico.ulisboa.pt/api/fenix/v1`. Docs: https://fenixedu.org/dev/api/
- **Repositorio da Universidade de Lisboa OAI-PMH** — OAI-PMH 2.0 metadata harvesting for the DSpace institutional open-access repository. Base URL `https://repositorio.ulisboa.pt/server/oai/request`. Home: https://repositorio.ulisboa.pt/

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-lisbon-plans-pricing.yml](plans/university-of-lisbon-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-lisbon-rate-limits.yml](rate-limits/university-of-lisbon-rate-limits.yml)
- FinOps: [finops/university-of-lisbon-finops.yml](finops/university-of-lisbon-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ulisboa.pt/en
- GitHub: https://github.com/ULisboa
- LinkedIn: https://www.linkedin.com/school/universidade-de-lisboa/
- SourceCode: https://github.com/ULisboa
- Plans, RateLimits, FinOps, Review: see files in this repository.

## Notes

All endpoints in this profile were probed live on 2026-06-03. The FenixEdu API (`/api/fenix/v1/about`) and the DSpace OAI-PMH endpoint (`/server/oai/request`) both returned HTTP 200 with valid payloads. The ULisboa GitHub org hosts four open-source Java repositories centered on Erasmus Without Paper (EWP) data exchange. The official website returns 500 to bare requests but 200 with a browser User-Agent. The research portal (Pure) returns 403 to automated requests and was not confirmed to expose a public API. No endpoints were fabricated; see [review.yml](review.yml) for verification details.

## Maintainers

- Kin Lane — kin@apievangelist.com
