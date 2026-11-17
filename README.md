# TurboWarp MCP Studio

Autonomous AI game dev studio for TurboWarp & Claude Desktop.

## Setup

### 1. Claude Desktop Config
```json
{
  "mcpServers": {
    "turbowarp": {
      "command": "npx",
      "args": ["-y", "github:apartmentserene-png/turbowarp-mcp"]
    }
  }
}
```

### 2. TurboWarp Extension
Open TurboWarp Editor -> Add Extension -> Custom Extension -> URL:
`https://githubusercontent.com`
Check **Run without sandbox** and click **Load**.
