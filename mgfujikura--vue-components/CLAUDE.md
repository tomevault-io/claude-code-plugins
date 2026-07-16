# composables

> Composable（src/composable）の実装規約

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/composables/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Composable

- DOM 参照の取得・監視・クリーンアップを内部で完結させる。
- オプションベースの柔軟な API を提供する。
- UI 側に sentinel 要素や observer 設定を要求しない。
- 命名は `useXxx` とし、責務を 1 つに絞る。

---
> Source: [mgfujikura/vue-components](https://github.com/mgfujikura/vue-components) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-16 -->
