# Hi, I'm Marcus Hightower 👋

Senior software engineer with 25+ years building backend systems, platform infrastructure, and automation pipelines. I use AI coding tools — Claude Code, GitHub Copilot, Gemini CLI — as a core part of how I design and ship software, not as a novelty.

I own the full delivery cycle: system architecture → backend development → CI/CD automation → containerization → production observability.

---

## 🔨 What I'm Building

### [Gopher-Pulse Observability Agent](https://github.com/mhightower/Gopher-Pulse_Observability_Agent)

A Go-based SRE observability agent built with Claude Code. Collects metrics from multiple providers via OpenTelemetry, exposes a Prometheus endpoint, and provisions a live Grafana dashboard automatically. Includes CI/CD, linting, 80%+ test coverage gate, and a full containerized stack.

`Go` `OpenTelemetry` `Prometheus` `Grafana` `Docker` `GitHub Actions` `MCP`

### [Autonomous Delta-Neutral Arbitrageur](https://github.com/mhightower/Autonomous_Delta-Neutral_Arbitrageur)

An AI-assisted crypto arbitrage agent built in Python. Uses a LangGraph workflow (monitor → AI auditor → executor) to evaluate cross-exchange spreads, get an LLM GO/WAIT decision before any trade execution, and log all decisions to a live Streamlit dashboard.

`Python` `LangGraph` `CCXT` `Streamlit` `SQLite` `Docker` `Anthropic API`

### [MyFinancial — AI-Powered Investment Discipline Platform](https://github.com/mhightower/My-Financial-AI-App)

A full-stack personal investment tracker engineered to eliminate emotional decision-making at the point of entry. Forces structured buy thesis documentation and explicit sell conditions before any position is opened — creating an auditable decision trail. Integrates Claude API to perform real-time gap analysis on investment theses and surface missed exit criteria. Backed by a fully async FastAPI + SQLAlchemy 2 data layer, server-side TTL caching for Alpha Vantage market data, and a 272-test suite (127 backend + 180 frontend + Playwright E2E) with ~80% line coverage.

`Python` `FastAPI` `SQLAlchemy` `Vue 3` `Pinia` `Vite` `SQLite` `Alpha Vantage API` `Anthropic API` `Playwright` `pytest-asyncio` `GitHub Actions`

### [EncryptionClientLib](https://github.com/mhightower/EncryptionClientLib)

A PHP encryption client library built for enterprise key management integration. Implements a high-availability key manager client (primary/secondary failover via TLS) against an external Alliance Key Manager, keeping cryptographic keys fully out of application code and off-disk. Enforces key instance tracking alongside ciphertext to support proper key rotation without data loss. OpenSSL-backed encryption/decryption layer with a clean interface that decouples key lifecycle from business logic — the same pattern used in regulated environments handling PII and payment data.

`PHP` `OpenSSL` `TLS` `PHPUnit` `Codeception`

---

## 🛠 Tech Stack

| Area | Tools |
|---|---|
| **Languages** | Python, Go, PHP, JavaScript, Bash |
| **AI Coding Tools** | Claude Code, GitHub Copilot, Gemini CLI, Anthropic API, MCP |
| **DevOps & Automation** | Jenkins, GitHub Actions, GitLab CI, Ansible, SaltStack, Cisco NSO |
| **Cloud & Infra** | AWS CloudWatch, Azure (AZ-103), VMware |
| **Containers** | Docker, Docker Compose, Podman |
| **Databases** | PostgreSQL, MySQL, Redis |
| **Observability** | OpenTelemetry, Prometheus, Grafana, New Relic, ELK Stack |

---

## 📜 Certifications

| Certification | Issuer | Year |
|---|---|---|
| Model Context Protocol: Advanced Topics | Anthropic | 2026 |
| Introduction to Model Context Protocol | Anthropic | 2026 |
| Claude Code in Action | Anthropic | 2026 |
| Building with the Claude API | Anthropic | 2026 |
| AI Fluency: Framework & Foundations | Anthropic | 2026 |
| AZ-103 Microsoft Azure Administrator | Microsoft | 2019 |
| AZ-900 Microsoft Azure Fundamentals | Microsoft | 2019 |

---

## 📬 Get in Touch

- 💼 [linkedin.com/in/mhightower](https://linkedin.com/in/mhightower)
- 📧 marcus.hightower@gmail.com
