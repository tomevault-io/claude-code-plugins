# game-context

> **注意**: "Escape from Duckov" 是独立游戏，不是 "Escape from Tarkov"

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/game-context/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# 游戏上下文

**注意**: "Escape from Duckov" 是独立游戏，不是 "Escape from Tarkov"

## 核心命名空间
- `Duckov.Modding` - 模组框架
- `TeamSoda.Duckov.Core` - 核心系统
- `TeamSoda.MiniLocalizor` - 本地化

## 主要关卡
- Prologue, Guide, Ground Zero, Storm Zone, J-Lab, Farm, Hidden Warehouse

## 模组加载
- 放在 `Duckov_Data/Mods/[ModName]/`
- 提供 `info.ini`
- 继承 `Duckov.Modding.ModBehaviour`

---
> Source: [Cyenoch/EfDEnhanced](https://github.com/Cyenoch/EfDEnhanced) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-07 -->
