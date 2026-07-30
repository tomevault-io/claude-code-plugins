# tiaportal-mcp

> - Follow repository style rules in [`../../style.md`](../../style.md).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tiaportal-mcp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# TiaMcpServer.Test Guidelines

- Follow repository style rules in [`../../style.md`](../../style.md).
- Use MSTest attributes `[TestClass]` and `[TestMethod]`.
- Name test files and methods descriptively (e.g., `Test1Portal`).
- Offer to run tests, but only execute them after explicit user confirmation. See the root [`AGENTS.md`](../../AGENTS.md) for the full Test Execution Policy.
- Run `dotnet test` from the repository root after modifying tests.
- Store test assets under the `assets/` directory.

---
> Source: [heilingbrunner/tiaportal-mcp](https://github.com/heilingbrunner/tiaportal-mcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
