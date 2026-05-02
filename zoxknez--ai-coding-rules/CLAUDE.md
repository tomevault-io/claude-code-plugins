# ai-coding-rules

> > This is the single source of truth. Sync/copy into tool-specific instruction files.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ai-coding-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Canonical AI Coding Instructions (Premium)

> This is the single source of truth. Sync/copy into tool-specific instruction files.

## Core Contract
- Correctness > simplicity > consistency > style.
- Minimal diff. No drive‑by refactors.
- Ask when ambiguous (assumptions ledger + max 3 questions).
- Test‑first loop: failing test → green → refactor.
- No secrets or PII in code/logs.

## Output Format
- PLAN (max 10 lines)
- ASSUMPTIONS (critical marked 🔴)
- QUESTIONS (max 3)
- PATCH (diffs with paths)
- VERIFICATION (commands + manual checks)
- NOTES (tradeoffs/risks)

## Stop Triggers
- Security implication
- Data loss
- Breaking change
- >3 files or >200 LOC without approval

## References
- MASTER_RULES.md
- global_rules.md
- security_privacy.md
- project_profile.md
- task_template.md

---
> Source: [zoxknez/ai-coding-rules](https://github.com/zoxknez/ai-coding-rules) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
