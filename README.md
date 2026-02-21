# Awesome Agentic Engineering [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for **Agentic Engineering**: the software development discipline where AI agents are orchestrated to autonomously plan, write, test, and evolve software based on human-defined goals and constraints.

Focused on **practical adoption** for team leads bringing agentic practices to their engineering teams.

---

## Contents

## Contents

- [What Is Agentic Engineering?](#what-is-agentic-engineering)
- [Team Adoption](#team-adoption)
- [Code-Focused Agent Tools](#code-focused-agent-tools)
- [Talks & Conferences](#talks--conferences)
- [Practical Advice](#practical-advice)
- [Case Studies](#case-studies)
- [Standards](#standards)
- [Contributing](#contributing)
---

## What Is Agentic Engineering?

Agentic Engineering is a software development approach where AI agents are orchestrated to autonomously plan, write, test, debug, and evolve software based on human-defined goals and constraints. Engineers focus on setting objectives, defining constraints, and reviewing outcomes instead of coding line by line.

---

## Team Adoption

> Practical guidance for engineering managers and team leads.

- [Claude Code Quickstart](https://docs.anthropic.com/en/docs/claude-code/quickstart) — Anthropic's official guide to getting started with an agentic coding CLI.
- [GitHub Copilot Workspace](https://githubnext.com/projects/copilot-workspace) — GitHub's agentic development environment where natural language goals are resolved into full PRs.
- [OpenAI Codex in Agentic Mode](https://platform.openai.com/docs/guides/code) — Using OpenAI models to run multi-step coding pipelines.
---

## Code-Focused Agent Tools

### Open Source — Model-Agnostic
- [Aider](https://github.com/paul-gauthier/aider) — AI pair programming in your terminal; supports complex multi-file refactors via agent-style planning. ![Stars](https://img.shields.io/github/stars/paul-gauthier/aider?style=flat&logo=github&label=)
- [OpenCode](https://github.com/sst/opencode) — CLI coding agent supporting 75+ LLM providers including local models, with MCP integration. ![Stars](https://img.shields.io/github/stars/sst/opencode?style=flat&logo=github&label=)
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) — Open-source Devin alternative; full software engineering agent with browser, terminal, and editor access. ![Stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=flat&logo=github&label=)
- [Plandex](https://github.com/plandex-ai/plandex) — Terminal-based AI coding engine designed for large, multi-file tasks. ![Stars](https://img.shields.io/github/stars/plandex-ai/plandex?style=flat&logo=github&label=)

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

# Practical advice

* [Building an AI-Native Engineering Team](https://developers.openai.com/codex/guides/build-ai-native-engineering-team/)

## Case Studies

> Real teams, real outcomes — learn from those ahead of you.

[**My LLM Coding Workflow Going into 2026** — Addy Osmani](https://medium.com/@addyosmani/my-llm-coding-workflow-going-into-2026-52fe1681325e). A practical guide to AI-assisted engineering that emphasizes specs-first planning, small iterations, strong context and model selection.


## Standards

[agents.md](https://agents.md/) — An open standard for guiding AI coding agents, giving them project-specific build, test, and code style instructions.

[MCP — Model Context Protocol](https://modelcontextprotocol.io/) — An open standard for connecting AI models to external tools, data sources, and services. 

---

## Contributing

Contributions welcome! This list prioritizes practical, team-applicable resources over theoretical ones. When suggesting additions, please include a one-line description of why it is useful specifically to a team lead adopting agentic engineering.
