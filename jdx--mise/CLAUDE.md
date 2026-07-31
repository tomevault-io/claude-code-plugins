# mise

> - `cargo build --all-features` - build the project

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mise/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


- `cargo build --all-features` - build the project
- `target/debug/mise` - run the built binary
- `mise run test:e2e [test_filename]...` - run e2e tests
- `mise run test:unit` - run unit tests
- `mise run lint` - run linting
- `mise run lint-fix` - run linting and fix issues

Don't run e2e tests by trying to execute them directly, always use `mise run test:e2e [test_filename]...`

Run `mise run lint-fix` and `git add` any lint fixes before trying to commit.

---
> Source: [jdx/mise](https://github.com/jdx/mise) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-27 -->
