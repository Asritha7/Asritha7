# Asritha Nibhanupudi

**Software Engineer @ Goldman Sachs** · Java backend · Distributed systems · Platform reliability

I enjoy building systems where correctness matters: **durable state, safe concurrency, authorization boundaries, and recovery when things go wrong**. I document the design trade-offs and failure cases—not just the happy path.

**[🌐 Explore my live portfolio](https://asritha.dev)** · [Engineering case studies](https://asritha.dev/work) · [Technical notes](https://asritha.dev/notes) · [LinkedIn](https://www.linkedin.com/in/asritha-nibhanupudi) · [Email](mailto:nibhanupudiasritha@gmail.com)

## Featured engineering work

### 🌐 [Engineering Portfolio — asritha.dev](https://asritha.dev)

**React 19 · TanStack Start · TypeScript · Tailwind CSS · Cloudflare Workers**

My live professional home, with **engineering case studies, technical notes, research, and project walkthroughs**. Built with server-side rendering, accessible navigation, responsive design, route-level SEO, and a three-mode theme system.

**[Visit the website](https://asritha.dev)** · [Read case studies](https://asritha.dev/work) · [Browse the public source](https://github.com/Asritha7/asritha-portfolio)

### 🛡️ [Runreviq — Governed operational evidence retrieval](https://github.com/Asritha7/runreviq)

**Python / FastAPI · Java / Spring Boot migration · PostgreSQL RLS · OIDC · Evaluation**

An access-controlled prototype for locating **applicable and authorized runbook evidence** by service, environment, version, and incident context.

- Governed document drafts, independent review, publication, immutable revisions, and withdrawal.
- Role-restricted PostgreSQL evidence reads, source-integrity checks, and exact cited passages.
- Deterministic retrieval and repeatable relevance evaluations, including failure analysis against external scenarios.

*Status: local prototype; Python remains the working runtime while Java cutover is in progress. Retrieval quality has known limitations. No LLM-generated answers or semantic contradiction detection.*

**[Architecture, implementation, and evaluation](https://github.com/Asritha7/runreviq)**

### ⚙️ [Job Intake Service — Durable asynchronous job processing](https://github.com/Asritha7/job-intake-service)

**Java 21 · PostgreSQL · JDBC · HikariCP (opt-in) · HTTP · Concurrency**

A Java backend reference that explores **idempotent acceptance, safe retries, concurrent workers, and crash recovery**.

- Transactional admission with database-enforced key uniqueness and shared capacity across API instances.
- Worker leases, attempt limits, stale-owner fencing, and durable results for a deterministic SHA-256 job.
- Bounded HTTP resources, liveness/readiness, metrics, checksum-verified migrations, and graceful shutdown.
- Optional bounded connection pooling, with CI experiments covering contention, backend recovery, and independent-JVM correctness.

*Status: local reference implementation; pooling is disabled by default. No authentication, tenant isolation, TLS, or exactly-once external execution guarantee.*

**[Explore architecture, API, and verified experiments](https://github.com/Asritha7/job-intake-service)**

## What I work with

**Backend & data:** Java, Spring Boot, PostgreSQL, JDBC, transactional consistency, concurrency  
**Cloud & platform:** Docker, Kubernetes, AWS, CI/CD, observability, reliability engineering  
**Evidence & AI systems:** Retrieval evaluation, access control, reviewed knowledge workflows

## Research & earlier projects

Co-authored an [IEEE ICMACC 2024 paper on RFID- and PIN-based access control](https://ieeexplore.ieee.org/document/10893942). Earlier exploration includes [SONAR classification](https://github.com/Asritha7/SONAR-RockVsMine-Prediction-ML-Python) and [YouTube comment analysis](https://github.com/Asritha7/YouTube-Comment-Analysis-Python).

---

*These repositories are personal learning and engineering projects, not employer source code. Professional case studies are published in a [sanitized public format](https://asritha.dev/work).*
