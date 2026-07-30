# lastminute.com

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
