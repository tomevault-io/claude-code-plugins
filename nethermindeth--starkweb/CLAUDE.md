# starkweb

> - When importing types, always use relative imports like `import type { Block } from '../../types/block.js'`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/starkweb/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Cursor AI Rules

## Import Rules
- When importing types, always use relative imports like `import type { Block } from '../../types/block.js'` 
- Never use absolute imports like `import type { Block } from 'src/types/block.js'`

## Code Generation Rules
- When generating or modifying imports for types, ensure paths are relative to the file location
- Convert any instances of `src/types/block.js` to the appropriate relative path (usually `../../types/block.js` in decorators) 

---
> Source: [NethermindEth/starkweb](https://github.com/NethermindEth/starkweb) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-05 -->
