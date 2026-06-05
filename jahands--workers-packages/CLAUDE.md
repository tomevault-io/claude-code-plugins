# typescript

> TypeScript testing conventions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/typescript/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

<typescript-testing>

<title>TypeScript Testing Conventions</title>

<rules>
- Always use vitest for tests
- Unit tests: `<file>.spec.ts` (e.g., `my-file.ts` → `my-file.spec.ts`)
- Integration tests: `<feature>.test.ts`
- Error variables: use `e` or `err`, never `error`
</rules>

</typescript-testing>

---
> Source: [jahands/workers-packages](https://github.com/jahands/workers-packages) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-05 -->
