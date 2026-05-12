# wheat

> **Question:** nonexistent

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/wheat/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Wheat Research Sprint

**Question:** nonexistent

**Audience:** engineers

**Constraints:**
- (none specified)

**Done looks like:** Decision-ready brief with evidence

## Claims System

All findings are tracked as typed claims in `claims.json`. Claim types: constraint, factual, estimate, risk, recommendation, feedback. Evidence tiers (low to high): stated, web, documented, tested, production.

## Key Commands

- `wheat init` — bootstrap a research sprint
- `wheat compile` — validate and compile claims
- `wheat status` — sprint health dashboard
- `wheat search <query>` — search claims
- `wheat add-claim` — add a new claim
- `wheat resolve <id>` — resolve a conflicting claim

---
> Source: [grainulation/wheat](https://github.com/grainulation/wheat) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-09 -->
