# eternalterminal

> - To run unit tests: `pushd build; ninja && ctest --parallel; popd`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/eternalterminal/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Testing

- To run unit tests: `pushd build; ninja && ctest --parallel; popd`
- To get code coverage: `bash coverage.sh`
- Any time a new test is added, you must run cmake for cmake/ctest to recognize the new test.
- To run lint: `bash format.sh`
- It's important to run lint and unit tests after making changes to the source code.

---
> Source: [MisterTea/EternalTerminal](https://github.com/MisterTea/EternalTerminal) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
