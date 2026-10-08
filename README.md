# Farnaz Nasehi

## Backend & AI Systems Engineer

I build backend platforms and AI systems with **Python, TypeScript, FastAPI, PostgreSQL, Redis, Docker, AWS, and LLM tooling**.

Main areas: **grounded agents, context engineering, retrieval, tool use, evaluation, guardrails, security, and observability**.

## Featured Projects

### [Grounded Agent Platform — Retrieval, Tools, Evals & Guardrails](https://github.com/FarnazNK/grounded-agent-platform)

[Live API](https://rag-agent-api-2uau.onrender.com/docs) · [Docs](https://rag-agent-api-2uau.onrender.com/docs) · [Health](https://rag-agent-api-2uau.onrender.com/health/live)

Production-oriented grounded-agent system combining retrieval, constrained tool use, evaluation, verification, and observability.

- Repository-aware developer agent with bounded context selection and reusable skills
- Policy-controlled tools for code search, file operations, and verification commands
- Multi-tenant grounded retrieval with **PostgreSQL/pgvector**, lexical search, and hybrid ranking
- Explicit write opt-in, sensitive-path protection, prompt/context/output guardrails, and citation validation
- Dedicated RAG, adversarial, developer-agent context, and latency evaluation gates in CI
- Structured traces, Prometheus/Grafana observability, Docker, Terraform, and AWS deployment paths

### [FinVision — AI-Assisted Portfolio Intelligence](https://github.com/FarnazNK/finvision)

[Dashboard](https://farnaznk.github.io/finvision/) · [Live API](https://finvision-api.onrender.com/docs) · [Docs](https://finvision-api.onrender.com/docs)

Portfolio intelligence system that applies grounded AI to authenticated financial data instead of treating the LLM as the source of calculations.

- Deterministic portfolio analytics exposed as tools for AI-assisted insights
- Document-retrieval prototype with ranked evidence and source citations
- FastAPI services for JWT auth, PostgreSQL portfolio state, market-data adapters, AI orchestration, and retrieval
- Optional Anthropic and Finnhub integrations with deterministic/offline fallbacks
- React/TypeScript product surface, Dockerized services, automated tests, and GitHub Actions CI

### [SecureShop — Security-Focused Backend](https://github.com/FarnazNK/secureshop-ecommerce)

[Storefront](https://secureshop-l35h.onrender.com) · [Live API](https://secureshop-api-zckt.onrender.com/api/reference)

Production-style FastAPI e-commerce system demonstrating backend security and transactional design.

- PostgreSQL, async SQLAlchemy, JWT/RBAC, refresh-token rotation, and reuse detection
- Rate limiting, security headers, explicit CORS, request IDs, and centralized errors
- Numeric money handling, order snapshots, Docker, integration tests, and CI

## Core Stack

**Backend:** Python, FastAPI, Node.js, SQLAlchemy, PostgreSQL, Redis  
**AI:** grounded agents, tool calling, context engineering, hybrid retrieval, pgvector, LLM evals, guardrails  
**Infrastructure:** Docker, AWS Lambda/SAM, Terraform, GitHub Actions, Prometheus, Grafana  
**Frontend:** TypeScript, React

## Connect

[LinkedIn](https://www.linkedin.com/in/farnaz-nasehi/)
