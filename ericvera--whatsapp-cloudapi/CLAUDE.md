# tests-commands

> Use yarn instead of npm for all test commands

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tests-commands/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Rules

## Use yarn for test commands
When running test commands, always use `yarn` instead of `npm`.

# Examples

## Valid
```bash
yarn test
cd functions && yarn test
yarn test src/utils/usage/updateDailyUsage.test.ts
```

## Invalid
```bash
npm test
cd functions && npm test
npm test src/utils/usage/updateDailyUsage.test.ts
```

---
> Source: [ericvera/whatsapp-cloudapi](https://github.com/ericvera/whatsapp-cloudapi) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
