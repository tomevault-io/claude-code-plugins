# relative-import

> не надо делать локальные импорты через относительные пути:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/relative-import/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

не надо делать локальные импорты через относительные пути:

```go
// плохо
import "../../config"

// хорошо
import "github.com/comerc/budva43/some/path/config"
```

---
> Source: [comerc/budva43](https://github.com/comerc/budva43) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-21 -->
