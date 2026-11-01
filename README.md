# University of Lisbon

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

The University of Lisbon (Universidade de Lisboa, ULisboa) is Portugal's largest public university — 18 schools plus the National Museum of Natural History and Science — and it is a federation of buyers rather than a producer of APIs. It runs no central developer portal, publishes no OpenAPI of its own, and has no open data portal: data.ulisboa.pt and dados.ulisboa.pt do not resolve, and the institution has no organization on the national portal dados.gov.pt. What it does operate, on its own infrastructure, is a small but real set of standards-based surfaces: the FenixEdu academic API at Instituto Superior Tecnico — institution-authored open-source software serving degrees, courses, campus spaces, blueprints, parking and a 1.2 MB serialized domain model anonymously, with Bennu OAuth 2.0 in front of person-scoped data; two independent OAI-PMH 2.0 endpoints, one over a 100,245-item DSpace 7.6.1 repository running since 2002 and one over the Koha union library catalog; and a SAML 2.0 identity provider published into the national RCTSaai federation and onward to eduGAIN, alongside a second IdP for Instituto Superior Tecnico that asserts SIRTFI. The institution also authors an open-source Erasmus Without Paper node on GitHub, which is its most substantive piece of public API engineering. Everything else is someone else's contract running under its name — most importantly researchportal.ulisboa.pt, which looks institutional and CNAMEs to ulisbon.elsevierpure.com; its own OAI-PMH Identify calls it a "Pure OAI Repository" and its Pure Web Service OpenAPI is behind an API key. Its Erasmus Without Paper node is hosted by another university entirely. Both are recorded here as tenancies, with the vendor contract deliberately left out of this repository.

**Areas:** University · Higher Education · Education · Portugal · Europe · Public Research University · Course Catalog · Research Repository · Library · Identity Federation · OAI-PMH · Open Access

## University of Lisbon on APIs.io

