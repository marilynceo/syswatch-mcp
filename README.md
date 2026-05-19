# syswatch-mcp

Monitor CPU, RAM, disk, network I/O, and processes on any Linux/macOS/Windows machine u2014 get alerts, trends, and insights u2014 directly from your AI agent. No SaaS, no agents, no infrastructure.

## Quick Start

```bash
git clone https://github.com/marilynceo/syswatch-mcp.git
cd syswatch-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://syswatch.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/syswatch-mcp

# Or connect directly via MCP client
# Endpoint: https://syswatch.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
