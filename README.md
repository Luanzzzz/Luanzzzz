🇧🇷 Português | [🇺🇸 English](README.en.md)

# Luan Valentino

**Backend Developer | Python • Go | FastAPI • Django | AI & Automation**

Desenvolvedor back-end brasileiro, com foco em APIs REST, modelagem de dados relacionais, regras de negócio e integrações entre sistemas. **Python é minha linguagem principal.** Estou estudando e aplicando **Go** em serviços concorrentes e avançando em **engenharia de IA** (integração com LLMs) e **automação**.

Estudante de Desenvolvimento de Software Multiplataforma na **FATEC Atibaia**, com formação técnica anterior em Desenvolvimento de Sistemas na **ETEC**. Busco **estágio ou vaga júnior em back-end**, preferencialmente remoto.

[GitHub](https://github.com/Luanzzzz) · [LinkedIn](https://www.linkedin.com/in/luan-valentino-dos-santos-a2059928b/)

---

## Como ler o status dos projetos

| Status | Significado |
| --- | --- |
| **Produto em evolução** | Sistema comercial com desenvolvimento ativo e código privado |
| **Em desenvolvimento** | Em construção, ainda não liberado ao público |
| **MVP** | Escopo mínimo completo e testado, sem deploy público |
| **Estudo** | Projeto de aprendizado, curso ou protótipo |
| **Online** | Projeto pessoal disponível publicamente |

Dos projetos públicos abaixo, apenas o DEV QUEST está online. Os de back-end rodam localmente e não têm deploy.

---

## Experiência comercial

Sistemas comerciais dos quais participei. O código é **privado** (`Private Source Code`), então descrevo apenas o que pode ser divulgado.

| Projeto | O que é | Minha contribuição | Stack confirmada | Status |
| --- | --- | --- | --- | --- |
| **Hi Control** | SaaS de gestão para o mercado brasileiro: agenda, cadastros, cobrança e fluxos de NF-e. [Site do produto](https://site-hi-control.vercel.app) | Parte significativa do desenvolvimento da aplicação e da lógica de negócio, no front-end e na API | FastAPI, PostgreSQL (Supabase), Pydantic v2, JWT · React, TypeScript, Vite, Tailwind · Playwright, Vitest | Produto em evolução |
| **Lua Lua / Lua Baby** | E-commerce de roupas infantis: catálogo, estoque, checkout, cálculo de frete e painel administrativo | Desenvolvimento web, serviços de back-end e integrações comerciais | Django, Next.js, PostgreSQL, Redis, Docker Compose, pytest | Em desenvolvimento. Integração com Mercado Pago implementada, mas desativada até a homologação. Sem URL pública |
| **Lead Bot** | Aplicativo desktop para Windows baseado em automação de navegador | Desenvolvimento do aplicativo | Instalador inclui Chromium e Firefox | Pré-lançamento 0.5.0 (instalador sem assinatura digital). [Downloads](https://github.com/Luanzzzz/lead-bot-downloads) |

---

## Projetos públicos em destaque

| Projeto | Foco | O que demonstra | Status |
| --- | --- | --- | --- |
| [**LeadFlow**](https://github.com/Luanzzzz/LeadFlow) | Python · FastAPI | Gestão de leads e follow-ups. Regras derivadas (atraso e pendência calculados a partir de datas e status). SQLModel, SQLite, React. 4 testes | MVP |
| [**InboxFlow**](https://github.com/Luanzzzz/InboxFlow) | Python · Django | Triagem de demandas com classificação por categoria e urgência e sugestões por heurística. Camada `ai/` preparada para LLM. 20 testes | MVP |
| [**OpsCore**](https://github.com/Luanzzzz/OpsCore) | TypeScript · IA | Triagem de inbox com **OpenAI** (Responses API, JSON Schema estrito, validação com Zod) e fallback por regras. Next.js 15. 58 testes | MVP |
| [**graceful-api**](https://github.com/Luanzzzz/graceful-api) | Go · PostgreSQL | Fila de jobs com workers concorrentes (goroutines), `FOR UPDATE SKIP LOCKED`, lease, retry com backoff exponencial, idempotência e graceful shutdown | Estudo |
| [**Gym-Tracker**](https://github.com/Luanzzzz/Gym-Tracker) | Python · Django | CRUD, autenticação, modelo de usuário customizado e relacionamento N:N com modelo intermediário. 33 testes. Projeto da Mate Academy | Estudo |
| [**DEV QUEST**](https://github.com/Luanzzzz/DEV-QUEST) | JavaScript | Portfólio em forma de jogo 2D, sem engine. [Demo online](https://devquest-khaki.vercel.app) | Online |

### Ressalvas

- **graceful-api:** o processamento do job é simulado (espera de 3 segundos), não há testes automatizados e **não há deploy público**.
- **OpsCore:** a persistência atual usa armazenamento local em arquivos. A camada Drizzle/PostgreSQL está definida, mas ainda não está conectada.
- **InboxFlow:** nenhum LLM é chamado hoje. A sugestão é feita por regras.
- **IA:** o OpsCore é o único projeto público com integração real de LLM. Pipeline de RAG e agentes com LangChain ainda não estão em repositório público.

---

## Tech Stack

| Nível | Tecnologias |
| --- | --- |
| **Aplicadas nos projetos acima** | Python, TypeScript, JavaScript, SQL · FastAPI, Django, Pydantic, SQLModel, JWT · PostgreSQL, SQLite · React, Next.js, Tailwind CSS · OpenAI API · pytest, Vitest, Playwright · Docker Compose, Git, GitHub |
| **Aprendendo e aplicando** | Go (concorrência, `context`, filas em banco de dados) |
| **Conhecimento de trabalho** | MySQL, MongoDB, n8n, Linux, Java (acadêmico) |
| **Em estudo** | LangChain, RAG, AI agents |

---

## Em andamento

- **graceful-api:** fila de jobs em Go, fase inicial.
- **[Nexus AI Workspace](https://github.com/Luanzzzz/Nexus-AI-Workspace):** apenas a estrutura do monorepo (FastAPI, PostgreSQL, pgvector planejado). Nenhuma funcionalidade implementada ainda.
- **Hi Control, Lua Lua / Lua Baby e Lead Bot:** desenvolvimento contínuo (privado).

---

## Contato

[LinkedIn](https://www.linkedin.com/in/luan-valentino-dos-santos-a2059928b/) · [GitHub](https://github.com/Luanzzzz)

---

🇧🇷 Português | [🇺🇸 English](README.en.md)
