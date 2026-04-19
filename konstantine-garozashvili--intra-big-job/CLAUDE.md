# intra-big-job

> curl --request POST \

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/intra-big-job/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

curl --request POST \
--url http://localhost:8000/api/login_check \
--header 'Content-Type: application/json' \
--data '{
"username": "{role}@bigproject.com",
"password": "Password123@"
}'

You can replace {role} by : student/admin/superadmin/recruiter/guest/hr/teacher


Then you can use the bearer token to execute the other curl commands

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/konstantine-garozashvili) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
