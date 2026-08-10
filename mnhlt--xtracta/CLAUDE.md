# testing-cheatsheet

> Testing checklist & snippets

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/testing-cheatsheet/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Quick reference for high‑impact tests:

1. **XPath parser fuzz**: generate 1 000 random yet valid XPath strings and assert no throw.  
2. **DOM highlight delta**: diff decoration IDs before & after evaluate.  
3. **Backend load**: k6 script `load-test.js` targeting 50 rps, 10 MB docs.  
4. **Lighthouse performance**: budget ‑‑performance ≥ 90 for `/#/` route.  

---
> Source: [mnhlt/Xtracta](https://github.com/mnhlt/Xtracta) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-10 -->
