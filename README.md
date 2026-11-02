# Utku Gulbardak

**AI platform engineer. I build multi-domain intelligence systems and the tooling around them.**

By day I work on AI and data engineering at an industrial IoT company for injection molding,
turning sensor data from molding tools into analytics, knowledge graphs and AI assistants for
the shop floor. Outside work I build the **Opsight Intelligence Platform**.

[Website](https://opsightintel.com) · [LinkedIn](https://www.linkedin.com/in/utku-gulbardak-7511515a/)

---

### Opsight Intelligence

A federated platform where independent domain engines (fraud, maritime, manufacturing,
AI governance) each run their own collect-to-assess pipeline and publish one standardized
intelligence contract to a shared bus. A federation gateway exposes those assessments to
LLM-driven executive personas. The design is contract-first: one shared schema, pure business
logic behind thin I/O adapters, and engines that stay independent but speak the same language.

Most of it is private. The public view is the
**[architecture overview](https://github.com/opsight-intelligence/Opsight-Architecture-Overview)**.

### Public projects

| Project | What it is |
|---|---|
| [opsentry](https://github.com/opsight-intelligence/opsentry) | Security guardrails for AI coding assistants: three-layer enforcement for Claude Code. `pip install opsentry` or `brew install opsight-intelligence/opsentry/opsentry` |
| [opsentry-action](https://github.com/opsight-intelligence/opsentry-action) | GitHub Action that scans pull requests for vulnerabilities, code quality and guardrail compliance |
| [aider-toolcalling](https://github.com/utku-local/aider-toolcalling) | Native tool calling for Aider against local MLX models, with its own eval harness and model comparison |
| [OSI](https://github.com/UttyWotty/ai_build_base_2026) | AI operations copilot for manufacturing, built for the AI Builder Cup 2026. Traces a failure alert through spare parts, suppliers and orders; a team of agents drafts the plan and a person approves it. [Live demo](https://ops-copilot-432875717420.asia-southeast1.run.app) · [Video](https://youtu.be/b1bc3dhXC74) |

### Also building

- **Local LLM tooling** on Apple Silicon: model serving, agents and offline image, video and
  vision tools, all running on local MLX models.
- **Manufacturing data**: mold and shot sensor pipelines, OEE and predictive maintenance,
  supply-chain ontologies and knowledge graphs.
- **Hackathons**: OSI above, plus several entries kept private.
- **Games**: a few engine and game projects, for fun.

### How I work

Small modules, full type hints, pure logic separated from I/O, and real CI gates (lint, types,
tests) before anything ships. I build AI systems the way I build backends: grounded, governed,
testable and reliable in production.

### Tech

![Python](https://img.shields.io/badge/Python-2b5b84?style=flat-square&logo=python&logoColor=white)
![LLM Agents](https://img.shields.io/badge/LLM%20Agents-512bd4?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-0a7d33?style=flat-square)
![MLX](https://img.shields.io/badge/MLX-000000?style=flat-square&logo=apple&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-05998b?style=flat-square&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-e92063?style=flat-square&logo=pydantic&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-31648c?style=flat-square&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29b5e8?style=flat-square&logo=snowflake&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1d63ed?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088ff?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-009fe3?style=flat-square&logo=pytest&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-261230?style=flat-square&logo=ruff&logoColor=white)
