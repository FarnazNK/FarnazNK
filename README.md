# Hi, I'm Farnaz 👋

### Full-Stack Engineer · React / TypeScript · Python / FastAPI · Applied AI

📍 Calgary, AB · Open to remote roles · [LinkedIn](https://www.linkedin.com/in/farnaz-nasehi/)

I build products end to end: fast, accessible React interfaces, secure Python APIs, PostgreSQL data models, and AI features that are grounded, tested and measured.

---

## Featured projects

### 🧠 [Grounded Agent Platform](https://github.com/FarnazNK/grounded-agent-platform): applied AI
Multi-tenant RAG API with **hybrid pgvector + full-text retrieval**, citation validation and layered guardrails, plus a developer agent whose tool use is **enforced by policy outside the model**. Every PR must pass RAG, adversarial, agent-context and latency **evaluation gates**. The live demo traces each question through the whole pipeline: guardrails, hybrid search, rank fusion, grounding and output checks.
`Python` `FastAPI` `PostgreSQL/pgvector` `React` `TypeScript` `Anthropic/OpenAI` `CI eval gates`
**[Live demo](https://grounded-agent-web.vercel.app)** · [API docs](https://grounded-agent-api.vercel.app/docs) · [Code](https://github.com/FarnazNK/grounded-agent-platform)

### 📊 [FinVision](https://github.com/FarnazNK/finvision): full-stack + AI
Portfolio tracker with an animated **three.js** landing page, a responsive dashboard and an AI assistant that calls **5 deterministic analytics tools** instead of doing math itself, and cites them.
`React` `TypeScript` `Redux Toolkit` `three.js` `FastAPI` `Anthropic tool use`
**[Live website](https://farnaznk.github.io/finvision/)** · [Dashboard](https://farnaznk.github.io/finvision/app) · [Code](https://github.com/FarnazNK/finvision)

### 🔐 [SecureShop](https://github.com/FarnazNK/secureshop-ecommerce): security-first e-commerce
React storefront and FastAPI backend built around the OWASP Top 10: **refresh-token rotation with theft detection**, constant-time login, RBAC, rate limiting, exact-decimal money and Stripe payment intents.
`React` `TypeScript` `Tailwind` `FastAPI` `PostgreSQL` `Stripe`
**[Live storefront](https://secureshop-storefront.vercel.app)** · [API reference](https://secureshop-api.vercel.app/api/reference) · [Code](https://github.com/FarnazNK/secureshop-ecommerce)

---

## Tech I use

| Area | Technologies |
| --- | --- |
| **Frontend** | TypeScript, React, Vite, Redux Toolkit, React Query, Tailwind CSS, styled-components, Recharts, three.js / WebGL |
| **Backend** | Python, FastAPI, Pydantic, SQLAlchemy, PostgreSQL, REST, GraphQL, Redis, Django REST Framework |
| **Applied AI** | Anthropic and OpenAI APIs, tool calling, RAG, hybrid search, pgvector, guardrails, evaluation pipelines |
| **Quality & delivery** | Jest, React Testing Library, Vitest, Playwright, pytest, GitHub Actions, Docker, Terraform, AWS, Azure DevOps |

## How I work

- **Measure AI, don't trust it.** Evaluation gates in CI, citations that get checked, and models that call tools for the numbers.
- **Security by default.** Least-privilege access, validated inputs, secrets that fail fast.
- **Ship it and test it.** Every project here is live, has CI, and documents its limitations honestly.

> All demos run on synthetic or simulated data. Each project's README explains exactly what's live and what isn't.
