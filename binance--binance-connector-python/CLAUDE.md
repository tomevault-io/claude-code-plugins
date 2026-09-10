# binance-connector-python

> from binance_common.configuration import ConfigurationWebSocketStreams

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/binance-connector-python/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent

```python
import asyncio
import ssl
import logging

from binance_common.configuration import ConfigurationWebSocketStreams
from binance_sdk_stocks.stocksimport Stocks

logging.basicConfig(level=logging.INFO)

configuration_ws_streams = ConfigurationWebSocketStreams(
    https_agent=ssl.create_default_context(),
)

client = Stocks(config_ws_streams=configuration_ws_streams)


async def price_stream():
    connection = None
    try:
        connection = await client.websocket_streams.create_connection()

        stream = await connection.price_stream()
        stream.on("message", lambda data: print(f"{data}"))

        await asyncio.sleep(5)
        await stream.unsubscribe()
    except Exception as e:
        logging.error(f"price_stream() error: {e}")
    finally:
        if connection:
            await connection.close_connection(close_session=True)


if __name__ == "__main__":
    asyncio.run(price_stream())
```

---
> Source: [binance/binance-connector-python](https://github.com/binance/binance-connector-python) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-10 -->
