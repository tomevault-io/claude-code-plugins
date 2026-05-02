# git-standards

> Git commit and branching standards

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/git-standards/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Git Standards

## Commits

- Format: `type(scope): description` (Conventional Commits)
- Types: `feat`, `fix`, `refactor`, `test`, `docs`, `chore`, `build`, `ci`
- Description: imperative mood, lowercase, no trailing period
- One logical change per commit

## Branches

- `feat/short-description` for features
- `fix/short-description` for bug fixes
- `chore/short-description` for maintenance

## Forbidden

- NEVER force-push to main/master
- NEVER commit .env, secrets, credentials, or API keys
- NEVER commit generated files (build output, node_modules, dist)
- NEVER rewrite published history

---
> Source: [war851/AI-Governance-Architecture](https://github.com/war851/AI-Governance-Architecture) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-24 -->
