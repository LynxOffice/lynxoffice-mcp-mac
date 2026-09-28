# LynxOffice MCP Server for Mac

LynxOffice offers an MCP server that lets AI agents read, edit and review Word, Excel, PowerPoint and PDF files on your Mac.

## Install

```bash
brew install lynxoffice/tap/lynxoffice-mcp
```

Then point your MCP client at it, for example:

```bash
claude mcp add lynxoffice -- "$(brew --prefix)/bin/lynxoffice-mcp"
```

Requires macOS 14 or later, on Apple silicon or Intel. Each build under [Releases](https://github.com/LynxOffice/lynxoffice-mcp-mac/releases) is signed with KDAN's Developer ID and notarized by Apple.

---

© 2009–2026 Kdan Mobile Software Ltd. All Rights Reserved.
