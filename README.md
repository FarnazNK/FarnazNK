# Farnaz Nasehi

## Full-Stack Software Engineer · TypeScript, React, Python & Applied AI

I build AI-powered products end to end: React/TypeScript interfaces, secure APIs, PostgreSQL data models, and LLM features grounded in real data, with retrieval, tool use, evaluations, and guardrails.

[Featured work](#featured-projects) · [Skills](#technical-skills) · [LinkedIn](https://www.linkedin.com/in/farnaz-nasehi/)

## Featured Projects

### [Grounded Agent Platform: Document RAG & Agent Harness](https://github.com/FarnazNK/grounded-agent-platform)

[Live API](https://grounded-agent-api.vercel.app/docs) · [Health](https://grounded-agent-api.vercel.app/health/live)

A grounded-agent system combining document retrieval, constrained tool use, evaluation, and observability.

- Multi-tenant document RAG with **PostgreSQL/pgvector**, full-text search, and hybrid ranking (reciprocal-rank fusion)
- Workspace-scoped authorization, prompt/context/output guardrails, PII checks, and citation validation
- Repository-aware developer agent with bounded context selection, policy-controlled tools, and explicit write opt-in
- RAG, adversarial, agent-context, and latency evaluation gates in CI
- Structured traces, Docker, Terraform, and AWS deployment paths

### [FinVision: AI-Assisted Portfolio Dashboard](https://github.com/FarnazNK/finvision)

[Dashboard](https://farnaznk.github.io/finvision/) · [Live API](https://finvision-api.vercel.app/docs)

A full-stack portfolio app that uses AI on authenticated financial data without letting the LLM do the calculations.

- **React/TypeScript** dashboard with Redux Toolkit and styled-components, tested with Jest and React Testing Library
- FastAPI services for JWT auth, PostgreSQL portfolio state, market data, and AI orchestration
- Deterministic portfolio analytics exposed to the LLM as tools
- Document retrieval with ranked evidence and source citations
- Anthropic and Finnhub integrations with offline fallbacks; Docker and GitHub Actions CI

### [SecureShop: Full-Stack E-Commerce](https://github.com/FarnazNK/secureshop-ecommerce)

[Storefront](https://secureshop-storefront.vercel.app) · [Live API](https://secureshop-api.vercel.app/api/reference)

A **React/TypeScript** storefront on a security-focused FastAPI backend.

- JWT auth, RBAC, refresh-token rotation with reuse detection
- Rate limiting, security headers, explicit CORS, request IDs, and centralized errors
- PostgreSQL with async SQLAlchemy, exact money handling, and order snapshots
- Integration tests, Docker, and CI

Each project also includes optional local Kubernetes manifests, Prometheus/Grafana monitoring, and mock-tested AWS Bedrock agent examples.

## Technical Skills

| Focus | Technologies |
| --- | --- |
| **Frontend** | TypeScript, React, Redux Toolkit, styled-components, Jest, React Testing Library |
| **Backend** | Python, FastAPI, Django REST Framework, REST, GraphQL, SQLAlchemy, PostgreSQL, Redis |
| **AI & LLMs** | Anthropic/OpenAI APIs, tool calling, agent workflows, RAG, hybrid retrieval, pgvector, LLM evaluations, guardrails |
| **DevOps** | Docker, Kubernetes, Azure CI/CD, GitHub Actions, Terraform, AWS |
