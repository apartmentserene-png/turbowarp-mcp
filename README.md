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
1. Open [TurboWarp Editor](https://turbowarp.org).
2. Click **Add Extension** (bottom-left) → **Custom Extension** → **URL** tab.
3. Paste:
   ```text
   https://githubusercontent.com
   ```
4. Check **"Run without sandbox"** and click **Load**.

## Features
- **Code:** Generate and inject Scratch 3.0 blocks directly onto the Blockly workspace.
- **Draw:** Create custom SVG vector costumes and stage backdrops.
- **Playtest:** Trigger Green Flag, broadcasts, simulated key holds, and mouse clicks.
- **Debug:** Inspect sprite coordinates, variables, lists, speech logs, and live stage screenshots.