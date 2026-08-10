# maplibre-flutter-gpu

> - Write source comments in concise, natural English.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/maplibre-flutter-gpu/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Comment Style

- Write source comments in concise, natural English.
- Document stable contracts and invariants instead of implementation history, tests, or temporary compatibility details.
- Explain behavior that is not obvious from the code, including ownership, units, null results, errors, and lifecycle requirements.
- Do not merely restate names or operations visible in the code.
- Avoid em dashes, semicolons, and label-style colons in prose. Prefer complete sentences.
- Add documentation to public APIs and to private code only when its contract or purpose is not self-evident.

# Dart Style

- Leave a blank line before a `return` that follows another statement.
- Do not leave that blank line when the preceding line closes a scope or the `return` is the only statement in its scope.
- A one-line control statement still requires a blank line before a following `return`.

---
> Source: [hyshu/maplibre_flutter_gpu](https://github.com/hyshu/maplibre_flutter_gpu) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-10 -->
