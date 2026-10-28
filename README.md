# Sashido01

**Software Developer · Python & TypeScript · Backend, Automation & AI-assisted Applications**

I build practical tools and applications, from HTML5 game-generation workflows to read-only financial API integrations. My focus is on **clear architecture, reproducible development, and verifiable results**—not just code that compiles.

**What I work on:** backend services · developer tools · AI-assisted workflows · local-first applications

## Selected projects

### [YAPLIX — text ideas into HTML5 games](https://github.com/Sashido01/YAPLIX)

A team project for the **2026 IT Sprint hackathon**. I am the **lead developer and integrator**, responsible for core backend and generation workflows, architecture, and integration.

- Builds self-contained HTML5 game candidates from text prompts, with editing and version history.
- Validates generated content using static checks and sandboxed Chromium/Playwright.
- Includes local SQLite storage, offline game export, and a QR-accessible LAN Arena with persistent results.

**Stack:** TypeScript · Node.js · Hono · SQLite · Playwright · HTML5 Canvas/WebGL

**Verification:** Core local workflows have been tested; live LLM generation and all target platforms are **not** claimed as fully verified. See the [verification report](https://github.com/Sashido01/YAPLIX/blob/main/docs/submission-verification.md) and [team contributions](https://github.com/Sashido01/YAPLIX/blob/main/AUTHORS.md).

### [tinvest-devkit — developer tools for T-Invest API](https://github.com/Sashido01/tinvest-devkit)

A reusable Python toolkit for building applications with the T-Invest API while keeping the broker integration **strictly read-only**.

- Exposes application-owned models for accounts, operations, positions, portfolios, and market data.
- Preserves financial precision with `Decimal` and supports paginated data retrieval.
- Provides CLI diagnostics (`doctor`), project scaffolding (`new`), automated tests, and setup documentation.

**Stack:** Python 3.11+ · T-Invest SDK · pytest · CLI tooling

## Technical toolkit

| Area | Tools and technologies |
| --- | --- |
| Languages | Python, TypeScript, JavaScript, SQL, Bash |
| Backend & data | Node.js, Hono, REST APIs, SQLite |
| Testing | Playwright, pytest, Node.js test runner |
| Development | Linux, Git, CLI tooling, reproducible setup |
| Interactive applications | HTML5, Canvas/WebGL, browser-based interfaces |

## Engineering approach

- **Build for real use.** Usable workflows and maintainable systems over demos alone.
- **Test the actual behavior.** Keep automated checks distinct from real-device and live-service verification.
- **Respect data and permissions.** Prefer explicit boundaries, local processing, and read-only access where appropriate.
- **Document limitations.** Explain what was tested, what remains unverified, and how to reproduce the result.

**Currently learning:** DevOps/SRE practices, CI/CD, Linux operations, and reliability engineering.

## Коротко на русском

Разрабатываю прикладные инструменты на Python и TypeScript: серверные приложения, интеграции API и решения с использованием ИИ. Особое внимание уделяю тестированию, воспроизводимым сборкам и безопасности данных. В профиле представлены только публичные проекты.

---

*For implementation details, current limitations, and attribution, see the linked project repositories.*
