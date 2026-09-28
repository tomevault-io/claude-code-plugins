# memhogs-android

> Kotlin + Compose app that ranks Android apps by memory (PSS) using a Shizuku shell.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/memhogs-android/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# memhogs for Android

Kotlin + Compose app that ranks Android apps by memory (PSS) using a Shizuku shell.

- Before moving code or adding a file, read `ARCHITECTURE.md`. It covers packages, dependency direction, and the reasons behind the design.
- Before writing code, read `CONTRIBUTING.md#code-standards`. It covers comments, errors, the privileged shell, strings, motion, palette, and dependencies.
- Done means this passes: `./gradlew ktlintCheck lintDebug testDebugUnitTest assembleDebug`. Run `./gradlew ktlintFormat` first.
- New pure logic gets a JVM unit test in `app/src/test`, written before the implementation.
- `keystore.properties` and `*.jks` hold release signing secrets. Read `RELEASING.md` before touching signing or versions.

---
> Source: [cicerothoma/memhogs-android](https://github.com/cicerothoma/memhogs-android) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-27 -->
