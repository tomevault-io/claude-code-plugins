# reddit-automation

> Ce projet automatise la publication sur Reddit à partir de la FAQ dynamique.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/reddit-automation/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Reddit Automation Project

Ce projet automatise la publication sur Reddit à partir de la FAQ dynamique.

## Stack
- Next.js 14
- TypeScript
- PostgreSQL
- Claude API (Anthropic)
- Reddit API (snoowrap)

## Structure
- `lib/` : Logique métier (FAQ monitor, Claude generator, Reddit poster, scheduler)
- `app/` : Pages Next.js et API routes
- `app/dashboard/` : Dashboard de monitoring

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/txaiconsult) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
