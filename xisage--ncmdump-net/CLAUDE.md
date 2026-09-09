# ncmdump-net

> Issues and specs live as GitHub issues; use the `gh` CLI. See `docs/agents/issue-tracker.md`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ncmdump-net/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Agent skills

### Issue tracker

Issues and specs live as GitHub issues; use the `gh` CLI. See `docs/agents/issue-tracker.md`.

### Triage labels

Five canonical triage roles with label strings equal to their names: `needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`. See `docs/agents/triage-labels.md`.

### Domain docs

Single-context layout — one `CONTEXT.md` + `docs/adr/` at the repo root. See `docs/agents/domain.md`.

## C# formatting

Before committing any C# change, run `dotnet format --severity info`. Then run `dotnet format --severity info --verify-no-changes` to check for remaining issues; if it reports any, fix them by hand according to its output.

---
> Source: [xiSage/ncmdump-net](https://github.com/xiSage/ncmdump-net) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-08 -->
