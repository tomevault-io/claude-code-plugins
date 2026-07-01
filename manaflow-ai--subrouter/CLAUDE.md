# subrouter

> Go service for routing AI coding-agent traffic across subscription accounts and API keys.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/subrouter/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# subrouter

Go service for routing AI coding-agent traffic across subscription accounts and API keys.

## Development

- Use `go test ./...` before handing off changes.
- Keep credential handling read-only unless a command explicitly delegates to the upstream account manager, such as `cx`.
- Do not log access tokens, refresh tokens, API keys, request bodies, or complete Authorization headers.
- Prefer standard-library networking primitives unless a dependency removes meaningful complexity.

---
> Source: [manaflow-ai/subrouter](https://github.com/manaflow-ai/subrouter) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
