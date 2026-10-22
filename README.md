<h1>Luan Valentino</h1>

**Backend Developer | Python • Go | FastAPI • Django | AI & Automation**

Brazilian developer focused on back-end systems: REST APIs, relational data modeling, business-rule logic and integrations between services. Python is my main language; I am studying and applying Go for concurrent back-end services, and I am expanding into AI engineering (LLM integrations) and automation.

I am a Software Development student (Multiplatform Software Development, **FATEC Atibaia**) with a prior technical diploma in Systems Development (**ETEC**). I am looking for **internship and junior back-end roles**, remote preferred.

[GitHub](https://github.com/Luanzzzz) · [LinkedIn](https://www.linkedin.com/in/luan-valentino-dos-santos-a2059928b/)

---

## Production & Commercial Projects

Commercial systems I worked on. Source code is private, so the descriptions below are intentionally non-confidential and limited to what I can show publicly.

| Project | What it is | My contribution | Confirmed stack | Status |
| --- | --- | --- | --- | --- |
| **Hi Control** <br> Enterprise Software <br> `Private Source Code` | Business-management SaaS for the Brazilian market: scheduling, client records, billing and fiscal-document (NF-e) workflows. Replaces scattered spreadsheets and chat threads with one flow. | A significant share of the application development and business logic, in both the front end and the API. | Python, FastAPI, PostgreSQL (Supabase), Pydantic v2, JWT auth · React 18, TypeScript, Vite, Tailwind · Vitest and Playwright E2E · Vercel | Active development. Public product site: [site-hi-control.vercel.app](https://site-hi-control.vercel.app) |
| **Lua Lua / Lua Baby** <br> E-commerce Platform <br> `Private Source Code` | E-commerce platform for a children's clothing business: catalog, stock, checkout, shipping quotes and an admin area. | Web development, back-end services and commercial integrations. | Django API with OpenAPI docs, Next.js, PostgreSQL, Redis, Docker Compose, pytest, Ruff | In development, run in a local integrated environment. The Mercado Pago Checkout Pro adapter (signed webhooks, reconciliation, refunds) is implemented but disabled by default until homologation. No public URL yet. |
| **Lead Bot** <br> Desktop Automation <br> `Private Source Code` | Windows desktop application built around browser automation. | Development of the application. | Installer bundles Chromium and Firefox for automation | Pre-release 0.5.0 for Windows (unsigned installer, pilot pending). Downloads only: [lead-bot-downloads](https://github.com/Luanzzzz/lead-bot-downloads) |

---

## Featured Backend Projects

### Python

| Project | Problem and approach | Stack | Status |
| --- | --- | --- | --- |
| **[LeadFlow](https://github.com/Luanzzzz/LeadFlow)** <br> FastAPI | Small sales teams lose leads and forget follow-ups. LeadFlow models the lead pipeline and derives business states (overdue, pending follow-up) from dates and status instead of storing them. Includes a dashboard summary endpoint. | FastAPI, SQLModel, SQLite, React, Vite, pytest (4 tests) | MVP complete. Screenshots in the repo. |
| **[Gym-Tracker](https://github.com/Luanzzzz/Gym-Tracker)** <br> Django | Workout management with a custom user model, an exercise catalog and workout plans linked through an explicit intermediate model. Documented ER diagram. | Django 6, SQLite, Bootstrap 5, Django test framework (33 tests) | Complete. Built as a Mate Academy portfolio project. |

### Go

| Project | Problem and approach | Stack | Status |
| --- | --- | --- | --- |
| **[graceful-api](https://github.com/Luanzzzz/graceful-api)** <br> Backend & Systems | Persistent job queue over HTTP. Jobs are stored in PostgreSQL and claimed by concurrent worker goroutines with `FOR UPDATE SKIP LOCKED`, leases, retries with exponential backoff and idempotency keys. On SIGINT/SIGTERM it stops accepting requests, drains HTTP, and returns in-flight jobs to the queue for retry. | Go, net/http, pgx, PostgreSQL, Docker Compose | Learning project, early stage. Job processing is simulated. Not deployed. |

I am still learning Go. This project is where I practice concurrency, context cancellation and database-backed queues.

---

## AI & Intelligent Automation

| Project | Type of AI | Detail |
| --- | --- | --- |
| **[OpsCore](https://github.com/Luanzzzz/OpsCore)** | **Real LLM integration** | Inbox triage using the OpenAI Responses API with a strict JSON schema, Zod validation of the output and a rule-based fallback when no API key is set. Next.js 15, TypeScript, 58 Vitest tests. |
| **[InboxFlow](https://github.com/Luanzzzz/InboxFlow)** | **Heuristics, AI-ready design** | Django triage system that classifies category and urgency and suggests next actions with rules. The `ai/` layer is isolated for a future LLM provider. No LLM is called today. 20 Django tests. |
| **[Nexus AI Workspace](https://github.com/Luanzzzz/Nexus-AI-Workspace)** | **Planned** | Monorepo scaffold for a RAG and agents workspace (FastAPI, PostgreSQL, pgvector). Only the project structure exists so far; no feature is implemented yet. |

Not yet in a public repository: a working RAG pipeline and LangChain agents. These are in study and planned for Nexus AI Workspace.

---

## TypeScript & Full-Stack

- **[OpsCore](https://github.com/Luanzzzz/OpsCore)**: Next.js 15, React 19, TypeScript, Zod, Drizzle schema, Vitest. Inbox, tasks, agenda and an operational overview, with domain, API and UI tests. Current persistence is local file stores; the Drizzle/PostgreSQL layer is defined but not wired yet.

---

## Projects by Language

| Language | Representative projects |
| --- | --- |
| **Python** (primary) | [LeadFlow](https://github.com/Luanzzzz/LeadFlow), [InboxFlow](https://github.com/Luanzzzz/InboxFlow), [Gym-Tracker](https://github.com/Luanzzzz/Gym-Tracker) |
| **Go** (learning and applying) | [graceful-api](https://github.com/Luanzzzz/graceful-api) |
| **TypeScript** | [OpsCore](https://github.com/Luanzzzz/OpsCore) |
| **JavaScript** | [DEV QUEST](https://github.com/Luanzzzz/DEV-QUEST) (interactive 2D portfolio game, no engine, [live](https://devquest-khaki.vercel.app)) |
| **Java** | Academic coursework. No public repository yet. |

---

## Tech Stack

| Level | Technologies |
| --- | --- |
| **Applied in the projects above** | Python, TypeScript, JavaScript, SQL · FastAPI, Django, Pydantic, SQLModel, JWT · PostgreSQL, SQLite · React, Next.js, Tailwind CSS · OpenAI API with structured outputs · Playwright (E2E tests), pytest, Vitest · Docker Compose, Git, GitHub |
| **Learning and applying** | Go (concurrency, context, database-backed queues) |
| **Working knowledge** | MySQL, MongoDB, n8n workflows, Linux, Java (academic) |
| **In study** | LangChain, RAG pipelines, AI agents |

---

## Currently Building

- **graceful-api**: Go job queue, early stage (public).
- **Hi Control**: ongoing development (private).
- **Lua Lua / Lua Baby**: ongoing development (private).
- **Lead Bot**: Windows pre-release (private).

Planned, not started: the first implemented features of [Nexus AI Workspace](https://github.com/Luanzzzz/Nexus-AI-Workspace) (currently a scaffold).

---

## Contact

- LinkedIn: [luan-valentino-dos-santos](https://www.linkedin.com/in/luan-valentino-dos-santos-a2059928b/)
- GitHub: [@Luanzzzz](https://github.com/Luanzzzz)
