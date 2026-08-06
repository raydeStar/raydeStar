# Mark Hall

## Local-first AI, agentic systems, MCP, and .NET

> Local models. Real tools. Honest measurements.

By day, I build production software with .NET and Azure. This profile is my
workshop for local AI, agent tooling, game systems, and experiments in making
smaller language models genuinely useful.

Most of my career has been spent building C# systems. Lately, I have been
exploring the unglamorous machinery that turns an impressive AI demo into
dependable software: deterministic execution, Model Context Protocol (MCP)
integrations, explicit permissions, retrieval-augmented generation (RAG),
durable memory, visible evidence, human approval around destructive actions,
and repeatable evaluation.

**[Project notes, experiments, and longer-form writing at markbhall.dev](https://markbhall.dev)**

## What I'm building

### [Sir Thaddeus](https://github.com/raydeStar/sir-thaddeus)

An open-source, local-first AI assistant and agent workspace for Windows. Sir
Thaddeus connects local models through LM Studio, Ollama, or another
OpenAI-compatible endpoint, then gives them permissioned MCP tools, durable
memory, private knowledge, visible sources, execution traces, routines, and an
emergency stop.

It also serves as an evidence-driven research harness for measuring how
deterministic tools, retrieval, memory, permissions, and verification improve
the real-world task performance of fixed small language models.

`C#` · `.NET` · `Avalonia` · `MCP` · `Local LLMs` · `RAG` · `Agent evaluation`

### [Grand Adventure Engine](https://github.com/raydeStar/grand-adventure-engine)

A self-hosted multiplayer AI-narrated RPG for Discord and the web. The language
model tells the story, while a deterministic C# game engine resolves combat,
dice rolls, loot, quests, inventory, and skill checks. The result is generative
storytelling with rules that remain fair, testable, and consistent.

`C#` · `.NET 10` · `ASP.NET Core` · `SignalR` · `Docker` · `Playwright` · `LM Studio` · `Ollama`

## Open-source notes

- **[Unsloth Zoo PR #769](https://github.com/unslothai/unsloth-zoo/pull/769):**
  Added reasoning-channel extraction for DiffusionGemma's OpenAI-compatible
  shim, including streaming boundary handling and automated tests. Merged
  upstream into the Unsloth ecosystem.

## Principles behind the projects

- Keep the LLM out of the critical path when correctness matters.
- Use deterministic systems for rules, state transitions, validation, and
  destructive actions.
- Give agents bounded capabilities, explicit permissions, visible evidence,
  and a hard stop.
- Measure improvements against frozen baselines and unseen tasks, not
  impressive-looking demos.

## From the blog

At **[markbhall.dev](https://markbhall.dev)**, I publish engineering notes and
experiments on local language models, agentic AI, MCP tooling, LLM evaluation,
benchmark design, production AI safety, and AI-assisted software development.

## Topics I keep returning to

`Agentic AI` · `Model Context Protocol (MCP)` · `Local LLMs` · `LLM evaluation` ·
`RAG` · `Tool use` · `Structured outputs` · `Human-in-the-loop AI` · `.NET / C#` ·
`Azure` · `Docker` · `Playwright`

## Elsewhere

- [LinkedIn](https://www.linkedin.com/in/mhall0808/)
