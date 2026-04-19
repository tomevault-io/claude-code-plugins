# cursor-temp

> "context_initialization": {

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cursor-temp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

{
    "rules": {
        "context_initialization": {
            "description": "Starting point for each interaction",
            "steps": [
                "ALWAYS read `.notes/project_overview.md` and `.notes/task_list.md`"
            ]
        },
        "operational_protocol": {
            "description": "How to approach tasks",
            "before_action": [
                "Create a MECE task breakdown"
            ],
            "code_changes": [
                "Read relevant code sections before editing",
                "Preserve existing functionality",
                "Maintain type safety"
            ]
        },
        "safety_requirements": [
            "NEVER break type safety",
            "ALWAYS maintain proper error handling",
            "ALWAYS document new code"
        ],
        "priorities": [
            {
                "source": ".notes/",
                "weight": 1.0
            }
        ],
        "modes": {
            "base": {
                "description": "For routine tasks"
            },
            "enhanced": {
                "description": "For complex problems"
            }
        },
        "project_directives": {
            "name": "my_project",
            "ai_first": true
        }
    }
}

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/youngjuene) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-14 -->
