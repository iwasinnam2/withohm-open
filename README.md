# withOhm — open client tools

MIT-licensed client SDKs, MCP server, and integration templates for
[withOhm](https://www.withohm.dev) — a metered pipe that replays
byte-identical LLM requests and fetches public web context under
compliance controls.

This repo ships:

- `sdks/python/` — Python OpenAI `base_url` helper (`at-utility-sdk` on PyPI)
- `sdks/typescript/` — TypeScript/JS helper (`@at-utility/sdk` on npm)
- `packages/ohm-mcp/` — MCP server for Cursor/Claude agents (`withohm-mcp` on PyPI)
- `templates/` — ready-to-clone agent integration templates

The gateway, cache/replay engine, and billing/compliance core are
proprietary and not included here — see [withohm.dev](https://www.withohm.dev)
for the hosted pipe.

License: MIT (see `LICENSE`). This repo is a periodically-synced mirror of
the relevant directories in withOhm's private monorepo, not the primary
development location.
