# University of Antwerp (university-of-antwerp)

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

The University of Antwerp (Universiteit Antwerpen) is a public research university in Antwerp, Belgium, ranked #267 in the QS World University Rankings 2025. Its public developer footprint is centered on library and scholarly infrastructure: the library's software department, Anet, builds the open-source Brocade library management system (published via the `anet-be` GitHub organization), and the Institutional Repository University of Antwerp (IRUA) exposes scholarly metadata through a standards-based OAI-PMH interface. There is no general-purpose commercial developer portal; administrative, student-information, and identity systems are gated behind institutional affiliation.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-antwerp/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-antwerp-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Library, Institutional Repository, OAI-PMH, Open Data, Belgium, Europe

## APIs

- **IRUA OAI-PMH Metadata API** — OAI-PMH 2.0 interface for the Institutional Repository University of Antwerp (IRUA). Base URL: `https://repository.uantwerpen.be/oai/abua/`. Docs: https://www.openarchives.org/OAI/openarchivesprotocol.html
- **Brocade Library Services (Anet)** — Open-source, web-based library management system developed by the University of Antwerp library since 1998, using open standards (Z39.50, MARC, OAI-PMH, EAD, EAC). Docs: https://www.uantwerpen.be/nl/projecten/anet/brocade/ — Code: https://github.com/anet-be

## Plans

- [plans/university-of-antwerp-plans-pricing.yml](plans/university-of-antwerp-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-antwerp-rate-limits.yml](rate-limits/university-of-antwerp-rate-limits.yml)

## FinOps

- [finops/university-of-antwerp-finops.yml](finops/university-of-antwerp-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uantwerpen.be/en/
- GitHub: https://github.com/anet-be
- LinkedIn: https://www.linkedin.com/school/university-of-antwerp/
- Twitter/X: https://x.com/uantwerpen
- Source Code: https://github.com/anet-be

## Notes

All endpoints in this profile were probed and verified. The IRUA OAI-PMH endpoint returns valid OAI-PMH XML; the legacy `http://anet.be/oai/abua/` path 301-redirects to the canonical `https://repository.uantwerpen.be/oai/abua/`. The `anet-be` GitHub org exists with 17 public repositories. No public self-service REST API, commercial developer portal, or documented course/timetable/SIS/identity API was found — those systems require institutional affiliation. The LinkedIn school page returns HTTP 999 (anti-bot) to automated requests but resolves in a normal browser. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
