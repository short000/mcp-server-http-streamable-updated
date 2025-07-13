
You can use npx mcp-remote to retrofit MCP Clients that do not yet support Streamable HTTPS (only local STDIO). Replace the example URL with the one pointing to actual server.
```
    "Remote Example": {
      "command": "npx",
      "args": [
        "mcp-remote",
        "http://127.0.0.1:8000/mcp",
        "--allow-http"
      ]
    }
```