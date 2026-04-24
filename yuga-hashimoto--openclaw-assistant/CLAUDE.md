# openclaw-assistant

> GitHub CLI (`gh` コマンド) を使用してPRを作成すること。

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/openclaw-assistant/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Git ワークフロー

### PR作成
GitHub CLI (`gh` コマンド) を使用してPRを作成すること。

```bash
# 変更をコミット
git add <files>
git commit -m "commit message"

# ブランチをpush
git push origin <branch-name>

# ghコマンドでPR作成
gh pr create --title "PRタイトル" --body "PR本文" --base main
```

**注意:** `git` コマンドだけでなく、必ず `gh` コマンドを使ってPRを作成すること。

---
> Source: [yuga-hashimoto/openclaw-assistant](https://github.com/yuga-hashimoto/openclaw-assistant) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-21 -->
