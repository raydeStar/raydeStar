# Mark Hall — AI Engineer & Open-Source Developer

I'm **Mark Hall**, known as **raydeStar** on GitHub. I build **local-first AI
agents, LLM evaluation tools, and AI-powered creative software**, with a
background in **C#/.NET and Azure** and hands-on work across Python and TypeScript.

My focus is the engineering that makes AI useful beyond a demo: explicit tool
permissions, durable state, reproducible experiments, and human review. That
work spans private AI assistants, Model Context Protocol (MCP) integrations,
image-to-3D pipelines, and film pre-production tools.

[Website & engineering notes](https://markbhall.dev/) ·
[Explore the Stillwater 3D showcase](https://markbhall.dev/stillwater/) ·
[LinkedIn](https://www.linkedin.com/in/mhall0808/)

## Featured engineering projects

### [Sir Thaddeus — Local-first AI assistant](https://github.com/raydeStar/sir-thaddeus)

A private AI assistant and agent workspace for Windows. Connect local models
through LM Studio, Ollama, or another OpenAI-compatible endpoint, then work with
permissioned MCP tools, durable memory, a Markdown knowledge base, and visible
execution traces.

Sir Thaddeus is also my testbed for improving what a fixed model can accomplish
through better tools, retrieval, and verification. The
[public research method](https://github.com/raydeStar/sir-thaddeus/blob/master/docs/RESEARCH_METHOD.md)
documents paired experiments, repeat checks, and validation on unseen tasks.

**Built with:** C#/.NET, React, MCP, local LLMs.

### [Reference Asset Compiler — AI image-to-3D pipeline](https://github.com/raydeStar/reference-asset-compiler)

A pipeline connecting reference images to 3D assets through Hunyuan3D,
Blender, and Unreal Engine 5. It brings geometry generation, PBR texturing,
retopology, rigging, deformation checks, and engine import into a workflow with
review gates and traceable artifacts.

The engineering focus is reproducibility: record which reference, mesh,
texture, and approval produced each asset. Human visual review remains part of
the process. Explore [Stillwater](https://markbhall.dev/stillwater/), the browser
showcase, to see the assets in a Three.js scene.

**Built with:** Python, Blender, Hunyuan3D, Unreal Engine 5, Three.js.

### [Framewright — AI storyboarding & film pre-production](https://github.com/raydeStar/framewright)

A local-first creative workspace for planning shots, maintaining character and
world references, reviewing generated images, staging 3D scenes, and assembling
animated takes. Immutable media versions and explicit approvals keep creative
decisions attached to the work they describe.

The architecture combines a .NET backend, a React workspace, SQLite, and
recoverable provider jobs. The first Windows release is available; individual
generation integrations have documented preview and validation status.

**Built with:** C#/.NET, React, TypeScript, SQLite, ComfyUI adapters.

### [Local Benchmark Runner — LLM & AI agent evaluation](https://github.com/raydeStar/local-benchmark-runner-public)

An evaluation harness designed to reduce benchmark contamination and measure
verified task completion. It uses fabricated evidence, sealed task banks,
hashes published before measurement, and statistics that account for related
test cases. It works with OpenAI-compatible model endpoints.

The public repository includes the methodology and a retired benchmark bank
for inspecting and reproducing the evaluation process.

**Built with:** Python, paired experiments, deterministic verification.

## More projects

- **[Grand Adventure Engine](https://github.com/raydeStar/grand-adventure-engine)** —
  A self-hosted AI game master and multiplayer RPG for Discord and the web.
  A deterministic C# engine owns combat, dice, quests, and persistent state;
  the language model narrates the results. Includes a WebMCP co-DM workflow
  with human approval for game-state changes.
- **[HireZero](https://hirezero.app/)** — An early-preview marketing employee
  for founders, built around research, campaign drafts, revision history, and
  explicit publishing decisions. The
  [public source](https://github.com/raydeStar/marketing-hire) combines a .NET
  host, React cockpit, and an OpenClaw employee.

## Merged open-source contributions

- **[OpenClaw: fix Workshop skill diagnostics](https://github.com/openclaw/openclaw/pull/145396)** —
  Fixed full Doctor lint incorrectly flagging relocated skills by resolving
  their paths against the original filesystem while inspecting a database snapshot.
- **[Unsloth Zoo: DiffusionGemma reasoning channels](https://github.com/unslothai/unsloth-zoo/pull/769)** —
  Separated reasoning from answer text in the OpenAI-compatible shim, including
  streaming markers split across chunk boundaries.

## How I build

- Keep rules, permissions, and state changes in code that can be tested.
- Make sources, tool actions, approvals, and failure states inspectable.
- Compare changes against fixed baselines and validate on unseen tasks.
- Publish limitations alongside results, and distinguish prototypes from releases.

## Writing & contact

I write about local AI, agent architecture, MCP, LLM evaluation, and trustworthy
software at **[markbhall.dev](https://markbhall.dev/)**. For professional contact,
find me on **[LinkedIn](https://www.linkedin.com/in/mhall0808/)**.

*Local models. Useful tools. Receipts for the magic.*
