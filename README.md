# Luan Valentino

**Backend Developer | Python • Go | FastAPI • Django | Engenharia de IA**

Desenvolvedor back-end brasileiro, com foco em APIs REST, modelagem de dados relacionais, regras de negócio e integração de software com LLMs. **Python é minha linguagem principal.** Também estudo **Go** em serviços concorrentes.

Estudante de Desenvolvimento de Software Multiplataforma na **FATEC Atibaia**, com formação técnica em Desenvolvimento de Sistemas na **ETEC**. Busco **estágio ou vaga júnior em back-end**, com aplicação de IA em produto, preferencialmente remoto.

[GitHub](https://github.com/Luanzzzz) · [LinkedIn](https://www.linkedin.com/in/luan-valentino-dos-santos-a2059928b/)

---

## Como ler o status dos projetos

| Status | Significado |
| --- | --- |
| **Produto em evolução** | Sistema comercial com desenvolvimento ativo e código privado |
| **Em desenvolvimento** | Em construção, com partes ainda pendentes ou sem exposição pública |
| **MVP** | Escopo mínimo completo e testado, sem deploy público |
| **Estudo** | Projeto de aprendizado ou protótipo |

---

## Experiência comercial

Sistemas comerciais dos quais participei. O código é **privado**, então descrevo apenas o que pode ser divulgado.

### Hi Control

SaaS de gestão para clínicas e profissionais de saúde: agenda, cadastros, cobrança e fluxos de NF-e.

Produção: [hicontroltec.com](https://hicontroltec.com) · app: [app.hicontroltec.com](https://app.hicontroltec.com)

Participei de parte significativa do desenvolvimento da aplicação e da lógica de negócio, no front-end e na API.

No backend, há uma camada de IA construída no código: gateway de providers com stub seguro, agentes com tool-calling, controle de créditos e budget, e o **Hi Zap**, módulo de WhatsApp via Evolution API e Cloud API da Meta.

Stack: Python, FastAPI, Pydantic, PostgreSQL, JWT, Docker, GitHub Actions · React, TypeScript, Vite, Tailwind · Playwright, Vitest.

Status: produto em evolução.

### Lua Lua Outlet

E-commerce de roupas infantis: catálogo, estoque, checkout, cálculo de frete e painel administrativo. Trabalho em desenvolvimento web, serviços de back-end e integrações comerciais.

Stack: Django, Next.js, PostgreSQL, Redis, Docker Compose, pytest.

Status: em desenvolvimento. Integração com Mercado Pago implementada, mas desativada até a homologação. Sem URL pública.

### Lead Bot

Aplicativo desktop para Windows baseado em automação de navegador. O instalador inclui Chromium e Firefox. Pré-lançamento 0.5.0 (instalador sem assinatura digital). [Downloads](https://github.com/Luanzzzz/lead-bot-downloads).

---

## Projetos públicos em destaque

### [Nexus AI Workspace](https://github.com/Luanzzzz/Nexus-AI-Workspace)

Backend de portfólio para um workspace com RAG e agentes (FastAPI, PostgreSQL, pgvector). Já implementados: autenticação com Argon2 e JWT, workspaces multi-tenant, upload de documentos, CI no GitHub Actions, pytest e Ruff. A extração de texto está em uma branch; o RAG com embeddings e busca no pgvector está em desenvolvimento. Frontend e agentes ainda não foram implementados. Sem deploy público.

Status: em desenvolvimento.

### [OpsCore](https://github.com/Luanzzzz/OpsCore)

Plataforma operacional (inbox, tarefas e agenda) com triagem assistida por **OpenAI** (Responses API, JSON Schema) e fallback heurístico quando não há chave. Next.js, TypeScript, Zod, Vitest (58 testes). A persistência atual usa arquivos locais; a camada Drizzle/PostgreSQL está definida, mas ainda não está conectada. Sem deploy público.

Status: MVP.

### [LeadFlow](https://github.com/Luanzzzz/LeadFlow)

Gestão de leads e follow-ups em FastAPI, com regras derivadas (atraso e pendência a partir de datas e status). SQLModel, SQLite, React. 4 testes. Sem deploy público.

Status: MVP.

### [graceful-api](https://github.com/Luanzzzz/graceful-api)

Fila de jobs em Go e PostgreSQL, com workers concorrentes (`FOR UPDATE SKIP LOCKED`), lease, retry com backoff exponencial, idempotência e graceful shutdown. Projeto de estudo: o processamento do job é simulado, não há testes automatizados e não há deploy público.

Status: estudo.

---

## Stack

Tecnologias que uso nos projetos acima:

- **Linguagens:** Python, TypeScript, JavaScript, SQL, Go
- **Backend:** FastAPI, Django, Pydantic, SQLModel, JWT, Argon2
- **Dados:** PostgreSQL, pgvector, SQLite, Redis, Alembic
- **Frontend:** React, Next.js, Vite, Tailwind CSS
- **IA:** OpenAI API (Responses API, no OpsCore)
- **Qualidade e infra:** pytest, Vitest, Playwright, Ruff, Docker, Docker Compose, GitHub Actions, Git

---

## Estudando agora

Fundamentos de ML/LLMs, RAG e avaliação.

---

## Contato

[LinkedIn](https://www.linkedin.com/in/luan-valentino-dos-santos-a2059928b/) · [GitHub](https://github.com/Luanzzzz)
