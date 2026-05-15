# test-rules

> rules for running tests

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/test-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Environment Variables

When you run tests that require connecting to Snowflake manually, define environment variable:
PARAMETER_PATH=/[project_location]/parameters.json

Where [project_location] is the path to your project root.
Tests won't run without this variable.

There are also utils for testing - read the project README.md

---
> Source: [snowflakedb/universal-driver](https://github.com/snowflakedb/universal-driver) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-14 -->
