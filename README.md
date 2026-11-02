# Ranadhir Ghosh

**Principal Research Scientist, AI & Innovation** — I build AI systems in public: first principles on the whiteboard → built live in the editor → measured honestly, failures included.

25+ years in AI research and engineering: agentic systems, LLM inference, evaluation, and the unglamorous work of measuring whether any of it actually works. Everything below is runnable code with published numbers — including the negative results.

## Flagship results

| Project | What it is | Measured result |
|---|---|---|
| [agentic-systems-lab](https://github.com/ranadhir19/agentic-systems-lab) | 21 original agentic-AI systems with seeded experiments | Each system ships its own measured result and an honest conclusion — what worked, what didn't |
| [llm-reasoning-and-planning](https://github.com/ranadhir19/llm-reasoning-and-planning) | Companion lab to *Demystifying LLM Reasoning, Part 2* | Real model (Qwen2.5-0.5B-Instruct, run in CI): direct 0/14 → chain-of-thought 6/14 → majority vote 9/14 → verifier best-of-9 5/14 — the verifier lost |
| [llm-reasoning-demystified](https://github.com/ranadhir19/llm-reasoning-demystified) | Part 1: what happens inside the model when arithmetic goes wrong | All 32 discount problems generated the same multiplier (0.8) regardless of the stated rate; causal patching isolates the failure to specific layers |
| [mcp-server-lab](https://github.com/ranadhir19/mcp-server-lab) | An MCP server a model can actually use, tested against real model behaviour | Companion lab to a video certified 96/100 under independent review |
| [agent-eval-lab](https://github.com/ranadhir19/agent-eval-lab) | An eval harness designed to catch broken agents — and broken benchmarks | Companion lab to a video certified 96/100 under independent review |
| [fairness-transport-accounting](https://github.com/ranadhir19/fairness-transport-accounting) | Research deposit: what fairness numbers can and cannot survive distribution shift | Headline forecasting claim falsified under pre-registration; rebuilt as a bound-only transport-accounting result and submitted |

## Also here

- [sentinel-scan](https://github.com/ranadhir19/sentinel-scan) — a scanning tool for AI-generated code and configs
- [llm-inference-engine](https://github.com/ranadhir19/llm-inference-engine) — 8 advanced LLM inference systems as an installable package (`llm-inference-lab`)
- [horizonkit](https://github.com/ranadhir19/horizonkit) — tools for time-horizon measurement of AI agents

## Watch it built

Every flagship here has a full build on **The Architect's AI Workshop** (YouTube): derivations on the whiteboard, the build live in the editor, and the measurements — failures included.

- YouTube: https://www.youtube.com/@ArchitectsAIWorkshop
- LinkedIn: https://www.linkedin.com/in/dr-ranadhir-ghosh-bbb7b827

*No hype. Derivations, builds, and receipts.*
