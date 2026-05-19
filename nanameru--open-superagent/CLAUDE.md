# git-worktree

> git branch ai-task-$i main

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/git-worktree/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

5個同時にワークツリー作成できるコマンド
"""
for i in {1..5}; do
  git branch ai-task-$i main
  git worktree add ../ai-task-$i ai-task-$i
done
"""

npm run dev同時起動するコマンド
"""
for i in {1..5}; do
  port=$((3000 + i))
  (cd ../ai-task-$i && npm run dev -- --port=$port) &
done
wait
"""

---
> Source: [nanameru/Open_SuperAgent](https://github.com/nanameru/Open_SuperAgent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
