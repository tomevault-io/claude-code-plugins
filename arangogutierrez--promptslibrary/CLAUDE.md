# node

> TypeScript/JavaScript standards

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/node/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Node/TypeScript
style:strict-TS|no-any|explicit-return-types
pattern:async/await>callbacks|zod-for-validation|const>let>never-var
error:typed-errors|never-swallow-catch|Error-subclass-for-domain
test:vitest-or-jest|describe-blocks|mock-at-boundary-not-deep
security:no-eval|sanitize-user-input|env-for-secrets|CSP-headers

---
> Source: [ArangoGutierrez/promptsLibrary](https://github.com/ArangoGutierrez/promptsLibrary) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-08 -->
