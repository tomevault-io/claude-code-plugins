# imports

> importing files

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/imports/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

use absolute imports (using "@/folder") over relative imports

```diff
- import { activeDocuments } from "../store/whiteboard";
+ import { activeDocuments } from "@/src/store/whiteboard";
```

never use `import *` syntax, always be explicit with imports.

---
> Source: [hzoo/henry.ink](https://github.com/hzoo/henry.ink) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
