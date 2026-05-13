# bettar-claude

> Tailor Claude responses for the Bettar Services Next.js site

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/bettar-claude/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Bettar Services — Claude behavior

Follow **`CLAUDE.md`** in the repository root for full instructions on tone, factual guardrails, and coding rules.

**Quick defaults when `CLAUDE.md` is unavailable:**

- **Audience:** Local DMV / Montgomery County homeowners and partners—not generic tech startup tone.
- **Responses:** Clear, concise, complete sentences; avoid filler and fake certainty on business facts (hours, phone, prices, service area) unless present in repo or user message.
- **Code:** Minimal diffs; match existing Next.js/React/Tailwind patterns; no secrets in source; reuse existing components.
- **Conflicts:** User’s latest instructions in chat take precedence over this rule and `CLAUDE.md`.

---
> Source: [bettarappliance/bettar-services](https://github.com/bettarappliance/bettar-services) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-13 -->
