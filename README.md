# Basedash MCP

Remote MCP server for [Basedash](https://www.basedash.com), the AI-native BI platform. Connect Claude, Cursor, ChatGPT, and other MCP clients to live company data with governed answers.

**Endpoint:** `https://charts.basedash.com/api/public/mcp`  
**Transport:** Streamable HTTP  
**Auth:** Browser OAuth (no API key)

## Tools

| Tool | What it does |
| --- | --- |
| `ask_question` | Ask a question of live workspace data and get a governed answer |
| `get_data_sources` | List data sources available in the workspace |

## Connect

Point any MCP client at the endpoint above and complete the Basedash OAuth prompt.

Docs: [basedash.com/features/mcp-server](https://www.basedash.com/features/mcp-server)

## Registry

Published to the [official MCP Registry](https://registry.modelcontextprotocol.io) as `io.github.Basedash/mcp`.
