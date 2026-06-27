<p align="center">
  <img src="https://em-content.zobj.net/source/apple/391/kite_1fa81.png" width="120" />
</p>

<h1 align="center">awesome-kiro</h1>

<p align="center">
  <strong>A curated list of awesome Kiro IDE & CLI tools, skills, plugins, and resources</strong>
</p>

<p align="center">
  <a href="https://github.com/tomzhi919/awesome-kiro/stargazers"><img src="https://img.shields.io/github/stars/tomzhi919/awesome-kiro?style=flat&color=yellow" alt="Stars"></a>
  <a href="https://github.com/tomzhi919/awesome-kiro/commits/main"><img src="https://img.shields.io/github/last-commit/tomzhi919/awesome-kiro?style=flat" alt="Last Commit"></a>
  <a href="#contributing"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-CC0%201.0-blue.svg" alt="License: CC0"></a>
</p>

<p align="center">
  <a href="#official">Official</a> •
  <a href="#api--proxy">API & Proxy</a> •
  <a href="#skills--plugins">Skills & Plugins</a> •
  <a href="#context--memory">Context & Memory</a> •
  <a href="#multi-agent">Multi-Agent</a> •
  <a href="#utilities">Utilities</a> •
  <a href="#learning">Learning</a> •
  <a href="#contributing">Contributing</a>
</p>

---

> [!TIP]
> Kiro is Amazon's agentic IDE that works alongside you from prototype to production — spec-driven development, autonomous agents, and deep AWS integration. This list tracks the best community tools building on top of it.

## Contents

