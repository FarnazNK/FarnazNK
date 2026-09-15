# Farnaz Nasehi

## Backend & AI Systems Engineer

I build production-oriented backend systems and AI infrastructure with **Python, TypeScript, FastAPI, PostgreSQL, Redis, Docker, AWS, and modern LLM tooling**.

My work focuses on **agentic systems, retrieval, context engineering, developer tooling, APIs, evaluation, security, observability, and production reliability**.

I’m especially interested in systems where AI has to do real work safely: selecting the right context, using tools, operating within explicit permissions, verifying its own output, and producing behavior that can be measured and debugged.

---

## Featured Projects

### [RAG Agent — Retrieval + Developer Agent Platform](https://github.com/FarnazNK/rag-agent)

**Live RAG API:** [API](https://rag-agent-api-2uau.onrender.com/) · [Docs](https://rag-agent-api-2uau.onrender.com/docs) · [Health](https://rag-agent-api-2uau.onrender.com/health/live)

A production-oriented AI systems project with two complementary surfaces:

- a multi-tenant RAG API for grounded document answers;
- a repository-aware developer-agent harness for context selection, tool use, reusable skills, verification, and traceable software-engineering workflows.

**Developer-agent architecture**
- Task-aware repository context selection with bounded context budgets
- Code-aware matching for source files, identifiers, and implementation paths
- LLM tool-planning loop with Anthropic/OpenAI support
- Registry-backed tools for file listing, reads, code search, writes, and verification commands
- Explicit write opt-in and repository-root confinement
- Sensitive-file filtering and command allowlists
- Reusable YAML skills for code changes, debugging, and review
- Structured per-step traces with tool outcomes and changed-file tracking
- Context-selection evaluation dataset with CI quality gates

**RAG architecture**
- Hybrid dense + lexical retrieval with reciprocal-rank fusion
- PostgreSQL + pgvector
- JWT authentication and workspace-scoped authorization
- Prompt-injection checks and output/citation validation
- RAG quality and adversarial evaluation gates
- Prometheus metrics, Grafana dashboards, and structured logging
- Docker, Terraform, AWS Lambda/SAM, and GitHub Actions

**Engineering focus:** context quality, agent safety boundaries, evals, observability, deterministic CI, and production trade-offs.

---

### [SecureShop](https://github.com/FarnazNK/secureshop-ecommerce)

**Live:** [Storefront](https://secureshop-l35h.onrender.com) · [API](https://secureshop-api-zckt.onrender.com/) · [Products](https://secureshop-api-zckt.onrender.com/api/v1/products) · [Health](https://secureshop-api-zckt.onrender.com/api/v1/health)

Security-focused backend application built with **FastAPI, PostgreSQL, Redis, JWT, RBAC, Stripe, Docker, and CI**.

- Layered API/service architecture
- Refresh-token rotation and reuse detection
- Authentication and authorization flows
- Rate limiting and secure defaults
- Automated tests against real infrastructure services
- Dockerized local and deployment workflows

---

### [FinVision](https://github.com/FarnazNK/finvision)

**Live:** [Dashboard](https://farnaznk.github.io/finvision/) · [API](https://finvision-api.onrender.com/) · [Health](https://finvision-api.onrender.com/health) · [Docs](https://finvision-api.onrender.com/docs)

AI-assisted financial platform combining a **FastAPI backend, PostgreSQL-compatible persistence, portfolio analytics, AI research workflows, and React/TypeScript**.

- JWT-authenticated portfolio APIs
- AI insights grounded in portfolio data
- Document retrieval with citations
- Backend/frontend integration
- Dockerized services and CI/CD
- Public frontend demo backed by a production-oriented API

---

## Engineering Areas

### Agentic AI
- Tool-calling agents
- Repository-aware coding workflows
- Context engineering
- Agent skills and tool registries
- Permission boundaries
- Guardrails
- Agent traces
- Task-level evaluations

### Retrieval & LLM Systems
- RAG
- Hybrid search
- pgvector
- Dense + lexical retrieval
- Reciprocal-rank fusion
- Prompt/context engineering
- Grounded generation
- Citation validation
- LLM evaluation

### Backend Systems
- Python
- FastAPI
- Node.js / Express
- REST APIs
- SQLAlchemy
- PostgreSQL
- Redis
- Authentication / authorization
- Multi-tenant systems

### Infrastructure & Reliability
- Docker / Docker Compose
- AWS Lambda / SAM
- Terraform
- GitHub Actions
- Prometheus
- Grafana
- Structured logging
- Load testing
- CI quality gates
- Dependency scanning

### Frontend
- TypeScript
- React

---

## How I Build

I prefer systems with:

- clear API and service boundaries;
- explicit permissions and failure modes;
- tests that cover behavior rather than just happy paths;
- measurable AI quality;
- observable execution;
- reproducible local and CI environments;
- security controls outside the model;
- verification before autonomous changes are considered complete;
- architecture that can evolve without hiding operational trade-offs.

---

## Current Technical Focus

- Developer-agent infrastructure
- Large-codebase context selection
- Tool-using LLM systems
- Agent evals and observability
- Safe code execution boundaries
- Retrieval quality
- Backend platform engineering
- Production AI systems

---

## Connect

[LinkedIn](https://www.linkedin.com/in/farnaz-nasehi/)
