# do-update-tests-after-bugfixing

> When the bug was discovered, you performed and investigation anf fix, ask yourself - "why our current test(s) was not able to find it?"

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/do-update-tests-after-bugfixing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

When the bug was discovered, you performed and investigation anf fix, ask yourself - "why our current test(s) was not able to find it?"
If there is no test for that part of functionality - time to create it.
If there are test(s) for that part of functionality - extend it to prove that the bug does not exist anymore.
When completing the fix - run the test to prove that bug does not exist.

---
> Source: [FeatureFactory-io/mimir](https://github.com/FeatureFactory-io/mimir) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-25 -->
