# bafi

> - Format Go code with `gofmt -w` before committing.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/bafi/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS Instructions

## Development
- Format Go code with `gofmt -w` before committing.
- Run `go test ./...` and ensure all tests pass.

## Documentation
- If you modify files under `docs/` or `mkdocs.yml`, run `mkdocs build` to check that the documentation builds successfully (if mkdocs is available).

---
> Source: [mmalcek/bafi](https://github.com/mmalcek/bafi) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