- [Official](#official)
- [API & Proxy](#api--proxy)
- [Skills & Plugins](#skills--plugins)
- [Context & Memory](#context--memory)
- [Token Optimization](#token-optimization)
- [Multi-Agent & Orchestration](#multi-agent--orchestration)
- [Account & Session Management](#account--session-management)
- [Utilities & Developer Tools](#utilities--developer-tools)
- [Learning & Resources](#learning--resources)
- [Community](#community)

---

## Official

- [kirodotdev/Kiro](https://github.com/kirodotdev/Kiro) — Kiro IDE: the agentic IDE that works alongside you from prototype to production.
- [kirodotdev/spirit-of-kiro](https://github.com/kirodotdev/spirit-of-kiro) — Spirit of Kiro: a game built with and powered by generative AI.
- [Kiro Docs](https://kiro.dev/docs) — Official documentation for Kiro IDE & CLI.

## API & Proxy

- [viezai/kiro-openai-proxy](https://github.com/viezai/kiro-openai-proxy) — OpenAI-compatible HTTP proxy for Kiro CLI. Point any OpenAI client at Kiro. Zero dependencies.
- [jwadow/kiro-gateway](https://github.com/jwadow/kiro-gateway) — Proxy API gateway for Kiro IDE & CLI (Amazon Q / AWS CodeWhisperer).
- [Quorinex/Kiro-Go](https://github.com/Quorinex/Kiro-Go) — Convert Kiro accounts into OpenAI/Anthropic APIs. Multi-account pooling & streaming.
- [caidaoli/kiro2api](https://github.com/caidaoli/kiro2api) — Kiro to API bridge.
- [justlovemaki/AIClient2API](https://github.com/justlovemaki/AIClient2API) — Simulates Kiro, Gemini CLI, Codex, and Grok client requests as OpenAI-compatible API.
- [aliom-v/KiroGate](https://github.com/aliom-v/KiroGate) — OpenAI & Anthropic compatible Kiro IDE API proxy gateway.
- [petehsu/KiroProxy](https://github.com/petehsu/KiroProxy) — Compatibility and routing layer for developer workflows.
- [bestK/kiro2cc](https://github.com/bestK/kiro2cc) — Bridge Kiro to Claude Code.

## Skills & Plugins

- [obra/superpowers](https://github.com/obra/superpowers) — Agentic skills framework (240k⭐). Works with Kiro, Claude Code, Codex, and more.
- [anthropics/skills](https://github.com/anthropics/skills) — Official Agent Skills repository (155k⭐). Compatible with Kiro CLI agent mode.
- [sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills) — 1,600+ installable agentic skills for Kiro, Claude Code, Cursor, Codex.
- [FrancyJGLisboa/agent-skill-creator](https://github.com/FrancyJGLisboa/agent-skill-creator) — Turn any workflow into reusable AI agent skills for 17 platforms including Kiro.
- [agent-sh/agentsys](https://github.com/agent-sh/agentsys) — 24 plugins, 49 agents, 44 skills for Claude Code, Codex, Kiro, and more.
- [codexstar69/bug-hunter](https://github.com/codexstar69/bug-hunter) — Adversarial AI bug hunter with auto-fix skill for Kiro, Claude Code, Codex.
- [jnMetaCode/superpowers-zh](https://github.com/jnMetaCode/superpowers-zh) — Superpowers Chinese edition with 6 original skills for Kiro & Claude Code.

## Context & Memory

- [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph) — Pre-indexed code knowledge graph, auto-syncs on changes. For Kiro, Claude Code, Codex, Gemini, Cursor.
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) — Persistent file-based planning for AI coding agents. Crash-proof markdown task management.
- [AVIDS2/memorix](https://github.com/AVIDS2/memorix) — Open-source cross-agent memory layer via MCP. Compatible with Kiro, Claude Code, Codex.
- [voidcraft-dev/memory-forge-rs](https://github.com/voidcraft-dev/memory-forge-rs) — Local session manager for Kiro, Claude Code, Cursor. Edit memories instead of resetting.
- [huytieu/COG-second-brain](https://github.com/huytieu/COG-second-brain) — Self-evolving second brain with 17 AI skills and 6 worker agents.

## Token Optimization

- [rtk-ai/rtk](https://github.com/rtk-ai/rtk) — CLI proxy that reduces token consumption by 60-90% (66k⭐). Works with Kiro, Claude Code, Codex.
- [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) — Context compression layer for AI agents (52k⭐). 60-95% fewer tokens. Library, proxy, MCP.
- [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) — Makes agents talk concise — cuts ~75% output tokens (77k⭐). Works with 30+ agents including Kiro.
- [mksglu/context-mode](https://github.com/mksglu/context-mode) — Context window optimization. Sandboxes tool output (98% reduction). For Kiro, Claude Code, Codex.
- [mm7894215/TokenTracker](https://github.com/mm7894215/TokenTracker) — Track token usage across 25 AI coding tools including Kiro.

## Multi-Agent & Orchestration

- [formulahendry/wechat-acp](https://github.com/formulahendry/wechat-acp) — Bridge WeChat chat to any ACP-compatible agent including Kiro.
- [Human-Agent-Society/CORAL](https://github.com/Human-Agent-Society/CORAL) — Lightweight multi-agent autonomous self-evolution infrastructure.
- [SeemSeam/claude_codex_bridge](https://github.com/SeemSeam/claude_codex_bridge) — Multi-agent CLI workspace mixing Codex, Claude, Gemini, Kiro, and more.
- [wangdabaoqq/LinJun](https://github.com/wangdabaoqq/LinJun) — Cross-platform GUI for managing AI coding agents (Claude, Gemini, Codex, Kiro).

## Account & Session Management

- [hj01857655/kiro-account-manager](https://github.com/hj01857655/kiro-account-manager) — Smart Kiro IDE account management: one-click switch, quota monitoring.
- [chaogei/Kiro-account-manager](https://github.com/chaogei/Kiro-account-manager) — Kiro account manager.
- [jlcodes99/cockpit-tools](https://github.com/jlcodes99/cockpit-tools) — Universal AI IDE account manager: Kiro, Codex, Copilot, Windsurf, Cursor, Gemini.
- [QLHazyCoder/FlowPilot](https://github.com/QLHazyCoder/FlowPilot) — Chrome extension for Kiro registration, verification, and auto-recovery.

## Utilities & Developer Tools

- [hank9999/kiro.rs](https://github.com/hank9999/kiro.rs) — A Kiro client implemented in Rust.
- [jasonkneen/kiro](https://github.com/jasonkneen/kiro) — Complete system prompts for Kiro IDE by Amazon.
- [ghuntley/amazon-kiro.kiro-agent-source-code-analysis](https://github.com/ghuntley/amazon-kiro.kiro-agent-source-code-analysis) — Kiro agent source code analysis.
- [farion1231/cc-switch](https://github.com/farion1231/cc-switch) — Cross-platform All-in-One assistant for Claude Code, Codex, OpenCode, Kiro (109k⭐).

## Learning & Resources

- [x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools) — Full system prompts for Kiro, Claude Code, Cursor, Devin, and 20+ AI tools.
- [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) — Build a nano agent harness from scratch. Applicable to Kiro architecture understanding.
- [Kiro Blog](https://kiro.dev/blog) — Official blog with tips, updates, and deep dives.

## Community

- [Kiro Discord](https://discord.gg/kiro) — Official Kiro community Discord.
- [r/KiroIDE](https://reddit.com/r/KiroIDE) — Kiro subreddit.

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a PR.

### Criteria

- The project must be related to Kiro IDE or CLI
- It should be actively maintained (commit in last 6 months)
- It should have clear documentation (README)
- It should be useful to the Kiro community

### How to Add

1. Fork this repo
2. Add your link in the appropriate section
3. Use format: `[owner/repo](url) — Short description.`
4. Submit a PR with a brief explanation of why it's awesome

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related rights to this work.
