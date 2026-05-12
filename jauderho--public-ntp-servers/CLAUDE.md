# public-ntp-servers

> - Scan the URL provided or GitHub Issue for any relevant information

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/public-ntp-servers/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

- Scan the URL provided or GitHub Issue for any relevant information
- Extract hostname and verify that the NTP server is reachable
- Place new entry in the proper location in ntp-sources.yml by alphabetical country
- Do not make direct changes to README.md, chrony.conf and ntp.toml. Run scripts/ntpServerConvertor.py to update after changes to ntp-sources.yml are completed
- Leverage logic from scripts/ntpUpdateSources.py to determine AS and stratum if information is not provided

---
> Source: [jauderho/public-ntp-servers](https://github.com/jauderho/public-ntp-servers) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
