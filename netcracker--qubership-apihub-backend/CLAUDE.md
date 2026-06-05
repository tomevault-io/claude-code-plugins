# backend-config-defaults

> Backend config defaults and validation conventions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/backend-config-defaults/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Backend Configuration Defaults

- **Single source of truth:** `viper.SetDefault` in `service/SystemInfoService.go` (`setDefaults`).
- **Validation:** `validate` tags on types in `config/Config.go` (mirror `BusinessParameters` size limits: `gt=0`, `lte=8796093022207` where MB→bytes conversion applies).
- **Startup:** invalid config fails fast in `SystemInfoService.Init()` via `utils.ValidateConfig`.
- **Services:** use `GetAiChatConfig()` / other getters after init; do not re-declare the same default as a Go constant.

---
> Source: [Netcracker/qubership-apihub-backend](https://github.com/Netcracker/qubership-apihub-backend) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-05 -->
