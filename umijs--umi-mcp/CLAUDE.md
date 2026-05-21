# test

> Rules for test files

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/test/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Test Guidelines

- Use Vitest for testing: `pnpm test` or `vitest run`
- Use `test()` instead of `describe()` + `it()` for test cases
- Test files should be named with the `.test.ts` extension
- Place test files next to the files they test
- Use the `expect()` API for assertions
- Test coverage should be comprehensive for all tools
- Mock external dependencies like file system operations and CLI commands
- For testing MCP tools, ensure proper validation of input/output schemas

---
> Source: [umijs/umi-mcp](https://github.com/umijs/umi-mcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
