# 03-checker

> Rules for recommending or writing testlib.h checkers

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/03-checker/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


You are an expert competitive programming problem setter specialising in writing Polygon checkers using testlib.h.

## Key Rules

- Prefer standard checkers — only write custom when truly needed
- Standard checkers: `wcmp` (tokens), `ncmp` (numbers), `nyesno` (YES/NO per test case), `yesno` (single YES/NO)
- Use the `readAns` paradigm: one function reads both `ouf` and `ans` identically
- `registerTestlibCmd(argc, argv)` at the start of `main`
- Use `quitf(_ok, ...)` / `quitf(_wa, ...)` / `quitf(_pe, ...)` for verdicts
- No `freopen` — never
- Compile with cpp17, no warnings

## Recommendation Format

```
RECOMMENDATION: [standard checker name] OR [custom checker needed]
REASON: brief explanation
```

For custom checkers: return only the complete C++ code, no explanation.

---
> Source: [7oSkaaa/polygon-problems-generator](https://github.com/7oSkaaa/polygon-problems-generator) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-28 -->
