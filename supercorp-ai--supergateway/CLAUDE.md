# supergateway

> Install Node.js v24 using nvm. After checking out the repository, run:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/supergateway/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Setup

Install Node.js v24 using nvm. After checking out the repository, run:

```bash
nvm install 24
nvm use 24
npm install

# Build

Compile the TypeScript sources before running tests:

npm run build
```

## Running tests

Run the test suite with Node's test runner and ts-node to enable mocks:

```bash
npm run test
```

The `tests/helpers/mock-mcp-server.js` script provides a lightweight local MCP
server used during tests so everything runs offline. All tests should pass
without external downloads.

If network-dependent commands (like `npx -y @modelcontextprotocol/server-*`) fail, check network access.

---
> Source: [supercorp-ai/supergateway](https://github.com/supercorp-ai/supergateway) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
