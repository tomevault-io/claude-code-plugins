# node-client-api

> When generating TypeScript definitions, follow this advice:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/node-client-api/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

When generating TypeScript definitions, follow this advice:

All types will go into marklogic.d.ts.

Determining the output type is difficult. You have to look at the module containing the 
implementation code and look for an "outputTransform". The implementation of that function 
should reveal what the user-facing function will return. 

Please add "runtime" tests to the test-typescript directory. These tests should do 
"smoke" tests that - critically - verify the output of each function. 

---
> Source: [marklogic/node-client-api](https://github.com/marklogic/node-client-api) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
