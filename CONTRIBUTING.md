# Contributing

Thank you for contributing to a **shifulegend** project.

## Before You Start
- Read the repository's `README.md` and `docs/ai/project-overview.md`.
- Read `docs/ai/mistakes.md` and `docs/ai/decision-log.md` before touching existing code.
- Check open issues and pull requests to avoid duplicate work.

## Principles
- **Modular first** — smallest sensible unit, explicit interfaces, minimal coupling.
- **Zero hard-coding** — all configurable behavior lives in config files, env vars, schemas, or databases.
- **Documentation is mandatory** — every change must update the relevant docs.
- **Timestamps** — add timestamps to doc updates and non-obvious code comments.

## Workflow
1. Fork and create a feature branch from `main`.
2. Follow the commit discipline: one small, reviewable sub-step per commit.
3. Each commit message must explain **what** changed and **why**.
4. Ensure all checks pass: lint, typecheck, tests, build.
5. Open a PR and fill in the PR template completely.

## AI Agent Collaboration
This repository uses a cross-tool AI system (Claude Code, GitHub Copilot, Google Antigravity).
All AI agents are expected to update `docs/ai/` and tool-specific instruction files proactively every session.

## Code of Conduct
Be respectful. Constructive feedback only. See `CODE_OF_CONDUCT.md`.
