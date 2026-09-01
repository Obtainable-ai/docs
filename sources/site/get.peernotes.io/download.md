# Source: https://get.peernotes.io/download

_Captured 2026-08-31. Reference material for the docs — not published._

## Where PeerNotes lives

**Thoughts arrive anywhere. So does PeerNotes.** The browser you're reading in, the
phone in your pocket, the assistant you already ask — pick whichever is closest.

### 01 In your browser

**Start reading. Start keeping.**

The whole workspace runs in any browser — nothing to install. Add the clipper and the
page you're on becomes a source, highlight and all.

- Open peernotes.io — https://peernotes.io
- Google Chrome — available in the Chrome Web Store — https://chromewebstore.google.com/detail/ojongipbblbjdoidjgmefhdhngmimhbi
- Clipper also coming to Firefox
- Clipper also coming to Safari

### 02 In your pocket

**Say it before you lose it.**

Tap to dictate and it's in the workspace before you reach the car — or share a link or
screenshot into PeerNotes from any app on your phone. Everything lands in the same
workspace, so your teammates pick it up from the browser.

- Apple — private beta — request for iPhone: mailto:support@peernotes.io?subject=Request%20to%20join%20iPhone%20beta%20testing
- Android — private beta — request for Android: mailto:support@peernotes.io?subject=Request%20to%20join%20Android%20beta%20testing

Both apps are in private beta — tell them a little about your team and they'll send you a build.

### 03 In your assistant

**Ask about your own work. Get your own answers.**

Connect PeerNotes to the AI assistant you already use, and it answers from what you and
your teammates actually wrote — not from the open web.

Connecting takes a minute:

1. Copy your workspace address: `https://api.peernotes.io/mcp`
2. Paste it where your assistant asks for a connector.
3. Sign in with your PeerNotes account. No keys, no files to edit.

Your assistant only ever sees the workspaces your account can already open.

Prefer to edit a config file (Claude Desktop / Claude Code)?

```json
{
  "mcpServers": {
    "peernotes": {
      "url": "https://api.peernotes.io/mcp"
    }
  }
}
```

Settings › Developer › Edit config, then restart Claude. Works with Claude and any client
that supports remote MCP servers.

## Access

- Research preview now open for teams.
- Free while in preview · no card required.
- Sign in / Get started: https://peernotes.io
- Help & Support: https://help.peernotes.io
