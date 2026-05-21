# test-practices

> implement unit test

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/test-practices/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Unit Test Writing Best Practices

When working on unit tests, do the following:
1. Output "!!!Implementing Unit Test Cases!!!".
2. Make sure to cover the following test cases:
    1. Positive Test Cases
    2. Negative Test Cases
    3. Boundary Test Cases
    4. Exception Test Cases
3. Use Arrange, Act and Assert format. 
4. Implement using SOLID principles.
5. Only edit test files.

You MUST iterate implementing and fixing unit tests until all the following criteria are met:
1. At least 80% code coverage.
2. All unit test cases passes.
3. Execute `dotnet test` and it yields no compile error.

---
> Source: [aevatarAI/aevatar-station](https://github.com/aevatarAI/aevatar-station) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
