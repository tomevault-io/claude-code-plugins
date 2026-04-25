# backquant

> 当改动涉及 Jupyter 默认配置，或 `backtest` 镜像内的 Python 依赖时，按最小范围处理：

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/backquant/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# BackQuant Agent Notes

## Docker Compose Change Scope

当改动涉及 Jupyter 默认配置，或 `backtest` 镜像内的 Python 依赖时，按最小范围处理：

- 只重建 `backend` 和 `jupyter`
- 只重启 `backend` 和 `jupyter`
- 不要顺带重建或重启 `frontend`、`mariadb` 等无关服务

推荐命令：

```bash
docker compose build backend jupyter
docker compose up -d --no-deps backend jupyter
```

---
> Source: [bloom8262/backquant](https://github.com/bloom8262/backquant) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-22 -->
