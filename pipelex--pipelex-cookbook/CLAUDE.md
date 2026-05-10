# tdd

> Guidelines for writing test-driven development code

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tdd/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Test-Driven Development Guide

This document outlines our test-driven development (TDD) process and the tools available for testing.

## TDD Cycle

1. **Write a Test First**
[pytest.mdc](pytest.mdc)

2. **Write the Code**
   - Implement the minimum amount of code needed to pass the test
   - Follow the project's coding standards
   - Keep it simple - don't write more than needed

3. **Run Linting and Type Checking**
[coding_standards.mdc](coding_standards.mdc)

4. **Refactor if needed**
If the code needs refactoring, with the best practices [coding_standards.mdc](coding_standards.mdc)

5. **Validate tests**

Remember: The key to TDD is writing the test first and letting it drive your implementation. Always run the full test suite and quality checks before considering a feature complete.

---
> Source: [Pipelex/pipelex-cookbook](https://github.com/Pipelex/pipelex-cookbook) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
