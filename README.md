<!-- Banner -->
<div align="center">
  <img src="./banner.jpg" width="100%" alt="Ariel Jaime - Senior Backend Engineer & Distributed AI Systems Architect" />
  
  <h1>Ariel Jaime</h1>
  <p><strong>Senior Backend Engineer & Distributed AI Systems Architect</strong></p>
  <p><i>Building resilient distributed primitives & autonomous multi-agent systems with zero-compromise correctness.</i></p>

  <p>
    <a href="https://linkedin.com/in/ariel-jaime/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://nedder3.github.io"><img src="https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
    <a href="mailto:arij.dev@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
    <img src="https://img.shields.io/badge/English-EF%20SET%20C2%20Proficient-0052CC?style=for-the-badge" alt="English C2" />
  </p>

  <p>
    <img src="https://img.shields.io/badge/Java-21%20LTS-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 21" />
    <img src="https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
    <img src="https://img.shields.io/badge/AI_Systems-Multi--Agent%20Orchestration-8A2BE2?style=for-the-badge" alt="Agentic AI" />
    <img src="https://img.shields.io/badge/Architecture-Distributed%20Systems-4B32C3?style=for-the-badge" alt="Distributed Systems" />
    <img src="https://img.shields.io/badge/Concurrency-Lock--Free%20%2F%20Virtual%20Threads-008080?style=for-the-badge" alt="Concurrency" />
    <img src="https://img.shields.io/badge/Commits-Conventional%20Commits-FE5196?style=for-the-badge" alt="Conventional Commits" />
  </p>
</div>

---

### Executive Profile

Senior Backend Engineer with **10 years in IT and 6+ years specializing in Java enterprise ecosystems, high-concurrency architectures, and distributed primitives**. Pioneer in bridging mission-critical backend engineering with **autonomous multi-agent AI orchestration, knowledge graphs, and deterministic LLM pipelines**.

Currently serving as **Squad Senior / Tech Lead & Mentor at Teamcubation**, leading technical squads and training developers (including senior engineers with 15+ years of industry experience) across modern software architecture, Java 21, microservices, and enterprise AI workflows.

- **Distributed Systems & Concurrency:** Hexagonal architecture, CQRS / Event Sourcing, Vector Clocks, Write-Ahead Logs (WAL), CAS lock-free data structures, and Java 21 Virtual Threads.
- **Autonomous AI & Agentic Engineering:** Architected local 8-agent autonomous swarms with strict Single Responsibility Principles (SRP), automated Red/Green TDD quality gates, knowledge graphs with 33,000+ nodes, and deterministic arithmetic extraction pipelines.
- **Enterprise Track Record:** Engineered microservices and led technical acceleration programs for tier-1 enterprises (Sancor Salud, MercadoLibre training programs, Banco Santander, Globant).
- **Technical Leadership:** Mentored 100+ engineers, authoring production-grade curricula covering Clean Architecture, Concurrency, Virtual Threads, Copilot Studio, Claude, and Local LLMs (Ollama).

---

### Core Competencies & Tech Stack

```
Backend & Runtimes     : Java 21 LTS (Virtual Threads, Records, Sealed Types), Python 3.12, TypeScript, SQL
Frameworks & Core      : Spring Boot 3, Spring Security (OAuth2/JWT/OIDC), JPA/Hibernate, .NET Core
AI & Agentic Systems   : Multi-Agent Swarm Orchestration, Knowledge Graph RAG (33k+ nodes), Local LLMs (Ollama)
                         Deterministic Anti-Hallucination Pipelines, Copilot Studio, Claude, Prompt Engineering
Distributed Systems    : Vector Clocks, W-TinyLFU, WAL + CRC32, CQRS/ES, Outbox Pattern, Event-Driven Design
Messaging & Storage    : Apache Kafka, Redis, PostgreSQL, SQLite, MongoDB
Infra, Cloud & DevOps  : Docker, AWS (S3, IAM, Lambda, EC2), GitHub Actions, CI/CD, Linux CLI
Engineering Rigor      : TDD (JUnit 5, Mockito, AssertJ), Clean Architecture, Domain-Driven Design (DDD)
```

---

### Flagship Architectural & AI Engineering Projects

#### 1. [distributed-cache-engine](https://github.com/nedder3/distributed-cache-engine)
*Distributed, fault-tolerant in-memory key-value cache engine built from scratch with Java 21.*
- **Architecture:** Ports & Adapters (Hexagonal Architecture) with explicit CQRS/ES write/read path separation.
- **Consistency & Recovery:** Vector Clocks for causality tracking and conflict resolution; append-only Write-Ahead Log (WAL) with CRC32 checksums and asynchronous checkpointing.
- **Eviction & Storage:** High-throughput eviction engine pairing W-TinyLFU with Count-Min Sketch frequency estimation for optimal hit rates under dynamic workloads.
- **Concurrency & Rigor:** Built with Java 21 Virtual Threads and thread-safe lock striping. Tested with **359 comprehensive automated unit and integration tests** ensuring zero concurrency races.

