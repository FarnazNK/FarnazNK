# Farnaz Nasehi

## Full Stack Software Engineer | Python, React & Applied AI

I build **full-stack applications, secure Python APIs, and grounded AI systems**—from React/TypeScript interfaces and database-backed services to retrieval, tool use, evaluations, and observability.

**Focus:** Full-stack engineering · Python backends · React/TypeScript · Applied AI

[Featured work](#featured-projects) · [Skills](#technical-skills) · [LinkedIn](https://www.linkedin.com/in/farnaz-nasehi/)

## AWS AI Agent Portfolio

These projects demonstrate **AWS Bedrock, Strands Agents and AgentCore integration patterns** as **local, mock-tested reference implementations**. The AWS features are **opt-in and disabled by default**, so the demo requires no AWS account, API keys, or cloud spend. This is not a claim of live AWS deployment.

| Project | Security-focused AI implementation | Free offline demo |
| --- | --- | --- |
| [Grounded Agent Platform](https://github.com/FarnazNK/grounded-agent-platform) | Read-only Strands agent, Bedrock Guardrails configuration, AgentCore runtime adapter, JWT- and workspace-scoped retrieval | `python aws_agent/demo_offline.py` |
| [FinVision](https://github.com/FarnazNK/finvision) | JWT-scoped portfolio assistant with minimized holdings context, no trading permissions | `python aws_agentcore/demo_offline.py` |
| [SecureShop](https://github.com/FarnazNK/secureshop-ecommerce) | Read-only product-catalog assistant with no orders, payment or customer context | `python aws_agentcore/demo_offline.py` |

Each repository contains offline security regression tests, CI checks and a portfolio walkthrough (`aws_agent/PORTFOLIO.md` or `aws_agentcore/PORTFOLIO.md`). The existing hosted applications are separate from these non-deployed AWS demos.

## Kubernetes & Docker — Free Local Container Orchestration

All three projects include an **optional, local Kubernetes (kind) reference setup** using the existing Docker-built images. The manifests define Deployments, internal Services, container resource limits, runtime-generated Secrets and local PostgreSQL storage. Each project provides an [installation walkthrough](https://github.com/FarnazNK/grounded-agent-platform/blob/main/k8s/README.md) and automated manifest validation in GitHub Actions. These are **portfolio development configurations**, not deployed public Kubernetes clusters. No AWS or paid cloud account required.

| Project | Kubernetes guide |
| --- | --- |
| [Grounded Agent Platform](https://github.com/FarnazNK/grounded-agent-platform) | [Local cluster walkthrough](https://github.com/FarnazNK/grounded-agent-platform/blob/main/k8s/README.md) |
| [FinVision](https://github.com/FarnazNK/finvision) | [Local cluster walkthrough](https://github.com/FarnazNK/finvision/blob/main/k8s/README.md) |
| [SecureShop](https://github.com/FarnazNK/secureshop-ecommerce) | [Local cluster walkthrough](https://github.com/FarnazNK/secureshop-ecommerce/blob/main/k8s/README.md) |

## Featured Projects

### [Grounded Agent Platform — Retrieval, Tools, Evals & Guardrails](https://github.com/FarnazNK/grounded-agent-platform)

[Live API](https://grounded-agent-api.vercel.app/docs) · [Health](https://grounded-agent-api.vercel.app/health/live)

Production-oriented grounded-agent system combining retrieval, constrained tool use, evaluation, verification, and observability.

- Repository-aware developer agent with bounded context selection and reusable skills
- Policy-controlled tools for code search, file operations, and verification commands
- Multi-tenant grounded retrieval with **PostgreSQL/pgvector**, lexical search, and hybrid ranking
- Local gRPC/Protocol Buffers retrieval demo with workspace-scoped authentication, deadlines, and offline security tests (public API remains REST)
- Explicit write opt-in, sensitive-path protection, prompt/context/output guardrails, and citation validation
- Dedicated RAG, adversarial, developer-agent context, and latency evaluation gates in CI
- Structured traces, Prometheus/Grafana observability, Docker, Terraform, and AWS deployment paths

### [FinVision — AI-Assisted Portfolio Intelligence](https://github.com/FarnazNK/finvision)

[Dashboard](https://farnaznk.github.io/finvision/) · [Live API](https://finvision-api.vercel.app/docs)

Portfolio intelligence system that applies grounded AI to authenticated financial data instead of treating the LLM as the source of calculations.

- Deterministic portfolio analytics exposed as tools for AI-assisted insights
- Document-retrieval prototype with ranked evidence and source citations
- FastAPI services for JWT auth, PostgreSQL portfolio state, market-data adapters, AI orchestration, and retrieval
- Read-only **GraphQL** dashboard queries with JWT-scoped holdings, query bounds, and regression tests alongside the REST APIs
- Optional Anthropic and Finnhub integrations with deterministic/offline fallbacks
- React/TypeScript dashboard with Redux Toolkit and styled-components; Jest/React Testing Library, pytest, Docker, and GitHub Actions CI

### [SecureShop — Security-Focused Backend](https://github.com/FarnazNK/secureshop-ecommerce)

[Storefront](https://secureshop-storefront.vercel.app) · [Live API](https://secureshop-api.vercel.app/api/reference)

Production-style FastAPI e-commerce system demonstrating backend security and transactional design.

- PostgreSQL, async SQLAlchemy, JWT/RBAC, refresh-token rotation, and reuse detection
- Rate limiting, security headers, explicit CORS, request IDs, and centralized errors
- Numeric money handling, order snapshots, Docker, integration tests, and CI

## Technical Skills

| Focus | Technologies |
| --- | --- |
| **Backend** | Python, FastAPI, REST, GraphQL, gRPC, Protocol Buffers, Django, Django REST Framework, Node.js, SQLAlchemy, PostgreSQL, MySQL, Redis |
| **AI & LLMs** | Grounded agents, tool calling, context engineering, hybrid retrieval, pgvector, LLM evaluations, guardrails |
| **Cloud & DevOps** | Docker, Kubernetes, kind, AWS Lambda/SAM, Terraform, GitHub Actions, Prometheus, Grafana |
| **Frontend** | TypeScript, React, Redux Toolkit, styled-components, Jest, React Testing Library |

**[Connect on LinkedIn](https://www.linkedin.com/in/farnaz-nasehi/)**
