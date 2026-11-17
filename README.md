# TurboWarp MCP Studio 🎮🤖

Turn **TurboWarp** into an autonomous AI game development studio connected to **Claude Desktop**. Claude can write Scratch blocks, draw custom SVG vector costumes & backdrops, spawn sprites, press the Green Flag, playtest with keyboard/mouse inputs, and visually inspect the stage via screenshots.

## Quick Setup

### 1. Claude Desktop Config
Open your `claude_desktop_config.json` (**Claude Settings → Developer → Edit Config**) and add:

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
*(Windows tip: If `npx` fails to start, use `"command": "npx.cmd"` instead.)*

Restart Claude Desktop completely after saving.

### 2. TurboWarp Extension
1. Download `tw-mcp.js` from the [Latest Release](https://github.com) (or copy the raw code from [`tw-mcp.js`](https://githubusercontent.com)).
2. Open [TurboWarp Editor](https://turbowarp.org) → **Add Extension** → **Custom Extension**.
3. Switch to the **Files** (or **Text**) tab, load `tw-mcp.js`, check **"Run without sandbox"**, and click **Load**.

4. Check **"Run without sandbox"** and click **Load**.

## Features
- **Code:** Generate and inject Scratch 3.0 blocks directly onto the Blockly workspace.
- **Draw:** Create custom SVG vector costumes and stage backdrops.
- **Playtest:** Trigger Green Flag, broadcasts, simulated key holds, and mouse clicks.
- **Debug:** Inspect sprite coordinates, variables, lists, speech logs, and live stage screenshots.