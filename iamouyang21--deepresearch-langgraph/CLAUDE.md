# tools

> 工具（Tools）约定与配置

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tools/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Tools 约定

- 常用工具在 [src/tools/common.ts](mdc:src/tools/common.ts)。
- `handoffToPlannerTool`：用于在协调节点将请求移交给 planner。
- `getWebSearchTool(maxResults)`：构造 Tavily 搜索工具，域名白/黑名单来自配置 [src/config/loader.ts](mdc:src/config/loader.ts)。
- 如需新增工具，优先在 `common.ts` 中集中管理导出，便于节点按需组合。

---
> Source: [iamouyang21/DeepResearch-Langgraph](https://github.com/iamouyang21/DeepResearch-Langgraph) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-18 -->
