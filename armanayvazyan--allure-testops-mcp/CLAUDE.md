# mcp-tools-guidelines

> Conventions for MCP tool implementation under src/tools

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mcp-tools-guidelines/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# MCP Tool Guidelines

- Keep tool schema descriptions precise and user-focused; update docs/examples when behavior changes.
- Maintain backward compatibility for tool parameters unless a breaking change is explicitly requested.
- Validate required project context (`projectId` or `projectName`) consistently with existing tool patterns.
- Return actionable, structured errors; avoid vague failure messages.
- Prefer shared API/auth helpers instead of duplicating request logic in each tool file.

## Verification

- For tool behavior changes, run relevant integration tests in `tests/integration`.
- Confirm no regressions in tool registration and names.

---
> Source: [armanayvazyan/allure-testops-mcp](https://github.com/armanayvazyan/allure-testops-mcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
