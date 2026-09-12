# antigravity-account-switcher

> This repository contains the Go source code for **Antigravity Account Switcher**, an in-process supervisor, quota monitor, and transparent failover reverse proxy for Google Antigravity 2.0.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/antigravity-account-switcher/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Copilot Instructions for Antigravity Account Switcher

This repository contains the Go source code for **Antigravity Account Switcher**, an in-process supervisor, quota monitor, and transparent failover reverse proxy for Google Antigravity 2.0.

Refer to `AGENTS.md` in the repository root for full project architecture, Antigravity 2.0 binary internals, and pull request requirements.

## Development Standards
- **Pure Go (Zero CGO)**: Never add Cgo dependencies or external C runtime calls. SQLite persistence uses `modernc.org/sqlite`.
- **Formatting**: Format code with `make fmt` (`gofmt -s -w .`).
- **Code Quality**: Ensure zero linter errors (`make lint`) and zero race conditions (`make test-race`).
- **Architecture**: Adhere strictly to Clean/Hexagonal Architecture boundaries in `internal/domain/`, `internal/store/`, `internal/proxy/`, `internal/launcher/`, and `internal/quota/`.
- **Git Conventions**: Use Conventional Commits (`feat:`, `fix:`, `refactor:`, `docs:`, `test:`, `chore:`).

---
> Source: [Muriel-Gasparini/antigravity-account-switcher](https://github.com/Muriel-Gasparini/antigravity-account-switcher) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-11 -->
