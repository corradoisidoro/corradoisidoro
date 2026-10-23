# Hi, I'm Corrado Isidoro 👋

**Senior Software Engineer · .NET/C# backend systems · AI/LLM applications**

📍 Prague, Czech Republic · [LinkedIn](https://www.linkedin.com/in/corrado-isidoro-4230a167) · [All repositories](https://github.com/corradoisidoro?tab=repositories)

## About

I have 15+ years of experience building and running production backend systems in C#/.NET across on-premises, hybrid, AWS and Azure environments: APIs, microservices, performance, and reliability.

I also build LLM applications in Python: RAG pipelines on PostgreSQL/pgvector, tool-calling agents and MCP integrations. I care about what makes these systems dependable in practice: failure handling, security boundaries, testing and observability.

Open to senior backend and AI engineering roles with English-speaking teams.

## Selected projects

### AI / LLM

- **[mini-agent-code](https://github.com/corradoisidoro/mini-agent-code)**: a tool-calling coding agent in pure Python, without an agent framework. Covers the model/tool loop, tool schemas, human confirmation for file writes and shell commands, and a turn-limit safeguard. Strictly typed (`mypy --strict`), tested with pytest, CI on every push.
- **[agent-harness](https://github.com/corradoisidoro/agent-harness)**: a personal-assistant agent with a provider-agnostic loop over any OpenAI-compatible endpoint (local Ollama by default), MCP server tools, workspace-confined file tools and persistent memory. Failures are contained per tool and per model call. Tested with pytest, linted with Ruff, CI on every push.
- **[feedback-insights](https://github.com/corradoisidoro/feedback-insights)**: turn a batch of customer reviews into per-review labels, 1–5 scores, and themes with aggregate insights. Runs fully locally with FastAPI, Streamlit, Ollama, and SQLite. Features schema-constrained LLM outputs, per-review error isolation, and 100% test coverage.

### Backend

- **[orders-api](https://github.com/corradoisidoro/orders-api)**: Go order-management API on PostgreSQL with clean architecture, migrations, pagination, per-client rate limiting, graceful shutdown, Docker and 90%+ test coverage on core packages.
- **[CleanCinema](https://github.com/corradoisidoro/CleanCinema)**: layered .NET 10 CQRS sample with an ASP.NET Core Minimal API, MediatR, EF Core, a FluentValidation pipeline, RFC 7807 ProblemDetails error handling and 24 xUnit tests against a real SQLite database. React/TypeScript client.
- **[sentinel-rbac](https://github.com/corradoisidoro/sentinel-rbac)**: Go (Gin, GORM) API with JWT authentication in httpOnly cookies, role-based access control middleware, layered rate limiting and Swagger documentation.

## Tech I work with

- **Languages:** C#, Python, Go, SQL
- **Backend:** .NET, ASP.NET Core, Entity Framework Core, FastAPI, REST, microservices, distributed systems
- **AI / LLM:** OpenAI API, RAG, pgvector, ChromaDB, LangChain, LangGraph, Ollama, MCP
- **Data:** PostgreSQL, SQL Server, Redis, Kafka, Elasticsearch
- **Cloud & delivery:** AWS, Azure, Docker, CI/CD, Splunk

## Engineering impact

Outcomes from my professional work (scope and measurement vary by project, and I'm happy to discuss the context):

- Improved API response times and throughput by **20%**.
- Kept production services at **99.9% uptime** under traffic spikes.
- Reduced mean time to recovery (MTTR) by **30%** with monitoring and alerting.
- Built automation saving **10+ hours of manual work per week**.

## Connect

[LinkedIn](https://www.linkedin.com/in/corrado-isidoro-4230a167) · [Repositories](https://github.com/corradoisidoro?tab=repositories)
