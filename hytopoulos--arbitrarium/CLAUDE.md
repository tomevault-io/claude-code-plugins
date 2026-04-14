# arbitrarium

> All debugging of frontend/ and backend/ must take place inside the docker containers.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/arbitrarium/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


All debugging of frontend/ and backend/ must take place inside the docker containers.

You may test on the backend like so:
docker compose exec backend python manage.py shell -c "from coreapp.models import Frame; frame=Frame.from_framenet(xxx);"

Always check docker logs for build or runtime errors

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/hytopoulos) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-13 -->
