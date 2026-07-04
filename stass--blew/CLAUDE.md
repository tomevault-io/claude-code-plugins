# design

> Use always

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/design/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


When this rule loads, input: "Rule loaded: design.mdc."
The project architecture and design is described in [DESIGN.md](mdc:DESIGN.md)  Please analyze @DESIGN.md before implementing changes and make your plans based on that.

When making architectural changes, make sure to update [DESIGN.md](mdc:DESIGN.md) as well so it reflects the changes made.

Don't hedge or add fallback values -- make a reasoned decision on what values should be available and use them, throw errors when unexpected things happend instead of adding fallbacks

Don't use emojis in documentation or logs.

Whenever we update user facing functionality or behvaior update README.md to reflect the changes.

For every new change make sure tests still pass.  If we are fixing a bug -- add a new test to cover it.

---
> Source: [stass/blew](https://github.com/stass/blew) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-04 -->
