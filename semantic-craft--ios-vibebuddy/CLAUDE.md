# ios-vibebuddy

> Agent-facing configuration for the iOS-vibebuddy repo.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ios-vibebuddy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

Agent-facing configuration for the iOS-vibebuddy repo.

## Agent skills

Per-repo configuration consumed by the engineering skills (`to-issues`, `to-prd`,
`triage`, `diagnose`, `tdd`, `improve-codebase-architecture`, `zoom-out`).

### Issue tracker

Issues and PRDs live as **local markdown** under `.scratch/<feature>/` in this repo
(not GitHub Issues). See `docs/agents/issue-tracker.md`.

### Triage labels

Five canonical triage roles use their **default strings** (`needs-triage`,
`needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`), recorded as a
`Status:` line in each issue file. See `docs/agents/triage-labels.md`.

### Domain docs

**Single-context** layout — one `CONTEXT.md` + `docs/adr/` at the repo root.
See `docs/agents/domain.md`.

---
> Source: [semantic-craft/iOS-vibebuddy](https://github.com/semantic-craft/iOS-vibebuddy) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-08 -->
