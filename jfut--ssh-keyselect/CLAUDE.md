# ssh-keyselect

> - `README.md` is the canonical description of user-visible CLI commands, output, configuration, and security guidance. Keep it focused on information users need for normal use.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ssh-keyselect/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository instructions

- `README.md` is the canonical description of user-visible CLI commands, output, configuration, and security guidance. Keep it focused on information users need for normal use.
- Put package architecture, implementation details, development workflows, and release procedures in `docs/dev.md`.
- Document internal safeguards such as connection caps, frame deadlines, request queues, overload handling, and connection cleanup in `docs/dev.md`, even when they serve a security purpose. Do not put these implementation details in `README.md`.
- Prefer tests that exercise a real boundary or user-visible guarantee. Avoid tests that reproduce library behavior, validate mocks, duplicate another test's coverage, or lock down incidental implementation details.
- Use `just test` to run the default and GUI-tagged suites. Use `just deps-credits` after dependency or target-platform changes.

---
> Source: [jfut/ssh-keyselect](https://github.com/jfut/ssh-keyselect) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-06 -->
