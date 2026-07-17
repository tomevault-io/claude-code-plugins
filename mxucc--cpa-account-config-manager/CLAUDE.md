# cpa-account-config-manager

> Standalone CLIProxyAPI native plugin for safe account configuration listing and batch edits.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cpa-account-config-manager/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

Standalone CLIProxyAPI native plugin for safe account configuration listing and batch edits.

## Commands

```bash
gofmt -w .
go test ./...
make build
make verify
```

## Conventions

- Keep the CGO ABI bridge thin; business logic belongs under `internal/` and must be testable without loading CLIProxyAPI.
- Treat Management Keys, Auth JSON, tokens, cookies, API keys, proxy credentials, and header values as secrets.
- Never persist or log secrets. Public API models must be explicitly allow-listed and redacted.
- Plugin Management routes are exact paths. Do not use dynamic path parameters.
- Resource routes serve static UI only. Privileged data and writes belong behind authenticated Management routes.
- Comments and new Markdown documentation are English unless a language-specific file is explicitly created.
- Use contextual errors and bounded concurrency. Do not panic in request or job paths.

---
> Source: [Mxucc/cpa-account-config-manager](https://github.com/Mxucc/cpa-account-config-manager) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-17 -->
