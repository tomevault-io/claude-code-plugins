# quality-gates

> Run these checks after making any changes to Dart files.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/quality-gates/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Quality Gates

Run these checks after making any changes to Dart files.

## Dart Code Quality

After modifying any `*.dart` files, use the dart tool to run the following checks:

1. Run `format` in the affected packages to format the code
2. Run `analyze` in the affected packages to check for issues
3. Fix all infos, warnings, and errors surfaced by these commands
4. Run `test` in the affected packages to ensure all tests pass
5. Fix any failing tests
6. Repeat steps 1-5 until all issues are resolved and all tests pass

---
> Source: [Peetee06/flutter-testing-concepts](https://github.com/Peetee06/flutter-testing-concepts) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
