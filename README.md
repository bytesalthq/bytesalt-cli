<p align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://bytesalt.com/docs/logo-light.svg">
    <source media="(prefers-color-scheme: dark)" srcset="https://bytesalt.com/docs/logo-dark.svg">
    <img src="https://bytesalt.com/docs/logo-light.svg" alt="Bytesalt logo" width="220">
  </picture>
</p>

# Bytesalt - Your AI QA teammate

**Weeks of testing, done in minutes.** 

> **Status:** Research Preview

Bytesalt is your **AI QA teammate** that reduces weeks of human testing to minutes. It complements your existing deterministic scripts (like Playwright and Selenium) by finding critical real-world issues in your application that instruction-based tests aren't designed for.

→ **[bytesalt.com](https://bytesalt.com)** · [Docs](https://bytesalt.com/docs) · [Quick Start](https://bytesalt.com/docs/quick-start)

---

## Overview

Most testing suites rely on an **Instruction Layer** — scripts that handle the strict validation of known paths. Bytesalt provides the **Judgement Layer**, using parallel AI agents to explore the unknown and evaluate your application through multiple specialized lenses, including:

- **UX & Visual**: Visual regressions, high-friction user flows, and cross-browser or mobile device bugs.
- **Security Audit**: OWASP vulnerabilities and data leaks.
- **Accessibility**: Continuous WCAG 2.1 auditing.
- **QA & Regression**: Complex workflows and logic bugs.

Simply provide a plain-English goal — e.g., `"Test the checkout flow"` — and the agents will explore your application to uncover the types of edge cases and regressions that deterministic scripts miss.

---

## Install

**macOS / Linux / WSL**
```sh
curl -fsSL https://bytesalt.com/install.sh | sh
```

**Windows (PowerShell)**
```powershell
irm https://bytesalt.com/install.ps1 | iex
```

---

## Quick Start

```sh
# Run your first test
bytesalt start "Test https://www.craigslist.org for usability on an iPhone. Check only above the fold. Report a single issue and stop. Do not explore."
```

Bytesalt distributes the job across parallel agents and provides a detailed report including the identified issue, its cause, impact, and a suggested fix.

---

## How it works

**1. Run the test** — Trigger tests via CLI or CI/CD using plain-English goals; no test cases required.

**2. Parallel execution** — The task is distributed across parallel AI agents that simulate real user interactions simultaneously.

**3. Actionable reports** — Receive technical reports containing what broke, why it broke, and how to fix it.

---

## Key capabilities

- **Judgement Layer** — Agents explore the application dynamically to find edge cases that scripted tests never reach.
- **Autonomous Adaptation** — Agents adapt as the product evolves, reducing the need for selector maintenance.
- **Platform Agnostic** — Supports web applications, backend APIs, and distributed systems.
- **Private Tunneling** — Securely test applications on `localhost` or staging without firewall changes.
- **Elastic Scale** — Jobs scale automatically across a fleet of parallel workers.

---

## CI/CD integration

Bytesalt can be integrated into any CI/CD platform that executes shell commands.

- [CI/CD integration docs](https://bytesalt.com/docs/ci-cd-integration)
- [CI/CD examples repository](https://github.com/bytesalthq/bytesalt-examples)

---

## Documentation

- [Quick Start](https://bytesalt.com/docs/quick-start)
- [Core Concepts](https://bytesalt.com/docs)
- [Private Tunneling](https://bytesalt.com/docs/core-concepts/tunnel)
- [Security & Privacy](https://bytesalt.com/docs/security-and-privacy)
- [CI/CD Integration](https://bytesalt.com/docs)

---

## Status

Bytesalt is currently in **Research Preview**. Feedback is welcome — open an issue or reach out via [bytesalt.com/contact](https://bytesalt.com/contact).
