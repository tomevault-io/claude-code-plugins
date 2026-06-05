# testing

> - When generating a test file, inherit from ActiveSupport::TestCase.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Testing

- When generating a test file, inherit from ActiveSupport::TestCase.
- The test file should ONLY require "test_helper". All other files are automatically required.
- The test class name should be declared in a single line and NOT nested under a module.
- NEVER use mocks or stubs.
- DO NOT create a setup method with instance variables unless clearly specified.

---
> Source: [luizpvas/explicit](https://github.com/luizpvas/explicit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-05 -->
