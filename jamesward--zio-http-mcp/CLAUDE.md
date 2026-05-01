# zio-http-mcp

> Every code example in README.md must have a corresponding test in `McpToolSpec`. When adding or modifying a README example, add or update the matching test. The test suites in McpToolSpec are organized to mirror the README sections.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/zio-http-mcp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Guidelines

## README Examples

Every code example in README.md must have a corresponding test in `McpToolSpec`. When adding or modifying a README example, add or update the matching test. The test suites in McpToolSpec are organized to mirror the README sections.

## Testing

- Run `./sbt "testOnly *McpToolSpec*"` for unit tests
- Run `./sbt "testOnly *ConformanceSpec*"` for MCP conformance tests (requires Docker)
- Conformance tests use testcontainers with `host.testcontainers.internal` for Docker networking (rootless Docker compatible)

---
> Source: [jamesward/zio-http-mcp](https://github.com/jamesward/zio-http-mcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-27 -->
