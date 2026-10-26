# lastminute.com

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

lastminute.com N.V. (SIX Swiss Exchange: LMN) is a European travel-tech group and the
regional leader in dynamic holiday packages, operating an online travel agency portfolio
that includes lastminute.com, Volagratis, Rumbo, Bravofly, Weg.de, Jetcost and Hotelscan
alongside the Forward media/advertising business.

## API surface

lastminute.com runs a real partner-facing API portal at
[developers.lastminute.com](https://developers.lastminute.com/) — a Stoplight workspace
branded "lmn API Portal" (`lmnuserexperience`, created 2023-08, last updated 2025-07).
The portal is publicly reachable, but **no project in the workspace is anonymously
readable**: the workspace has no public projects, and `/docs` returns 404. API reference
content therefore sits behind a sign-in and is a partner/private surface, not a
self-service developer program.

As of 2026-07-19 the enrichment pipeline found **no** publicly retrievable OpenAPI,
AsyncAPI or GraphQL description, no first-party SDK on any public package registry,
no CLI, no MCP server, no public Postman collection, no status page, no changelog, no
API pricing or sign-up path, no `/.well-known/` document of any kind (including
security.txt), no vulnerability disclosure program and no trust center.

The public [GitHub organization](https://github.com/lastminutedotcom) has 10 repositories,
all engineering samples and internal tooling — no client libraries.

The [technology blog](https://technology.lastminute.com/) is active and substantive,
including the "Our Tech Ecosystem" series covering architecture, Kafka and DDD, the
Java/Kotlin/Spring Boot and React/TypeScript/Next.js stack, Kubernetes DevOps and
observability, and data/ML.

## Artifacts

- `security/lastminute-com-domain-security.yml` — TLS/HSTS/DNS probe across four hosts
  (SPF and DMARC `p=reject` present; no DNSSEC, no CAA)
- `well-known/lastminute-com-well-known.yml` — negative `/.well-known/` probe record
- `llms/lastminute-com-llms.txt` — generated catalog summary

Backed by: northzone — https://www.lastminute.com
