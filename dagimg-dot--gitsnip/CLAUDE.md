# gitsnip

> See [ARCHITECTURE.md](./ARCHITECTURE.md) for project structure and design.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gitsnip/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

See [ARCHITECTURE.md](./ARCHITECTURE.md) for project structure and design.

## Pre-commit

Run before any commit:

```
make test
go vet ./...
make lint
```

Fix all failures. No commit with broken tests, vet warnings or lint issues.

## Commit rules

- Never commit without explicit user approval.
- Concise messages. No co-authors, no footers, no trailers.
- Separate concerns into separate commits (refactor != chore != feature).
- Keep the diff focused — no drive-by changes in unrelated files.

---
> Source: [dagimg-dot/gitsnip](https://github.com/dagimg-dot/gitsnip) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-06 -->
