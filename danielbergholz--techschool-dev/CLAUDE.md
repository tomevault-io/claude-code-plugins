# techschool-dev

> - Run `mix precommit` before declaring any code change complete.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/techschool-dev/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository instructions

- Run `mix precommit` before declaring any code change complete.
- For LiveView or other UI changes, add a relevant LiveView test and verify the final behavior with Tidewave's browser tools.
- `mix credo --strict` has known existing cleanup debt and is intentionally outside the green precommit gate. Do not hide or suppress its findings; address them when they are in scope.

---
> Source: [danielbergholz/techschool.dev](https://github.com/danielbergholz/techschool.dev) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-30 -->
