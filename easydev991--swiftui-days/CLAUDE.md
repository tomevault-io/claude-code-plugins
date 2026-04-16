# swiftui-days

> Пользовательские ключи Environment и их назначение

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/swiftui-days/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


## Пользовательские ключи Environment

- Для кросс-иерархических значений, не требующих наблюдаемости, используем `EnvironmentKeys/`.
- Пример: `currentDate` — источник истины для расчётов, связанных с датой.

Определение ключа (фрагмент `EnvironmentKeys/CurrentDateEnvironmentKey.swift`):
@SwiftUI-Days/EnvironmentKeys/CurrentDateEnvironmentKey.swift

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/easydev991)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/easydev991)
<!-- tomevault:4.0:claude_md:2026-04-09 -->
