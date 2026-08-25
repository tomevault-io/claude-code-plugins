# dsh-mattpocock-skills-deck

> This file gives an agent working in this repo the context it needs to operate well.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/dsh-mattpocock-skills-deck/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions

This file gives an agent working in this repo the context it needs to operate well.

## Agent skills

### Issue tracker

Issues live as GitHub issues, driven through the `gh` CLI. See `docs/agents/issue-tracker.md`.

### Triage labels

Five canonical triage roles map to this repo's labels; the mandatory label set is `bug` / `needs-triage` / `wayfinder:grilling`. See `docs/agents/triage-labels.md`.

### Domain docs

Single-context layout — root `CONTEXT.md` plus `docs/adr/`. See `docs/agents/domain.md`.

---
> Source: [FeatherHunter/dsh-mattpocock-skills-deck](https://github.com/FeatherHunter/dsh-mattpocock-skills-deck) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-23 -->
