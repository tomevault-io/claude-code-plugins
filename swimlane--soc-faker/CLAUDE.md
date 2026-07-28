# soc-faker

> This documentation provides details about the data that can be faked for an Agent.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/soc-faker/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent

This documentation provides details about the data that can be faked for an Agent.

To retrieve data about a fake Agent you can do the following:


```python
from socfaker import SocFaker

sc = SocFaker()

print(sc.agent.ephermeral_id)
print(sc.agent.id)
print(sc.agent.type)
print(sc.agent.name)
print(sc.agent.version)
```

## Agent Class

```eval_rst
.. automodule:: socfaker.agent
   :members:
   :undoc-members:
```

---
> Source: [swimlane/soc-faker](https://github.com/swimlane/soc-faker) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
