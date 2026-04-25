# domeo-server

> После сброса/очистки БД миграции применяет сам пользователь — агент не запускает dotnet ef.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/domeo-server/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# База данных Domeo (миграции)

- После **очистки / сброса БД** (`reset_database.sql`, `reset-db.ps1`, DROP схем и т.п.) **не запускать** автоматически `dotnet ef database update` и не предлагать это как обязательный следующий шаг в ответе, если пользователь явно не попросил.
- **Миграции на БД применяет сам пользователь** (вручную или через старт сервисов — как у него принято). Не выполнять массовый `database update` по всем сервисам от имени агента без явной просьбы.
- Кратко можно напомнить: «структуру восстановите своими командами миграций», без пошагового навязывания.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/kalmykovgroup) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
