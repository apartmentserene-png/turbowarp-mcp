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
  },
  "preferences": {
    "coworkLegacyRootGrantsPruned": true,
    "remoteToolsDeviceName": "desktop-gip7u7o",
    "launchPreviewPersistedWorkspaces": [],
    "launchPreviewSessionScopedSessions": [],
    "httpCacheZstdLatched": true,
    "coworkScheduledTasksEnabled": false,
    "ccdScheduledTasksEnabled": false,
    "epitaxyPrefs": {
      "dframe-group-scopes": {},
      "dframe-local-slice": {
        "pinnedOrder": [],
        "homeProjectsPinnedOrder": []
      },
      "dframe-code-sections": {
        "12b9f0ba-ccb9-4eec-a94e-f70ffa4e4b4e/693a1fc9-1dcb-4448-8632-50a25b38ad59": {
          "sections": [
            {
              "id": "pinned",
              "kind": "pinned",
              "v": 2,
              "name": "",
              "order": 0,
              "sortBy": "recency",
              "ascending": false,
              "show": {
                "metadata": false,
                "emptyGroups": false,
                "sideChats": false,
                "slack": true
              },
              "collapsed": false,
              "shown": true
            },
            {
              "id": "routines",
              "kind": "routines",
              "v": 2,
              "name": "",
              "order": 1,
              "sortBy": "recency",
              "ascending": false,
              "show": {
                "metadata": false,
                "emptyGroups": false,
                "sideChats": false,
                "slack": true
              },
              "collapsed": true,
              "shown": false
            },
            {
              "id": "sessions",
              "kind": "sessions",
              "v": 2,
              "name": "",
              "order": 2,
              "sortBy": "recency",
              "ascending": false,
              "show": {
                "metadata": false,
                "emptyGroups": false,
                "sideChats": false,
                "slack": true
              },
              "collapsed": false,
              "shown": true
            }
          ],
          "migratedFrom": 1,
          "prefsSeeded": true
        }
      },
      "desktop-frame.paneStore.v1": {
        "state": {
          "extraPanesByMode": {},
          "colWeightsByMode": {},
          "rowSplit": 0.5,
          "draftNonce": 0,
          "lastPrimaryCodeSession": null
        },
        "version": 4
      },
      "starred-session-groups": [],
      "starred-local-routines": [],
      "starred-local-code-sessions": [],
      "starred-cowork-spaces": []
    },
    "coworkHipaaRestricted": false,
    "orgWorkAcrossAppsDisabled": true,
    "coworkWebSearchEnabled": true,
    "coworkPreferredBrowser": "built_in",
    "coworkBrowserToolsEnabled": false,
    "coworkModelAutoFallbackByAccount": {
      "12b9f0ba-ccb9-4eec-a94e-f70ffa4e4b4e": true
    },
    "bypassPermissionsGateByAccount": {
      "12b9f0ba-ccb9-4eec-a94e-f70ffa4e4b4e": false
    }
  },
  "coworkUserFilesPath": "C:\\Users\\Admin\\Claude"
}
```

### 2. TurboWarp Extension
Open TurboWarp Editor -> Add Extension -> Custom Extension -> URL:
`https://githubusercontent.com`
Check **Run without sandbox** and click **Load**.
