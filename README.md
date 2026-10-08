# Hi there, I'm Mateo Pavoni!

### About Me
I am a **Full Stack Developer** with a practical mindset and a passion for building scalable solutions that solve real-world problems. I specialize in modern web ecosystems and business automation, focusing on creating efficient and maintainable products.

- **Currently:** Junior Full Stack Developer at **AR IT Services**.
- **Education:** Studying **Information Systems Engineering** at UTN-FRC and **Software Development** at Inst. Brochero (100% Merit-based Scholarship). Full Stack Developer Career at **Coderhouse**
---

### Technical Stack
| Category | Tools & Technologies |
| :--- | :--- |
| **Frontend** | Next.js, React, TypeScript, SvelteKit, Tailwind CSS, Sass, Bootstrap 5 |
| **Backend & DB** | Node.js, Python (FastAPI), Go, .NET Core, PHP, Supabase (PostgreSQL), SQL Server, MySQL, MongoDB, Redis |
| **Infrastructure** | Docker, Dokku, Coolify, VPS Management, Cloudflare, Linux |
| **Automation & AI** | n8n (Self-hosted), WhatsApp/Meta API, Claude Code (MCP/Hooks), Google Cloud APIs |
| **Quality & QA** | Playwright (E2E Testing), Lighthouse (Performance/SEO) |

---

### Featured Project: ChronoFlow
**Event-driven workflow engine on directed acyclic graphs (DAGs).**
- **The Stack:** Python, FastAPI, PostgreSQL, asyncio, React, TypeScript, React Flow.
- **The Solution:** Async parallel DAG execution, JSONPath expressions for dynamic payloads, and Time-Travel Debugging via event-sourcing (replay the historical state of any run, node by node).
- **Extras:** Visual graph editor built with React Flow.

### Featured Project: TuTienda
**Multi-store ecommerce builder, SaaS-style (à la Shopify / Tienda Nube).**
- **The Stack:** Go, MongoDB, Redis, SvelteKit, TypeScript, Docker, microservices.
- **The Solution:** Never oversell stock under concurrent load, isolated per store — atomic MongoDB operations and time-boxed cart holds with Redis, in a multi-tenant Go microservices architecture.
- **Extras:** SvelteKit frontend covering marketing, storefront per store, and merchant dashboard.

### Featured Project: ClubCore
**REST API for membership management at a health/sports club.**
- **The Stack:** Java 21, Spring Boot 3.3, MySQL 8, Flyway, MapStruct, Resilience4j, Bucket4j, Docker, GitHub Actions.
- **The Solution:** On-demand membership state engine (no caching). Real concurrency control: an initial @Transactional + SELECT FOR UPDATE attempt failed under load (commit happens after method return) — fixed with a per-client JVM lock + TransactionTemplate, verified with a 10-parallel-request test against a quota of 1.
- **Extras:** 27 tests (H2 for unit/controller, Testcontainers for integration), retry + circuit breaker on outgoing webhooks, rate limiting, and plan-catalog caching. Deployed to production via Dokku with CI/CD.

### Featured Project: Chaos Playground
**Chaos Engineering playground with real OTP processes, not simulations.**
- **The Stack:** Elixir, Phoenix LiveView, PostgreSQL, Tailwind, Docker.
- **The Solution:** Every infrastructure node on the canvas (load balancer, API, DB, cache, queue) is a real GenServer under a DynamicSupervisor — "killing" a node runs an actual `Process.exit(pid, :kill)`. Deliberate `:temporary` restart strategy to show real "let it crash" behavior, no auto-heal masking the failure.
- **Extras:** Live metrics dashboard (RPS, p99, error rate), automatic Chaos Monkey, and a centralized traffic simulator generating concurrent load. 101 tests running in CI/CD on every push to main.

---

### Let's Connect!
- **Email:** mateopavoni6@gmail.com
- **LinkedIn:** [mateopavonidev](https://www.linkedin.com/in/mateopavonidev/)
- **GitHub:** [mateopavoni](https://github.com/mateopavoni)
