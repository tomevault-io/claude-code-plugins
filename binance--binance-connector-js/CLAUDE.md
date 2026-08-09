# binance-connector-js

> import { HttpsProxyAgent } from 'https-proxy-agent';

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/binance-connector-js/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# WebSocket Agent Configuration

```typescript
import { HttpsProxyAgent } from 'https-proxy-agent';
import { Alpha, ALPHA_WS_STREAMS_PROD_URL } from '@binance/alpha';

const configurationWebsocketStreams = {
    wsURL: ALPHA_WS_STREAMS_PROD_URL,
    agent: new HttpsProxyAgent('your-proxy-url'),
};
const client = new Alpha({ configurationWebsocketStreams });

client.websocketStreams.connect().then(console.log).catch(console.error);
```

---
> Source: [binance/binance-connector-js](https://github.com/binance/binance-connector-js) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-09 -->
