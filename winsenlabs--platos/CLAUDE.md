# executing-commands

> how to run commands in the monorepo

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/executing-commands/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Almost all commands in the monorepo should be executed when `pnpm run ...` from the root of the monorepo. For example, running tests for the `@internal/run-engine` internal package:

```
pnpm run dev --filter webapp
```

But often, when running tests, it's better to `cd` into the directory and then run tests:

```
cd apps/webapp
pnpm run test --run
```

This way you can run for a single file easily:

```
cd internal-packages/run-engine
pnpm run test ./src/engine/tests/ttl.test.ts --run
```

---
> Source: [winsenlabs/platos](https://github.com/winsenlabs/platos) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-07 -->
