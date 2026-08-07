# aprireader

> Read `docs/product/PRODUCT_SPEC.md`, `docs/design/UI_SPEC.md`,

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/aprireader/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# ApriReader contributor rules

Read `docs/product/PRODUCT_SPEC.md`, `docs/design/UI_SPEC.md`,
`docs/architecture/ARCHITECTURE.md`, `docs/legal/DEPENDENCY_POLICY.md`, and
`ROADMAP.md` before product work.

- Implement one roadmap task at a time and preserve the approved design.
- Treat every book as untrusted input. Never execute embedded scripts or allow
  implicit external requests.
- Keep user books in place and user data local by default.
- Do not add dependencies before checking their license.
- Do not add Steamworks, telemetry, catalogs, TTS, models, or generated covers.
- Completion requires format, lint, typecheck, tests, production build, Rust
  checks, documentation, and a focused manual test.

---
> Source: [Aprilarius/ApriReader](https://github.com/Aprilarius/ApriReader) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-01 -->
