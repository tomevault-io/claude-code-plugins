# code-organization

> Code and file organization standards

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/code-organization/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Code Organization

- Avoid code duplication - use inheritance or composition when classes share common fields
- Keep related functionality together in modules

# File Organization

- JSON schema files should be kept in a schemas/ subdirectory within the module
- Configuration files should use YAML format
- NO example files anywhere - not in tests, not in fixtures, nowhere

---
> Source: [raw-labs/mxcp](https://github.com/raw-labs/mxcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
