# claude-web

> 本仓库的项目说明、架构和踩坑记录都在 [CLAUDE.md](CLAUDE.md)。开始任何改动前先完整读一遍它。

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/claude-web/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

本仓库的项目说明、架构和踩坑记录都在 [CLAUDE.md](CLAUDE.md)。开始任何改动前先完整读一遍它。

最常用的命令：

```
npm install
npm run typecheck      # server + web + desktop
npm test               # vitest（server + web）
npm run build:all
npm run e2e            # 用临时 HOME 起 server，跑不花 token 的 WebSocket 端到端检查
```

---
> Source: [ypyik0669/claude-web](https://github.com/ypyik0669/claude-web) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-01 -->
