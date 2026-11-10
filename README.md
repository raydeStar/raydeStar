# Mark Hall, AI engineer: agent reliability and evaluation

I'm **Mark Hall** (**raydeStar** on GitHub), a senior full-stack engineer who
builds **agent harnesses and evals that make AI agents measurably reliable**.
My focus is the part after the demo: proving an agent finishes the job, and
showing why. In [Sir Thaddeus](https://github.com/raydeStar/sir-thaddeus), the
same 1.2B local model went from **4/20 to 15/20** on a fresh verified-outcome
scorecard once the harness gave it the right tools, state and checks, and any
change that doesn't repeat on unseen tasks gets deleted. In
[HireZero](https://github.com/raydeStar/HireZero), agents act only through
approvals bound to the exact version reviewed, with budgets reserved before
every model call. I work in Python, TypeScript and C#/.NET on Azure, and I've
had fixes merged into OpenClaw and Unsloth Zoo.

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
- **[HireZero](https://github.com/raydeStar/HireZero)** —
  A company of AI employees (Developer, Marketing, Support and CEO) where every
  push, send, publish or spend waits for the owner's approval of the exact
  version reviewed, and each model call reserves its budget first. Built with
  C#/.NET and React. [Try the live demo](https://app.hirezero.app), hosted on Vultr.

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
