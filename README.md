# Utku Gulbardak

**AI platform engineer building multi-domain intelligence systems.**

I design and build the **Opsight Intelligence Platform** — a federated system where
independent domain engines (fraud, maritime, manufacturing, AI-governance) each run
their own collect-to-assess pipeline and publish a single standardized intelligence
contract to a shared bus, which a federation gateway exposes to LLM-driven executive
AI personas. The focus is contract-first architecture: one shared schema, strict
pure-core / thin-I/O layering, and engines that stay independent yet speak the same
language.

I build AI systems the way I build backends — with real engineering discipline:
grounded, governed, testable, and reliable in production.

---

### What I work on

- **AI systems** — LLM-driven agents, MCP servers, RAG pipelines, and executive AI
personas that consume structured assessments; prompt design, structured outputs,
tool/function calling, and AI governance (grounding, human-in-control, evaluation).
- **Platform architecture** — contract-first design, dependency inversion, pure
business logic isolated from I/O adapters, single-source-of-truth registries.
- **Intelligence pipelines** — collect, normalize, enrich, detect, score, assess,
publish; idempotent, content-addressed artifacts.
- **Distributed services** — Python backends, an event/intelligence bus, MCP servers
and a federation gateway.
- **Engineering discipline** — small modules, full type hints, real CI gates
(lint + types + tests), reproducible releases.

### Tech

![Python](https://img.shields.io/badge/Python-2b5b84?style=flat-square&logo=python&logoColor=white)
![LLMs](https://img.shields.io/badge/LLM%20Agents-512bd4?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-0a7d33?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-05998b?style=flat-square&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-e92063?style=flat-square&logo=pydantic&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-31648c?style=flat-square&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29b5e8?style=flat-square&logo=snowflake&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1d63ed?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088ff?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-009fe3?style=flat-square&logo=pytest&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-261230?style=flat-square&logo=ruff&logoColor=white)

### Currently

Aligning every Opsight domain engine onto the Intelligence Bus, building out the MCP
federation gateway, and moving the executive AI personas to consume structured
assessments instead of raw documents.

### Where the work lives

Active development happens in the **Opsight Intelligence** organization, where
the domain engines, intelligence bus, and federation gateway are built. Most of
those repositories are private, so for a public, high-level view of the
architecture and design principles, see:

**→ [Opsight Architecture Overview](https://github.com/UttyWotty/Opsight-Architecture-Overview)**

This profile focuses on the platform-level thinking; the overview repo describes
the system without exposing implementation details.
