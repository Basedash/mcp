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
| `create_dashboard` | Create a dashboard and return its durable Basedash URL |
| `edit_dashboard` | Edit a dashboard and return its durable Basedash URL |
| `create_chart` | Create a chart, optionally on a dashboard, with its Basedash URL and screenshot link when available |
| `edit_chart` | Edit a chart and return its Basedash URL and screenshot link when available |
| `list_dashboards` | List dashboards in the workspace |
| `get_dashboard` | Get a dashboard and its charts |
| `list_charts` | List charts in the workspace |
| `get_chart` | Get a chart and its details |

## Connect

Point any MCP client at the endpoint above and complete the Basedash OAuth prompt.

Docs: [basedash.com/features/mcp-server](https://www.basedash.com/features/mcp-server)

## Registry

Published to the [official MCP Registry](https://registry.modelcontextprotocol.io) as `com.basedash/mcp`.
