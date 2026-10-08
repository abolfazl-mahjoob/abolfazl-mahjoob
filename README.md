# Abolfazl Mahjoob

**Product-minded software engineer · Full-stack development · System architecture**

I build digital products end to end—from defining the problem and shaping the user experience to designing APIs, implementing systems, and preparing them for real-world use.

My work spans education technology, trading and business platforms, and developer-oriented web products. I care about clear domain boundaries, maintainable code, pragmatic architecture, and reliable delivery.

[Selected work](#selected-work) · [Engineering approach](#how-i-work) · [Mimyar](https://mimyar.site)

---

## Selected work

| Product | What I worked on | Engineering case study |
| --- | --- | --- |
| **[Amoozyar](https://amoozyar.site)** | Education platform with multi-surface course delivery, secure playback, live sessions, and administration | [Architecture & decisions](case-studies/amoozyar.md) |
| **[Zarnoush](https://zarnoushgold.ir)** | Digital gold and agency-oriented business platform; pricing workflows, domain modeling, backend architecture | [Architecture & decisions](case-studies/zarnoush.md) |
| **[Mimyar](https://mimyar.site)** | Digital product studio and tools platform; product UX, full-stack development, platform foundations | [Architecture & decisions](case-studies/mimyar.md) |

These are product and architecture case studies—not public mirrors of proprietary repositories. Each write-up explains the problem, my engineering focus, a simplified system view, and the trade-offs behind important decisions.

## Open-source engineering

**[Persian Retrieval Core](https://github.com/abolfazl-mahjoob/persian-retrieval-core)** — a standalone, MIT-licensed Python package adapted from real Persian-language retrieval work: text normalization, heading-aware chunking, BM25, reciprocal-rank fusion, and evaluation helpers. Includes automated tests, multi-version CI and Docker verification.

[Read the code →](https://github.com/abolfazl-mahjoob/persian-retrieval-core) · [Quality gate →](https://github.com/abolfazl-mahjoob/persian-retrieval-core/actions/workflows/ci.yml)

**[Reliable Webhook Inbox](https://github.com/abolfazl-mahjoob/reliable-webhook-inbox)** — a NestJS + PostgreSQL reference implementation adapted from Amoozyar's webhook reliability work. Covers raw-body HMAC, tenant-aware deduplication, durable inbox claims, transactional local effects, crash recovery, retries, dead-letter handling and concurrency tests against real PostgreSQL.

[Review the code →](https://github.com/abolfazl-mahjoob/reliable-webhook-inbox) · [Verified CI →](https://github.com/abolfazl-mahjoob/reliable-webhook-inbox/actions/workflows/ci.yml)

## What I work with

| Area | Technologies |
| --- | --- |
| **Backend & APIs** | Go, TypeScript, Node.js, NestJS |
| **Frontend** | React, Next.js, TypeScript |
| **Cross-platform** | Flutter |
| **Data & asynchronous work** | PostgreSQL, Redis, Prisma, queues and workers |
| **Infrastructure & operations** | Docker, Nginx, object storage, CI, deployment workflows |
| **Product delivery** | System design, product discovery, UX, technical planning, quality assurance |

I choose technologies based on constraints and product needs—not loyalty to a particular stack.

## How I work

**Start with the product problem.** Understand user needs, operational constraints, and the smallest meaningful delivery before selecting implementation details.

**Keep architecture proportional.** Prefer clear interfaces, explicit ownership, and deployable simplicity over premature complexity.

**Treat reliability as part of the product.** Tests, CI checks, migrations, access control, documentation, and deployment impact are part of engineering—not afterthoughts.

**Think across disciplines.** Product decisions affect data models, UX affects API design, and infrastructure choices affect what the business can sustainably ship.

## Source code and collaboration

Much of my recent work is commercial or actively developed, so the underlying repositories are private. Public case studies describe selected architecture and decisions without exposing client code, credentials, or confidential business details.

For collaboration or a technical walkthrough, you can reach me through [GitHub](https://github.com/abolfazl-mahjoob) or [Mimyar](https://mimyar.site).
