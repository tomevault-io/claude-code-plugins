# prompts

> Prompt 文件与变量注入

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/prompts/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Prompt 约定

- 所有模板放在 [src/prompts/*.md](mdc:src/prompts)。
- 使用 `{{ VAR }}` 作为占位符；在处理时会自动转换为 LangChain 模板 `{VAR}`。
- 可用变量示例：`CURRENT_TIME`、以及 `GraphAnnotation.State` 中的字段。
- 变量注入由 [src/prompts/template.ts](mdc:src/prompts/template.ts) 负责，输出系统消息 + 现有 `state.messages`。

---
> Source: [iamouyang21/DeepResearch-Langgraph](https://github.com/iamouyang21/DeepResearch-Langgraph) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-18 -->
