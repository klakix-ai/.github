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
  <a href="https://klakix.com/blender-mcp">Blender MCP</a> ·
  <a href="https://klakix.com/ai-video-skills">AI video skills</a> ·
  <a href="https://klakix.com/models">Models</a> ·
  <a href="https://klakix.com/pricing">Pricing</a> ·
  <a href="https://x.com/klakix">X</a>
</p>

---

**Klakix** ([klakix.com](https://klakix.com)) is a browser-based AI video studio. One account gives you text to video, image to video, talking photos, UGC-style ads, video effects, motion transfer, video upscaling, AI images, voiceovers, music and sound effects. Models from Google (Veo, Nano Banana), ByteDance (Seedance, OmniHuman), Kuaishou (Kling), Alibaba (Wan), MiniMax (Hailuo), OpenAI (GPT Image), HeyGen and Topaz run side by side, priced in credits with no subscription required.

## Open source

| Project | What it is |
|---|---|
| [ai-video-skills](https://github.com/klakix-ai/ai-video-skills) | Ten Agent Skills for AI video production (MIT): camera angles, character consistency, Seedance and Kling prompts, realism, lip sync, pacing, viral formats, phone screen compositing and 3D previs. Works with Claude Code, Codex, Cursor and Gemini CLI. |
| [klakix-mcp](https://github.com/klakix-ai/klakix-mcp) | Klakix MCP server: setup for Claude, ChatGPT, Claude Code, Cursor, VS Code, Devin Desktop (Windsurf), Codex and Gemini CLI, the 19 tools and 7 workflows. |
| [klakix-blender](https://github.com/klakix-ai/klakix-blender) | Blender MCP add-on (GPL-3.0, Blender 4.2+): lets Claude, ChatGPT, Cursor and other MCP clients build, light, animate and render in your open Blender scene through the same Klakix MCP URL. |
| [`klakix-mcp` on npm](https://github.com/klakix-ai/klakix-mcp/tree/main/packages/cli) | Stdio bridge for Claude Desktop: `npx -y klakix-mcp`. |
| [`@klakix/mcp-server`](https://github.com/klakix-ai/klakix-mcp/tree/main/packages/mcp-server) | Stateless Streamable HTTP MCP server for the Fetch API, with zod tools, prompts, resources and an SSRF-safe media fetcher. |
| [`@klakix/mcp-oauth`](https://github.com/klakix-ai/klakix-mcp/tree/main/packages/mcp-oauth) | OAuth 2.1 authorization server for remote MCP servers: PKCE, dynamic client registration, client ID metadata documents, refresh token rotation. |

## Klakix MCP server in one line

```bash
claude mcp add --transport http --scope user klakix https://klakix.com/api/mcp
```

Server URL: `https://klakix.com/api/mcp` (Streamable HTTP, OAuth 2.1 sign-in or API key). Ask your assistant for a video, an image or a voiceover, and it calls Veo, Kling, Seedance, Nano Banana or GPT Image through your Klakix account.

## Contact

- Support: support@klakix.com
- Security reports: see [SECURITY.md](https://github.com/klakix-ai/klakix-mcp/blob/main/SECURITY.md)
