# weftcut

> Project glossary and domain vocabulary live in [`CONTEXT.md`](CONTEXT.md);

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/weftcut/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# WeftCut — agent instructions

Project glossary and domain vocabulary live in [`CONTEXT.md`](CONTEXT.md);
architectural decisions in [`docs/adr/`](docs/adr/).

## Agent skills

### Issue tracker

Issues and specs live as markdown files under `.scratch/<feature>/`. See `docs/agents/issue-tracker.md`.

### Domain docs

Single-context — one `CONTEXT.md` + `docs/adr/` at the repo root. See `docs/agents/domain.md`.

### Testing

Tests are grouped by runner, not one directory: colocated Vitest unit tests in `src/`, Rust tests in `native/`, Playwright E2E in `apps/desktop/e2e/`. For the full layout map and run commands, see `docs/agents/testing.md`.

---
> Source: [WeftCut/WeftCut](https://github.com/WeftCut/WeftCut) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
