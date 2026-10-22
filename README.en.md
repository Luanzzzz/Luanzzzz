[🇧🇷 Português](README.md) | 🇺🇸 English

# Luan Valentino

**Backend Developer | Python • Go | FastAPI • Django | AI & Automation**

Brazilian back-end developer focused on REST APIs, relational data modeling, business-rule logic and integrations between systems. **Python is my main language.** I am studying and applying **Go** for concurrent services, and moving into **AI engineering** (LLM integrations) and **automation**.

Software Development student (Multiplatform Software Development) at **FATEC Atibaia**, with a prior technical diploma in Systems Development from **ETEC**. I am looking for an **internship or junior back-end role**, remote preferred.

[GitHub](https://github.com/Luanzzzz) · [LinkedIn](https://www.linkedin.com/in/luan-valentino-dos-santos-a2059928b/)

---

## How to read project status

| Status | Meaning |
| --- | --- |
| **Evolving product** | Commercial system under active development, private source code |
| **In development** | Under construction, not yet released to the public |
| **MVP** | Minimum scope complete and tested, no public deployment |
| **Study** | Learning project, course work or prototype |
| **Online** | Personal project available publicly |

Among the public projects below, only DEV QUEST is online. The back-end projects run locally and have no deployment.

---

## Commercial experience

Commercial systems I worked on. The source code is **private** (`Private Source Code`), so I only describe what can be shared publicly.

| Project | What it is | My contribution | Confirmed stack | Status |
| --- | --- | --- | --- | --- |
| **Hi Control** | Management SaaS for the Brazilian market: scheduling, client records, billing and NF-e (electronic invoice) workflows. [Product site](https://site-hi-control.vercel.app) | A significant share of the application development and business logic, in the front end and the API | FastAPI, PostgreSQL (Supabase), Pydantic v2, JWT · React, TypeScript, Vite, Tailwind · Playwright, Vitest | Evolving product |
| **Lua Lua / Lua Baby** | E-commerce for children's clothing: catalog, stock, checkout, shipping quotes and an admin panel | Web development, back-end services and commercial integrations | Django, Next.js, PostgreSQL, Redis, Docker Compose, pytest | In development. Mercado Pago integration implemented but disabled until homologation. No public URL |
| **Lead Bot** | Windows desktop application built around browser automation | Application development | Installer bundles Chromium and Firefox | Pre-release 0.5.0 (installer not digitally signed). [Downloads](https://github.com/Luanzzzz/lead-bot-downloads) |

---

## Featured public projects

| Project | Focus | What it shows | Status |
| --- | --- | --- | --- |
| [**LeadFlow**](https://github.com/Luanzzzz/LeadFlow) | Python · FastAPI | Lead and follow-up management. Derived business rules (overdue and pending states computed from dates and status). SQLModel, SQLite, React. 4 tests | MVP |
| [**InboxFlow**](https://github.com/Luanzzzz/InboxFlow) | Python · Django | Demand triage with category and urgency classification and heuristic suggestions. `ai/` layer prepared for an LLM. 20 tests | MVP |
| [**OpsCore**](https://github.com/Luanzzzz/OpsCore) | TypeScript · AI | Inbox triage with **OpenAI** (Responses API, strict JSON Schema, Zod validation) and a rule-based fallback. Next.js 15. 58 tests | MVP |
| [**graceful-api**](https://github.com/Luanzzzz/graceful-api) | Go · PostgreSQL | Job queue with concurrent workers (goroutines), `FOR UPDATE SKIP LOCKED`, leases, retries with exponential backoff, idempotency and graceful shutdown | Study |
| [**Gym-Tracker**](https://github.com/Luanzzzz/Gym-Tracker) | Python · Django | CRUD, authentication, custom user model and an N:N relationship with an intermediate model. 33 tests. Mate Academy project | Study |
| [**DEV QUEST**](https://github.com/Luanzzzz/DEV-QUEST) | JavaScript | Portfolio built as a 2D game, no engine. [Live demo](https://devquest-khaki.vercel.app) | Online |

### Caveats

- **graceful-api:** job processing is simulated (a 3-second wait), there are no automated tests and **there is no public deployment**.
- **OpsCore:** current persistence uses local file storage. The Drizzle/PostgreSQL layer is defined but not wired yet.
- **InboxFlow:** no LLM is called today. Suggestions are rule-based.
- **AI:** OpsCore is the only public project with a real LLM integration. A RAG pipeline and LangChain agents are not in a public repository yet.

---

## Tech Stack

| Level | Technologies |
| --- | --- |
| **Applied in the projects above** | Python, TypeScript, JavaScript, SQL · FastAPI, Django, Pydantic, SQLModel, JWT · PostgreSQL, SQLite · React, Next.js, Tailwind CSS · OpenAI API · pytest, Vitest, Playwright · Docker Compose, Git, GitHub |
| **Learning and applying** | Go (concurrency, `context`, database-backed queues) |
| **Working knowledge** | MySQL, MongoDB, n8n, Linux, Java (academic) |
| **In study** | LangChain, RAG, AI agents |

---

## In progress

- **graceful-api:** Go job queue, early stage.
- **[Nexus AI Workspace](https://github.com/Luanzzzz/Nexus-AI-Workspace):** monorepo structure only (FastAPI, PostgreSQL, pgvector planned). No feature implemented yet.
- **Hi Control, Lua Lua / Lua Baby and Lead Bot:** ongoing development (private).

---

## Contact

[LinkedIn](https://www.linkedin.com/in/luan-valentino-dos-santos-a2059928b/) · [GitHub](https://github.com/Luanzzzz)

---

[🇧🇷 Português](README.md) | 🇺🇸 English
