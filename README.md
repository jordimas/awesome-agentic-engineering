# Awesome Agentic Engineering [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for **Agentic Engineering**: the software development discipline where AI agents are orchestrated to autonomously plan, write, test, and evolve software based on human-defined goals and constraints.

Focused on **practical adoption** for engineering teams adopting Agentic Engineering.

---

## Contents

- [What Is Agentic Engineering?](#what-is-agentic-engineering)
- [Team Adoption](#team-adoption)
- [Code-Focused Agent Tools](#code-focused-agent-tools)
- [Talks & Conferences](#talks--conferences)
- [Case Studies and Practical Advice](#case-studies-and-practical-advice)
- [Key Papers to Understand the Practice](#key-papers-to-understand-the-practice)
- [Standards](#standards)
- [Spec-Driven Development](#spec-driven-development)
- [Multi-Agent Frameworks](#multi-agent-frameworks)
- [Browser & Computer Use Agents](#browser--computer-use-agents)
- [Contributing](#contributing)
---

## What Is Agentic Engineering?

Agentic Engineering is a software development approach where AI agents are orchestrated to autonomously plan, write, test, debug, and evolve software based on human-defined goals and constraints. Engineers focus on setting objectives, defining constraints, and reviewing outcomes instead of coding line by line.

---

## Team Adoption

> Practical guidance for engineering teams.

- [Claude Code Documentation](https://code.claude.com/docs/) - Official documentation for Claude Code, gives a good overview of basic concepts, workflows and best practices.
- [OpenAI Codex Quickstart](https://developers.openai.com/codex/quickstart) — A beginner-friendly guide to getting started with OpenAI Codex, covering setup, API integration, and your first code generation requests.
---

## Code-Focused Agent Tools

### Open Source — Model-Agnostic
- [Aider](https://github.com/paul-gauthier/aider) — AI pair programming in your terminal; supports complex multi-file refactors via agent-style planning. ![Stars](https://img.shields.io/github/stars/paul-gauthier/aider?style=flat&logo=github&label=)
- [Cline](https://github.com/cline/cline) — Autonomous coding agent for VS Code that can create/edit files, run commands, and use the browser with human-in-the-loop approval at each step. ![Stars](https://img.shields.io/github/stars/cline/cline?style=flat&logo=github&label=)
- [Continue](https://github.com/continuedev/continue) — Open-source IDE extension (VS Code, JetBrains) for building, sharing, and running custom AI code assistants with any model. ![Stars](https://img.shields.io/github/stars/continuedev/continue?style=flat&logo=github&label=)
- [Goose](https://github.com/block/goose) — Block's open-source, on-machine AI agent that automates engineering tasks end-to-end with MCP-based tool extensions. ![Stars](https://img.shields.io/github/stars/block/goose?style=flat&logo=github&label=)
- [OpenCode](https://github.com/sst/opencode) — CLI coding agent supporting 75+ LLM providers including local models, with MCP integration. ![Stars](https://img.shields.io/github/stars/sst/opencode?style=flat&logo=github&label=)
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) — Open-source Devin alternative; full software engineering agent with browser, terminal, and editor access. ![Stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=flat&logo=github&label=)
- [Plandex](https://github.com/plandex-ai/plandex) — Terminal-based AI coding engine designed for large, multi-file tasks. ![Stars](https://img.shields.io/github/stars/plandex-ai/plandex?style=flat&logo=github&label=)
- [Roo Code](https://github.com/RooCodeInc/Roo-Code) — Autonomous AI coding agent for your editor; supports custom modes, multi-model providers, and orchestration of subtasks. ![Stars](https://img.shields.io/github/stars/RooCodeInc/Roo-Code?style=flat&logo=github&label=)

### Commercial offering

- [Gemini CLI](https://github.com/google-gemini/gemini-cli) — Google's terminal agent; optimized for Gemini models with tool use and MCP support. ![Stars](https://img.shields.io/github/stars/google-gemini/gemini-cli?style=flat&logo=github&label=)
- [Cursor](https://www.cursor.com/) — IDE built for agentic coding workflows; inline agent with codebase-wide context and multi-model support.
- [Claude Code](https://github.com/anthropics/claude-code) — Anthropic's agentic CLI that operates directly on your local codebase; optimized for Claude models. ![Stars](https://img.shields.io/github/stars/anthropics/claude-code?style=flat&logo=github&label=)
- [Codex](https://github.com/openai/codex) — OpenAI's lightweight coding agent that runs in your terminal; optimized for OpenAI models. ![Stars](https://img.shields.io/github/stars/openai/codex?style=flat&logo=github&label=)
---


## Talks & Conferences

> Video content worth watching with your team.

- [The Future of Coding is Agents — Andrej Karpathy (YC)](https://www.youtube.com/watch?v=fqVLjtvWgq8) — Landmark talk on the trajectory from coding assistants to autonomous agents.

- [Agentic Coding: The Future of Software Development with Agents — Armin Ronacher](https://www.youtube.com/watch?v=nfOVgz_omlU) — 37-minute talk by the creator of Flask and Sentry on adopting Claude Code and agentic workflows in practice; packed with concrete tips teams can apply immediately.


## Case Studies and Practical advice

> Real teams, real outcomes — learn from those ahead of you.

- [My LLM Coding Workflow Going into 2026 — Addy Osmani](https://medium.com/@addyosmani/my-llm-coding-workflow-going-into-2026-52fe1681325e). A practical guide to AI-assisted engineering that emphasizes specs-first planning, small iterations, strong context and model selection.
- [How Claude Code is Built](https://newsletter.pragmaticengineer.com/p/how-claude-code-is-built). A deep dive into Claude Code's origins, architecture, and what it signals for AI-assisted software development.
- [Building an AI-Native Engineering Team](https://developers.openai.com/codex/guides/build-ai-native-engineering-team/). OpenAI's practical guide to structuring and scaling engineering teams around AI-first workflows with Codex.
- [everything-claude-code](https://github.com/affaan-m/everything-claude-code). A comprehensive collection of resources, tips, prompts, and examples for getting the most out of Claude Code — Anthropic's AI-driven command-line coding assistant.

## Standards

* [agents.md](https://agents.md/) — An open standard for guiding AI coding agents, giving them project-specific build, test, and code style instructions.
* [MCP — Model Context Protocol](https://modelcontextprotocol.io/) — An open standard for connecting AI models to external tools, data sources, and services.
* [MCP Reference Servers](https://github.com/modelcontextprotocol/servers) — Official reference implementations of MCP servers; the canonical starting point for teams building agent integrations. ![Stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat&logo=github&label=)
* [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) — Community-curated catalog of MCP server implementations for hooking agents into databases, APIs, browsers, and more. ![Stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers?style=flat&logo=github&label=)

## Spec-Driven Development

> Frameworks for turning specs and requirements into working software via agents.

* [Spec Kit](https://github.com/github/spec-kit) — GitHub's toolkit for spec-driven development, helping teams define what to build before letting agents implement it. ![Stars](https://img.shields.io/github/stars/github/spec-kit?style=flat&logo=github&label=)
* [BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD) — Universal AI agent framework for agile, agentic-driven planning and execution across software, creative, and business domains. ![Stars](https://img.shields.io/github/stars/bmad-code-org/BMAD-METHOD?style=flat&logo=github&label=)

## Multi-Agent Frameworks

> Building blocks for orchestrating multiple agents with roles, memory, and tool access.

* [LangChain](https://github.com/langchain-ai/langchain) — The most widely used framework for building LLM-powered applications, including multi-step agent workflows. ![Stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat&logo=github&label=)
* [Microsoft AutoGen](https://github.com/microsoft/autogen) — Programming framework for building multi-agent AI systems with conversable agents that collaborate to solve tasks. ![Stars](https://img.shields.io/github/stars/microsoft/autogen?style=flat&logo=github&label=)
* [CrewAI](https://github.com/crewAIInc/crewAI) — Lean Python framework for orchestrating role-playing, autonomous AI agents that work together as a crew. ![Stars](https://img.shields.io/github/stars/crewAIInc/crewAI?style=flat&logo=github&label=)
* [Dify](https://github.com/langgenius/dify) — Open-source platform for building LLM apps with agentic workflows, RAG, and observability — useful as the orchestration layer next to coding agents. ![Stars](https://img.shields.io/github/stars/langgenius/dify?style=flat&logo=github&label=)

## Browser & Computer Use Agents

> Agents that drive browsers and desktops — useful for E2E testing, scraping, and verifying agent-built software.

* [Browser Use](https://github.com/browser-use/browser-use) — Make any LLM control a real browser; widely used for agentic E2E testing and automating web flows. ![Stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat&logo=github&label=)
* [Stagehand](https://github.com/browserbase/stagehand) — Production-ready AI browser automation framework with natural-language actions on top of Playwright. ![Stars](https://img.shields.io/github/stars/browserbase/stagehand?style=flat&logo=github&label=)
* [Playwright](https://github.com/microsoft/playwright) — Microsoft's cross-browser automation library; the de-facto substrate for agent-driven browser testing and MCP browser servers. ![Stars](https://img.shields.io/github/stars/microsoft/playwright?style=flat&logo=github&label=)
* [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) — Lets LLMs run code locally with full system access; a foundational pattern for desktop-level coding agents. ![Stars](https://img.shields.io/github/stars/OpenInterpreter/open-interpreter?style=flat&logo=github&label=)

## Key papers to understand the practice

[GLM-5: from Vibe Coding to Agentic Engineering](https://arxiv.org/pdf/2602.15763) — Technical report for GLM-5, a coding-focused model bridging casual vibe coding and structured agentic software engineering through advanced reasoning and tool use.

## Contributing

Contributions welcome! This list prioritizes practical, team-applicable resources over theoretical ones. When suggesting additions, please include a one-line description of why it is useful specifically to a team adopting agentic engineering.
