# packet-alignment-rules

> Keep packet work aligned to packet_ver 23

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/packet-alignment-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Packet Alignment Rules

- Always review `PACKET_VERSION_ALIGNMENT.md` before making packet-related decisions.
- The rebuilt client targets `packet_ver 23` for packet behavior and client-send packet alignment.
- Do not assume the decompiled client under `Ref` uses the same packet version as this rebuilt client.
- When packet version, opcode mapping, payload layout, or server expectations are in question, prefer `Ref/eAthena_src_2011` and `Ref/RunningServer` over raw client behavior from `Ref`.
- Use `Ref` for broader client behavior and implementation context, but treat packet-version-specific details as potentially different unless they match packet alignment documentation and server references.
- If the packet alignment document and reference sources disagree, call out the mismatch explicitly and follow the source matching the `packet_ver 23` target.

---
> Source: [Sziadan/open-midgard](https://github.com/Sziadan/open-midgard) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
