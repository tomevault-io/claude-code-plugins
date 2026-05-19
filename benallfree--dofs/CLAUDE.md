# start

> * fix errors without prompting

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/start/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This is a monorepo.

* fix errors without prompting
* don't ask to proceed, just go
* fix all warnings along the way without prompting
* ONLY when making changes to /packages/dofs-rust-client:
    * run `cargo build` after each change to be sure it compiles
    * run `cargo test` after each change to be sure it passes tests
* when making changes to /packages/dofs:
    * do not automatically build
    * do not automatically install packages

---
> Source: [benallfree/dofs](https://github.com/benallfree/dofs) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