Everything profiled for University of Lisbon is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-lisbon/](https://apis.io/providers/university-of-lisbon/)** — or go straight to one of the APIs or properties below.

### APIs (17)

- [Repositorio da Universidade de Lisboa — OAI-PMH](https://apis.io/apis/university-of-lisbon/repositorio-oai-pmh/) — OAI-PMH 2.0 metadata harvesting interface over the DSpace 7.6.1 institutional open-access repository. Operating since November 2002; 100,245 items; twelve…
- [Repositorio da Universidade de Lisboa — DSpace REST API](https://apis.io/apis/university-of-lisbon/repositorio-dspace-rest/) — Anonymous HAL+JSON REST API of the institution's DSpace 7.6.1 repository — communities, collections, items, bitstreams, discovery search, metadata schemas…
- [Catalogo Coletivo ULisboa (Koha) — OAI-PMH](https://apis.io/apis/university-of-lisbon/catalogo-bibliotecas-oai-pmh/) — OAI-PMH 2.0 interface over the union library catalog of the 18 schools, the National Museum of Natural History and Science and the Tropical Scientific…
- [Universidade de Lisboa SAML 2.0 Identity Provider (RCTSaai / eduGAIN)](https://apis.io/apis/university-of-lisbon/identity-federation-ulisboa/) — The institution's central SAML 2.0 identity provider, published into the Portuguese national identity federation RCTSaai (operated by FCCN) and onward to…
- [Instituto Superior Tecnico SAML 2.0 Identity Provider (RCTSaai / eduGAIN)](https://apis.io/apis/university-of-lisbon/identity-federation-tecnico/) — The identity provider for Instituto Superior Tecnico, federated through RCTSaai into eduGAIN and asserting SIRTFI incident-response assurance — a stronger…
- [ULisboa Research Portal — Elsevier Pure tenancy](https://apis.io/apis/university-of-lisbon/researchportal-pure/) — The institution's current research information system, an Elsevier Pure tenant (tenant id "ulisbon") presented on a ulisboa.pt hostname. The relationship is…
- [Erasmus Without Paper node (HEI ulisboa.pt)](https://apis.io/apis/university-of-lisbon/ewp-node/) — The institution's node in the Erasmus Without Paper network, through which student mobility, inter-institutional agreements, learning agreements and…
- [DataCite repository membership (QWBT.ULISBOA)](https://apis.io/apis/university-of-lisbon/datacite-membership/) — An active DataCite repository client registered to the university's central services for minting DOIs over the institutional repository. Recorded honestly…
- [ROR organization identifier](https://apis.io/apis/university-of-lisbon/ror-registration/) — The institution's registered ROR identifier — the canonical machine-readable organizational identity used across DataCite, Crossref and OpenAIRE metadata.…
- [Crossref memberships (organic units)](https://apis.io/apis/university-of-lisbon/crossref-membership/) — Five ULisboa organic units hold Crossref member IDs in their own right, minting DOIs for their journals independently of the rectorate. There is no single…
- [University of Lisbon Campus Life API](https://apis.io/apis/university-of-lisbon/university-of-lisbon-campus-life-api/) — Parking, canteen and shuttle information.
- [University of Lisbon Courses API](https://apis.io/apis/university-of-lisbon/university-of-lisbon-courses-api/) — Individual course units, their schedules, groups, evaluations and students.
- [University of Lisbon Degrees API](https://apis.io/apis/university-of-lisbon/university-of-lisbon-degrees-api/) — Degree catalog and the courses that belong to a degree.
- [University of Lisbon Domain Model API](https://apis.io/apis/university-of-lisbon/university-of-lisbon-domain-model-api/) — Serialized FenixEdu domain model.
- [University of Lisbon Institution API](https://apis.io/apis/university-of-lisbon/university-of-lisbon-institution-api/) — Institution-level metadata, contacts and academic calendar.
- [University of Lisbon Person API](https://apis.io/apis/university-of-lisbon/university-of-lisbon-person-api/) — Authenticated person-scoped academic data. Requires an OAuth 2.0 token.
- [University of Lisbon Spaces API](https://apis.io/apis/university-of-lisbon/university-of-lisbon-spaces-api/) — Campuses, buildings, floors and rooms, including blueprints.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (3)

The data models the API reads and writes.

- [FenixEdu About](https://apis.io/schemas/university-of-lisbon/university-of-lisbon-fenixedu-about/)
- [FenixEdu Degree](https://apis.io/schemas/university-of-lisbon/university-of-lisbon-fenixedu-degree/)
- [FenixEdu Space](https://apis.io/schemas/university-of-lisbon/university-of-lisbon-fenixedu-space/)

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [University Of Lisbon Context](https://apis.io/jsonld/university-of-lisbon/university-of-lisbon-context/)
- [University Of Lisbon Organization Context](https://apis.io/jsonld/university-of-lisbon/university-of-lisbon-organization/)

#### Examples (9)

Example requests and responses.

- [Datacite Client Qwbt Ulisboa](https://apis.io/examples/university-of-lisbon/datacite-client-qwbt-ulisboa/)
- [Fenixedu About](https://apis.io/examples/university-of-lisbon/fenixedu-about/)
- [Fenixedu Academicterms](https://apis.io/examples/university-of-lisbon/fenixedu-academicterms/)
- [Fenixedu Degree](https://apis.io/examples/university-of-lisbon/fenixedu-degree/)
- [Fenixedu Error 401](https://apis.io/examples/university-of-lisbon/fenixedu-error-401/)
- [Fenixedu Error 404](https://apis.io/examples/university-of-lisbon/fenixedu-error-404/)
- [Fenixedu Parking](https://apis.io/examples/university-of-lisbon/fenixedu-parking/)
- [Repositorio Dspace Api Root](https://apis.io/examples/university-of-lisbon/repositorio-dspace-api-root/)
- [Repositorio Dspace Externalsources](https://apis.io/examples/university-of-lisbon/repositorio-dspace-externalsources/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [University of Lisbon API Rules](https://apis.io/rules/university-of-lisbon/university-of-lisbon-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Lisbon Authentication](https://apis.io/security/university-of-lisbon/university-of-lisbon-authentication/)
- [University Of Lisbon Domain Security](https://apis.io/security/university-of-lisbon/university-of-lisbon-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [University Of Lisbon Scopes](https://apis.io/scopes/university-of-lisbon/university-of-lisbon-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Lisbon Plans Pricing](https://apis.io/plans/university-of-lisbon/university-of-lisbon-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Lisbon Rate Limits](https://apis.io/rate-limits/university-of-lisbon/university-of-lisbon-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Lisbon Finops](https://apis.io/finops/university-of-lisbon/university-of-lisbon-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ulisboa.pt/en)
- [Documentation](https://fenixedu.org/dev/api/)
- [API reference](https://fenixedu.org/dev/api/)
- [Support](https://www.ulisboa.pt/en/info/contacts-1)
- [Terms of service](https://www.ulisboa.pt/en/info/terms-use-0)
- [Privacy policy](https://www.ulisboa.pt/en/info/cookies-policy)
- [GitHub](https://github.com/ULisboa)

## API Evangelist rating

**Kin Score 35.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 51.4 |
| Contract governance | 15.2 |
| Operational transparency | 7.9 |
| Developer ergonomics | 33.3 |
| Access clarity | 26.3 |

**Agent readiness 23.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 34.3** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-lisbon/](https://apis.io/providers/university-of-lisbon/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Lisbon: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-lisbon/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
