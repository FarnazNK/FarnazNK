# Hi, I'm Farnaz 👋

### Backend & AI Systems Engineer | Python · FastAPI · LLMs

📍 Calgary, AB · [LinkedIn](https://www.linkedin.com/in/farnaz-nasehi/)

I build products end to end: fast, accessible React interfaces, secure Python APIs, PostgreSQL data models, and AI features that are grounded, tested and measured.

---

## Featured projects

### 🧠 [Grounded Agent Platform](https://github.com/FarnazNK/grounded-agent-platform): applied AI
Multi-tenant RAG API with **hybrid pgvector + full-text retrieval**, citation validation and layered guardrails, plus a developer agent whose tool use is **enforced by policy outside the model**. Every PR must pass RAG, adversarial, agent-context and latency **evaluation gates**. The live demo traces each question through the whole pipeline: guardrails, hybrid search, rank fusion, grounding and output checks.
`Python` `FastAPI` `PostgreSQL/pgvector` `React` `TypeScript` `Anthropic/OpenAI` `CI eval gates`
**[Live demo](https://grounded-agent-web.vercel.app)** · [API docs](https://grounded-agent-api.vercel.app/docs) · [Code](https://github.com/FarnazNK/grounded-agent-platform)

### 📊 [FinVision](https://github.com/FarnazNK/finvision): full-stack + AI
Portfolio tracker whose AI assistant **can't make up numbers**: it calls 5 deterministic analytics tools, and code checks every figure in the answer against the tool output and cites it. Advice, off-topic and prompt-injection requests are refused before the model runs, failures fall back to computed answers, and a **20-case eval set** runs in CI. The same tools are exposed to Claude Code and Cursor through an **MCP server**. React dashboard with real market prices, a three.js landing page, Zustand state and Zod-validated API contracts.
`React` `TypeScript` `Zustand` `Zod` `three.js` `FastAPI` `Anthropic tool use` `MCP` `Evals`
**[Live website](https://farnaznk.github.io/finvision/)** · [Dashboard](https://farnaznk.github.io/finvision/app) · [Code](https://github.com/FarnazNK/finvision)

### 🔐 [SecureShop](https://github.com/FarnazNK/secureshop-ecommerce): security-first e-commerce
React storefront and FastAPI backend built around the OWASP Top 10: **refresh-token rotation with theft detection**, constant-time login, RBAC and rate limiting. Checkout runs through **Stripe Checkout with a signature-verified webhook**, idempotent orders and race-safe stock that never oversells, tested under k6 load.
`React` `TypeScript` `Tailwind` `FastAPI` `PostgreSQL` `Stripe`
**[Live storefront](https://secureshop-storefront.vercel.app)** · [API reference](https://secureshop-api.vercel.app/api/reference) · [Code](https://github.com/FarnazNK/secureshop-ecommerce)

---

## Tech I use

| Area | Technologies |
| --- | --- |
| **Frontend** | TypeScript, React, Vite, Zustand, Zod, React Query, Tailwind CSS, styled-components, Recharts, three.js / WebGL |
| **Backend** | Python, FastAPI, Pydantic, SQLAlchemy, PostgreSQL, REST, GraphQL, Redis, Django REST Framework |
| **Applied AI** | Anthropic and OpenAI APIs, tool calling, RAG, hybrid search, pgvector, guardrails, evaluation pipelines |
| **Quality & delivery** | Jest, React Testing Library, Vitest, Playwright, pytest, GitHub Actions, Docker, Kubernetes, AWS, Azure DevOps |


> All demos run on synthetic or simulated data. Each project's README explains exactly what's live and what isn't.
