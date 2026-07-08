# boston-pie-academy

> These rules apply only to this repository: `/Users/vladislavzilber/boston-pie-academy`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/boston-pie-academy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Boston Pie Academy Agent Rules

These rules apply only to this repository: `/Users/vladislavzilber/boston-pie-academy`.

## Scope

- Work only inside this repo.
- Never touch BPI Ops, TrueOps, BPI Connect, BPI Labels, or any folder outside this repo.
- Do not edit application logic unless the user explicitly asks for a code change.

## Change Discipline

- Make the smallest safe change that satisfies the request.
- Inspect the relevant routes, templates, and models before editing.
- Preserve existing auth behavior, role permissions, user progress, and MIT/STS training data.
- Do not commit or push unless explicitly asked.

## Verification

- After edits, run Python compile checks for the changed Python surface when applicable.
- Prefer targeted checks that match the files changed.
- If checks cannot be run, explain why.

## Final Response

Summarize:

- Changed files.
- Checks run.
- Known risks or follow-up concerns.

---
> Source: [zilbervlad/boston-pie-academy](https://github.com/zilbervlad/boston-pie-academy) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-08 -->
