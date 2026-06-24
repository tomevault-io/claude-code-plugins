# jumusic-lx

> - 当用户确认“开工”且分支工作完成后，默认流程为：**先合并回 `main`，再推送远端**。

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/jumusic-lx/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# 仓库级默认协作约定

- 当用户确认“开工”且分支工作完成后，默认流程为：**先合并回 `main`，再推送远端**。
- 对于上述“合并回 `main` + 推送远端”的默认流程，除非用户明确要求更换流程，否则**不要再次重复询问**。
- 如 `main` 工作区存在未提交改动，仍应优先使用单独的干净 worktree 完成合并与推送，避免打扰现有本地状态。

---
> Source: [ifwlzs/juMusic_lx](https://github.com/ifwlzs/juMusic_lx) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-24 -->
