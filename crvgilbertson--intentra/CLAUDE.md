# intentra

> Testing requirements and strategy

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/intentra/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Testing Requirements

- Unit test pure logic:
  - Diff parsing + hunk hashing.
  - Schema validation + business validation.
  - Patch generation correctness.
- For git executor:
  - Integration tests using a temp git repo.
  - Ensure abort restores index on failure.
- Mock LLM client in tests; never hit network.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/crvgilbertson) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
