# mood

> Run the formatter before testing:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mood/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Verification

### Linting

Run the formatter before testing:

```shell
./gradlew fmt
```

### Testing

Run the checks relevant to the changes:

- Kotlin changes: `./gradlew test`
- Android-specific changes: `./gradlew :android:assembleDebug`
- Web-specific changes: `./gradlew :web:wasmJsBrowserDevelopmentDistribution`

---
> Source: [CharlieTap/mood](https://github.com/CharlieTap/mood) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-27 -->
