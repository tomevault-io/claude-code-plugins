# commit

> Rule for Commit message with Git

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/commit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Rule for Commit message with Git

- Follow Angular Commit Message Spec
- Format: `type(scope): subject`
  - type: feat|fix|docs|style|refactor|test|chore|perf
  - scope: Optional, the scope of the changes
  - subject: A concise description of the changes
- Keep the commit message as short as possible, changes on doc could be omited

<example>
feat(auth): add agent command
</example>

---
> Source: [umijs/umi-mcp](https://github.com/umijs/umi-mcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
