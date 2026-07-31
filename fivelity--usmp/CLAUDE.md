# 00-technologies-frameworks

> Absolute requirements for core technologies.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/00-technologies-frameworks/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# 00-technologies-frameworks

## Core Technologies and Frameworks

STRICT REQUIREMENT:
- Frontend Framework: SvelteKit, specifically Svelte 5 with Runes.
- Frontend Styling: Tailwind CSS v4+ (only use Tailwind utility classes or custom CSS extensions defined within `src/app.css`).
- Frontend Icons: Prefer `lucide-svelte`, fallback to `Font Awesome`, `Phosphor Icons`, or inline SVG for game-specific icons.
- Backend Framework: FastAPI (Python).
- Hardware Monitoring: Use the `HardwareMonitor` python library (`LibreHardwareMonitorlib` wrapper) for sensor data acquisition.
- Real-time Communication: WebSockets for live data updates.
- Backend Configuration: `python-dotenv`.
- Package Manager: `pnpm` for frontend development.

---
> Source: [fivelity/usmp](https://github.com/fivelity/usmp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-31 -->
