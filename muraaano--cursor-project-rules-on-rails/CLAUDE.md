# cursor-project-rules-on-rails

> - RailsのI18nを使用して多言語対応を実装する

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cursor-project-rules-on-rails/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# 多言語対応規約

## 基本

- RailsのI18nを使用して多言語対応を実装する
- 言語ファイルは `config/locales/` 配下に配置する
- enumの翻訳はenum_helpを使い、`{column_name}_i18n`で呼び出すこと
  - 例: `thing.hoge_type_i18n`
- 翻訳は以下のように `ja.enums.{model_name}.{enum_name}` の形式で定義する
```
ja:
  enums:
    thing:
      hoge_type:
          a: エー
          b: ビー
```

## エラーメッセージの定義

- デフォルトのエラーメッセージは `config/locales/defaults/ja.yml` に定義する
- モデル固有のエラーメッセージは `config/locales/models/` 配下に配置する

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/muraaano) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-15 -->
