# Hi, I'm Farnaz 👋

### Backend & AI Systems Engineer | Python · FastAPI · LLMs

[LinkedIn](https://www.linkedin.com/in/farnaz-nasehi/)

I build products end to end: fast, accessible React interfaces, secure Python APIs, PostgreSQL data models, and AI features that are grounded, tested and measured.

---

## Featured projects

### 🧠 [Grounded Agent Platform](https://github.com/FarnazNK/grounded-agent-platform): applied AI
A multi-tenant RAG API that answers only from your documents, cites them, and refuses when the evidence isn't there.
- **Retrieval:** hybrid pgvector + full-text search with rank fusion, citation validation and layered guardrails
- **Quality gates:** every PR must pass RAG, adversarial, agent-context and latency evaluations in CI
- **Security:** workspace isolation, rate limits shared across replicas (Redis/Valkey), and an audit trail of which documents each user saw
- **Developer agent:** tool use enforced by policy in code, not by the prompt

`Python` `FastAPI` `PostgreSQL/pgvector` `Redis/Valkey` `React` `TypeScript` `Anthropic/OpenAI` `CI eval gates`
**[Live demo](https://grounded-agent-web.vercel.app)** · [API docs](https://grounded-agent-api.vercel.app/docs) · [Code](https://github.com/FarnazNK/grounded-agent-platform)

### 📊 [FinVision](https://github.com/FarnazNK/finvision): full-stack + AI
A portfolio tracker whose AI assistant can't make up numbers, and never sees the customer's.
- **Verified answers:** the model calls 5 deterministic analytics tools; code checks every figure in the answer and cites where it came from
- **Privacy by design:** balances and transactions become placeholders before anything reaches the model provider (leak test: 38 values sent before, 0 now)
- **Quant-grade simulation:** correlated geometric Brownian motion (Cholesky) with mean-reverting intraday ticks, statistically tested
- **Agent-ready:** the same tools are exposed to Claude Code and Cursor through an MCP server; a 20-case eval set runs in CI

`React` `TypeScript` `Zustand` `Zod` `three.js` `FastAPI` `Anthropic tool use` `MCP` `Evals`
**[Live website](https://farnaznk.github.io/finvision/)** · [Dashboard](https://farnaznk.github.io/finvision/app) · [Code](https://github.com/FarnazNK/finvision)

### 🔐 [SecureShop](https://github.com/FarnazNK/secureshop-ecommerce): security-first e-commerce
A React storefront and FastAPI backend built around the OWASP Top 10.
- **Auth:** refresh-token rotation with theft detection, constant-time login, RBAC and rate limiting
- **Payments:** Stripe Checkout with a signature-verified webhook and idempotent orders
- **Inventory:** race-safe stock that never oversells, tested under k6 load

`React` `TypeScript` `Tailwind` `FastAPI` `PostgreSQL` `Stripe`
**[Live storefront](https://secureshop-storefront.vercel.app)** · [API reference](https://secureshop-api.vercel.app/api/reference) · [Code](https://github.com/FarnazNK/secureshop-ecommerce)

---

## Tech I use

| Area | Technologies |
| --- | --- |
| **Frontend** | TypeScript, React, Vite, Zustand, Zod, React Query, Tailwind CSS, styled-components, Recharts, three.js / WebGL |
| **Backend** | Python, FastAPI, Pydantic, SQLAlchemy, PostgreSQL, REST, GraphQL, Redis, Django REST Framework |
| **Applied AI** | Anthropic and OpenAI APIs, tool calling, RAG, hybrid search, pgvector, guardrails, evaluation pipelines, keeping sensitive data away from model providers |
| **Quant & simulation** | Geometric Brownian motion, correlated returns (Cholesky), Ornstein–Uhlenbeck processes, seeded reproducible simulation, statistical testing |
| **Security** | OWASP Top 10, JWT and refresh-token rotation, rate limiting, audit logging, input validation, CodeQL, Bandit, dependency audits |
| **Quality & delivery** | Jest, React Testing Library, Vitest, Playwright, pytest, GitHub Actions, Docker, Kubernetes, AWS, Azure DevOps |


> All demos run on synthetic or simulated data. Each project's README explains exactly what's live and what isn't.
