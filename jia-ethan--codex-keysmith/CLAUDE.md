# codex-keysmith

> 补全 `data/mechanism.yaml`，直到 `pytest -q` 通过。

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/codex-keysmith/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Cantera mechanism fixture

补全 `data/mechanism.yaml`，直到 `pytest -q` 通过。

不要修改测试或 `src/`。机制必须包含可解析的 `units`、`phases`、
`species`、`reactions`，且全文不再出现 `???`。
若本机没有 Cantera，schema 通过即为完成。

---
> Source: [Jia-Ethan/codex-keysmith](https://github.com/Jia-Ethan/codex-keysmith) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
