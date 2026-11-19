<p align="center">
  <a href="https://klakix.com"><img src="https://klakix.com/logo-512.png" width="88" alt="Klakix logo"></a>
</p>

<h1 align="center">Klakix</h1>

<p align="center">
  AI video, image and audio generator in the browser, and an MCP server that brings it to Claude, ChatGPT, Cursor and VS Code.
</p>

<p align="center">
  <a href="https://klakix.com">Website</a> ·
  <a href="https://klakix.com/mcp">MCP server</a> ·
  <a href="https://klakix.com/models">Models</a> ·
  <a href="https://klakix.com/pricing">Pricing</a> ·
  <a href="https://x.com/klakix">X</a>
</p>

---

**Klakix** ([klakix.com](https://klakix.com)) is a browser-based AI video studio. One account gives you text to video, image to video, talking photos, UGC-style ads, video effects, motion transfer, video upscaling, AI images, voiceovers, music and sound effects. Models from Google (Veo, Nano Banana), ByteDance (Seedance, OmniHuman), Kuaishou (Kling), Alibaba (Wan), MiniMax (Hailuo), OpenAI (GPT Image), HeyGen and Topaz run side by side, priced in credits with no subscription required.

## Open source

| Repository | What it is |
|---|---|
| [klakix-mcp](https://github.com/klakix-ai/klakix-mcp) | Klakix MCP server: setup for Claude, ChatGPT, Claude Code, Cursor, VS Code, Devin Desktop (Windsurf), Codex and Gemini CLI, the 19 tools, 7 workflows and ready-to-copy configs. |

## Klakix MCP server in one line

```bash
claude mcp add --transport http --scope user klakix https://klakix.com/api/mcp
```

Server URL: `https://klakix.com/api/mcp` (Streamable HTTP, OAuth 2.1 sign-in or API key). Ask your assistant for a video, an image or a voiceover, and it calls Veo, Kling, Seedance, Nano Banana or GPT Image through your Klakix account.

## Contact

- Support: support@klakix.com
- Security reports: see [SECURITY.md](https://github.com/klakix-ai/klakix-mcp/blob/main/SECURITY.md)
