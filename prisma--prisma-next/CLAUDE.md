# omit-should-in-tests

> Enforce omitting "should" in test descriptions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/omit-should-in-tests/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


When writing unit tests, omit the word "should" in test descriptions. Write concise, direct descriptions instead.

Good examples:
- it("equals 1")
- it("returns the correct value")
- it("handles null input")
- it("throws an error when invalid")

Avoid:
- it("should equal 1")
- it("should return the correct value")
- it("should handle null input")
- it("should throw an error when invalid")

This makes test descriptions more concise and easier to read.

---
> Source: [prisma/prisma-next](https://github.com/prisma/prisma-next) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
