# neowright

> Issues and PRDs are tracked in GitHub Issues for `isak102/neowright`. See `docs/agents/issue-tracker.md`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/neowright/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Agent skills

### Issue tracker

Issues and PRDs are tracked in GitHub Issues for `isak102/neowright`. See `docs/agents/issue-tracker.md`.

### Triage labels

Use the default five-label triage vocabulary: `needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`. See `docs/agents/triage-labels.md`.

### Domain docs

Use the single-context layout: root `CONTEXT.md` plus root `docs/adr/`. See `docs/agents/domain.md`.

## Repository workflow

After making Rust code changes, always run `just verify`; it must pass before considering the work complete.

---
> Source: [isak102/neowright](https://github.com/isak102/neowright) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-14 -->
