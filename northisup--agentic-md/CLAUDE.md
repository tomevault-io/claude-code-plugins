# agentic-md

> Testing

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agentic-md/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


- TDD: write failing test first, then implement
- Unit tests are inline (`#[cfg(test)] mod tests`) in each module
- Integration tests in `tests/integration/` exercise the full `run()` function
- Use `tempfile::tempdir()` for filesystem tests — never write to the real project dir in tests
- Test both the happy path and edge cases (empty input, missing files, conflicts)

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/NorthIsUp) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-13 -->
