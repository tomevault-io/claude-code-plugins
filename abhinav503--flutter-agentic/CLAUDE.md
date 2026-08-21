# review-code

> Apply when user asks to review, check, audit, or validate generated or modified code against project rules.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/review-code/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Run after any AI-generated code to catch rule violations before committing.

If no files were specified, ask: "Which files or feature should I review?"

Read the project rules in this order before checking anything:
1. `docs/ai-rules/conventions.md` — forbidden patterns and build rules
2. `docs/reference/architecture.md` — layer boundaries, naming, DI, error flow, testing

Then audit the specified files against every check in `docs/how-to/review-code.md`
and report a ✅/❌ checklist. Offer to fix each violation after reporting.

---
> Source: [abhinav503/flutter-agentic](https://github.com/abhinav503/flutter-agentic) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-21 -->
