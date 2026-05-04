# oh-my-antigravity

> These rules apply to this workspace when using Antigravity.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/oh-my-antigravity/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# oh-my-antigravity  - Project Rules (Antigravity)

These rules apply to this workspace when using Antigravity.

## Security
- Never hardcode secrets (API keys, tokens, passwords). Use environment variables.
- If a request includes secrets, ask for a safer alternative before proceeding.

## Code Hygiene
- Avoid `console.log` in production code; use a logger or remove before commit.
- Prefer deterministic output in scripts and tests.

## Testing
- When creating new source files, suggest tests and offer `/tdd`.
- If behavior changes, update or add tests accordingly.

## Quality Workflows
- Use `/format` for Prettier formatting.
- Use `/lint` for ESLint checks.
- Use `/typecheck` for TypeScript checks.

## Antigravity Constraints
- Hooks are not supported. Use skills, workflows, and these rules instead.

---
> Source: [materialofair/oh-my-antigravity](https://github.com/materialofair/oh-my-antigravity) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
