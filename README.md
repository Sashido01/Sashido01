# Sashido01

**Software development · Python & TypeScript · AI-assisted applications · Linux**

I build practical software: browser-based applications, API integrations, developer tools, and local-first workflows. My main interests are turning ideas into working products, making complex systems easier to operate, and validating software beyond a successful build.

## Featured projects

### [YAPLIX — from a text idea to an HTML5 game](https://github.com/Sashido01/YAPLIX)

A team project developed for the 2026 IT Sprint hackathon. I work as the **lead developer and integrator**, focusing on the application architecture, backend, game-generation pipeline, and integration.

- Turns text prompts into self-contained HTML5 game candidates, with an editable, versioned workflow.
- Includes static checks and browser-based validation before accepting generated games.
- Provides an offline library, game export, and a LAN Arena with QR-based access and persistent results.
- Documents verification boundaries: local tests do not constitute proof of live model generation or support on every platform.

**Stack:** TypeScript, Node.js, Hono, SQLite, Playwright, HTML5 Canvas/WebGL.

[Repository and documentation](https://github.com/Sashido01/YAPLIX) · [Team contributions](https://github.com/Sashido01/YAPLIX/blob/main/AUTHORS.md)

### [tinvest-devkit — read-only tools for T-Invest API projects](https://github.com/Sashido01/tinvest-devkit)

A Python development toolkit for integrating with the T-Invest API while keeping financial data handling explicit and broker access **read-only**.

- Provides application-level models for accounts, operations, positions, portfolios, prices, and historical candles.
- Uses `Decimal` for financial values and separates application models from SDK-specific structures.
- Includes a CLI for environment diagnostics (`doctor`) and new-project scaffolding (`new`).
- Contains automated tests and documentation for configuration, security, and development workflows.

**Stack:** Python 3.11+, T-Invest SDK, pytest, CLI tooling.

[Repository and documentation](https://github.com/Sashido01/tinvest-devkit)

## Technical focus

| Area | Technologies and practices |
| --- | --- |
| Languages | Python, TypeScript, JavaScript, SQL, Bash |
| Backend and APIs | Node.js, Hono, Python integrations, REST APIs |
| Data | SQLite, data modeling, financial-value precision |
| Testing | Playwright, pytest, Node.js test runner, browser validation |
| Development environment | Linux, Git, command-line tooling, reproducible setup |
| Frontend and interactive systems | HTML5, Canvas/WebGL, browser-based applications |

## How I approach development

- **Build for real use:** prioritize usable workflows, clear interfaces, and maintainability.
- **Verify what works:** distinguish automated test results from real-world and platform-specific testing.
- **Respect boundaries:** use explicit permissions, local data handling, and read-only integrations where appropriate.
- **Document decisions:** make setup, architecture, limitations, and recovery steps understandable.

I am also developing my knowledge of **DevOps/SRE practices**, including Linux operations, CI/CD, and reliability engineering.

## About me · Коротко на русском

Разрабатываю прикладные инструменты на Python и TypeScript, экспериментирую с ИИ-генерацией программ и уделяю внимание тестированию, воспроизводимой сборке и безопасности данных. В открытом портфолио представлены только публичные проекты; другие работы остаются приватными.

---

**Explore the repositories above for source code, documentation, and current project limitations.**
