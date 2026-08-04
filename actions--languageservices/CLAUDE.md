# languageservices

> npm -w @actions/expressions test

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/languageservices/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agents

## Build

```
npx lerna run build
```

## Test

```
npm -w @actions/expressions test
npm -w @actions/workflow-parser test
npm -w @actions/languageservice test
```

## Format

Always run formatting before committing:

```
npx prettier --write <changed files>
```

Verify with:

```
npm run format-check -ws
```

## Feature flags

Feature flags are defined in `expressions/src/features.ts` (`ExperimentalFeatures` interface + `allFeatureKeys` array). They are plumbed through `ConvertOptions`, `CompletionConfig`, `ValidationConfig`, and `initializationOptions`. When a feature graduates to stable, remove its flag and make the behavior unconditional.

---
> Source: [actions/languageservices](https://github.com/actions/languageservices) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