#### 2. Multi-Agent Autonomous Swarm Architecture (Hermes Core)
*Enterprise autonomous multi-agent orchestration engine featuring specialized roles and TDD gates.*
- **Specialized Swarm Roles:** 8 distinct agent personas (Orchestrator, TDD Red-Tester, Backend Implementer, Visual/Tokens Designer, Security/A11y Gate Auditor, DevOps/Deployer, Knowledge Curator) governed by strict Single Responsibility (SRP).
- **Quality Gates:** Implements mandatory Red-TDD phase before code generation, with blind automated verification gates prior to deployment.
- **Inference Resilience:** Designed serial scheduling algorithms preventing VRAM thrashing on local models (Ollama) and eliminating upstream HTTP 503 concurrency errors.
- **Guiding Principle:** *"Verify, don't trust self-reports"* — all agent actions are deterministically verified via CLI execution (git, tests, builds).

#### 3. [java-event-bus](https://github.com/nedder3/java-event-bus)
*High-throughput, asynchronous in-memory event bus designed for modular monoliths.*
- **Non-Blocking Core:** Atomic CAS operations and non-blocking queues (`ConcurrentLinkedQueue`) eliminating synchronization bottlenecks on high-frequency hot paths.
- **Bounded Backpressure:** Configurable backpressure strategies (`REJECT` via exceptions or `DROP` with drop-rate observability metrics).
- **Dispatch Strategies:** Configurable fan-out multicasting or round-robin consumer balancing with `CompletableFuture` coordination.
- **Quality Assurance:** **42 multi-threaded concurrency stress tests** validating zero event loss and strict deterministic delivery.

#### 4. Deterministic ROI Analysis Engine (Teamcu Hackathon)
*Production API estimating automation time/cost savings with mathematical certainty.*
- **Anti-Hallucination Design:** Segregates LLM capabilities to strict schema extraction, running all arithmetic in deterministic Python logic.
- **Textual Evidence Links:** Every quantitative claim is traceable back to an immutable file location, speaker timestamp, and verbatim transcript citation.
- **Dynamic Rates:** Integrated with official Argentine Central Bank (BCRA) and RIPTE wage series APIs with stale-cache fallback.

#### 5. [tq-labs](https://github.com/nedder3/tq-labs)
*Developer technical platform & internal learning management engine.*
- Full-stack SSR architecture utilizing Astro, Supabase (PKCE auth, Row-Level Security), and Vercel edge deployment.
- Features dynamic markdown labs, progress tracking, and **174 automated Vitest tests** covering auth, database isolation, and rendering pipelines.

---

### Professional Trajectory Snapshot

| Period | Role | Organization & Scope |
|---|---|---|
| **08/2025 – Present** | **Squad Senior / Tech Lead & Mentor** | **Teamcubation** — Technical mentoring for devs and senior engineers (15+ yrs); curriculum design across Java 21, Spring Boot, Microservices, and Agentic AI workflows. |
| **01/2024 – 06/2024** | **Programming Mentor** | **Alkemy** — Led technical mentorship for the **MercadoLibre** Java Spring Boot bootcamp; oversaw comprehensive production-ready capstone architectures. |
| **11/2023 – 01/2024** | **Backend Developer** | **Right Partner** — Engineered mission-critical REST microservices in Java Spring Boot for **Sancor Salud** healthcare domain. |
| **01/2021 – 11/2022** | **Backend Teacher & Lead** | **Digital House** — Delivered intensive backend engineering training for top accounts (**MercadoLibre, Banco Santander, Globant, Sabre, Xpertal**). |
| **01/2020 – 01/2021** | **Application Developer** | **Bernardo Lew** — Core Java, Spring Boot, MySQL/PostgreSQL/MongoDB development for enterprise management systems and lab routing equipment. |
| **08/2015 – 01/2020** | **Software Developer** | **Freelance** — Desktop and web client solutions with C#, .NET, MySQL, and full-stack web platforms. |

---

### GitHub Activity & Metrics

<div align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=nedder3&show_icons=true&theme=tokyonight&hide_border=true&cache_seconds=86400" alt="GitHub Stats" height="165px" />
  &nbsp;&nbsp;
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=nedder3&layout=compact&theme=tokyonight&hide_border=true&cache_seconds=86400" alt="Top Languages" height="165px" />
</div>

<br/>

<div align="center">
  <p>📍 Bahía Blanca, Buenos Aires, Argentina &nbsp;|&nbsp; 🌐 Open to Worldwide Remote Opportunities (USD)</p>
  <p><small>Engineered with rigor, verifiable distributed systems principles, and production AI orchestration.</small></p>
</div>
