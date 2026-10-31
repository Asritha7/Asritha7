# Asritha Nibhanupudi

**Software Engineer @ Goldman Sachs** · Java backend engineering · Distributed systems · Cloud & platform reliability

I build software with a focus on **correctness under concurrency, security boundaries, and operational reliability**. My public projects explore durable job processing, evidence-aware retrieval, identity and authorization, and reproducible engineering experiments.

[**Portfolio**](https://asritha.dev) · [**Engineering case studies**](https://asritha.dev/work) · [**LinkedIn**](https://www.linkedin.com/in/asritha-nibhanupudi) · [**Email**](mailto:nibhanupudiasritha@gmail.com)

## Featured projects

### [Runreviq — Operational evidence workspace](https://github.com/Asritha7/runreviq)

**Java / Spring Boot · PostgreSQL · Row-level security · OIDC · Retrieval evaluation**

An in-progress, access-controlled workspace for finding the *applicable* operational runbook for a specific service, version, environment and incident context—without treating every matching document as reliable guidance.

- **Evidence governance:** Private Markdown drafts, independent review, controlled publication, immutable revisions and withdrawal.
- **Trust boundaries:** Google OIDC or local demo identities, restricted PostgreSQL roles and row-level security, source-integrity checks and exact cited passages.
- **Retrieval and evaluation:** Applicability-aware filtering, structured conflict checks, lexical ranking and repeatable comparison against synthetic and externally supplied incident questions.
- **Migration discipline:** A staged Python-to-Java backend migration, cross-language parity checks and an isolated Java browser/rollback rehearsal.

**Current boundary:** This is a local prototype. Retrieval still has documented misses on fresh incident scenarios; automatic prose contradiction discovery and LLM-generated answers are **not implemented**. Java runtime cutover and independent quality acceptance remain ongoing.

[Explore the source, architecture and experiments](https://github.com/Asritha7/runreviq)

### [Job Intake Service — Durable, idempotent job processing](https://github.com/Asritha7/job-intake-service)

**Java 21+ · PostgreSQL · JDBC · HTTP APIs · Concurrency**

A standalone Java service demonstrating how to **accept work durably, handle ambiguous retries, and execute jobs safely across process restarts**.

- **Atomic idempotency:** Duplicate requests reuse the original job ID; conflicting key reuse returns an explicit HTTP 409.
- **Durability and capacity:** PostgreSQL transactions and unique constraints preserve accepted work, with bounded intake capacity and checksum-verified SQL migrations.
- **Worker reliability:** Lease-based claims, retry scheduling, stale-owner protection and concurrent workers; the demo task computes a payload SHA-256 hash.
- **Operational behavior:** Readiness and process-local metrics, bounded HTTP resources, graceful shutdown, and database-backed concurrency and restart tests.

**Current boundary:** A local reference implementation—not a production job platform. It does not provide authentication, tenant isolation, TLS or exactly-once execution.

[Explore the API, worker design and tests](https://github.com/Asritha7/job-intake-service)

## More work

| Repository | Focus |
| --- | --- |
| [Engineering portfolio](https://github.com/Asritha7/asritha-portfolio) | Public code behind [asritha.dev](https://asritha.dev), built with React, TanStack Start and Cloudflare Workers |
| [SONAR rock vs. mine classification](https://github.com/Asritha7/SONAR-RockVsMine-Prediction-ML-Python) | Earlier Python machine-learning exercise |
| [YouTube comment analysis](https://github.com/Asritha7/YouTube-Comment-Analysis-Python) | Earlier API and sentiment-analysis exercise |

## Areas I'm exploring

**Backend:** Java, Spring Boot, HTTP APIs, PostgreSQL, concurrency and transactional consistency  
**Platform:** AWS, Docker, Kubernetes, CI/CD, observability and reliability  
**AI systems:** Evidence retrieval, evaluation methodology, human-reviewed knowledge and grounded generation

## Research

Co-authored an [IEEE ICMACC 2024 publication on RFID- and PIN-based access control](https://ieeexplore.ieee.org/document/10893942).

---

*These are personal projects and learning work; no employer source code or internal data is published. For professional experience, see my [sanitized case studies](https://asritha.dev/work).*
