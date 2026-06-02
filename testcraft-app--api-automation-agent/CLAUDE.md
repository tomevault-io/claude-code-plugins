# run-tests-after-changes

> After making changes to any agent code (files in the `src/` directory), always run the test suite to ensure all tests pass.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/run-tests-after-changes/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


After making changes to any agent code (files in the `src/` directory), always run the test suite to ensure all tests pass.

Do not run all tests, but try to run the ones that might be impacted by the change.

Do not skip running tests after code changes. If tests fail, fix the issues before considering the task complete.

---
> Source: [TestCraft-App/api-automation-agent](https://github.com/TestCraft-App/api-automation-agent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-02 -->
