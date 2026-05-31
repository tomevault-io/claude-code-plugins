# mitmwall

> mitmwall is a transparent outbound firewall for Ubuntu. `systemd` runs `mitmweb`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mitmwall/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

mitmwall is a transparent outbound firewall for Ubuntu. `systemd` runs `mitmweb`
as the dedicated `mitmwall` user, `iptables`/`ip6tables` redirect outbound HTTP
and HTTPS traffic to the local transparent proxy, and `src/main.py`
loads TOML files in `/etc/mitmwall/rules.d` to allow or block requests by
hostname.
Non-proxy users can only make DNS queries and proxied web requests; the proxy
user is allowed to connect upstream.

Ensure all python functions, classes etc. have doc comments.

Ensure valid types by running `basedpyright`

Never use any pypi packages. Only use stdlib.

After any changes run `./test.sh` and `./integration_tests.sh`

`tests/integration/integration-test-rules.toml` is installed during integration tests.

See logs with:

sudo journalctl -u mitmwall --no-pager

---
> Source: [esamattis/mitmwall](https://github.com/esamattis/mitmwall) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-31 -->
