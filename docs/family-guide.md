# Family guide

How the twelve Awesome-llms-labs lists fit together — and which one to open first.

## The model lists

Four lists slice the model landscape along different axes, deliberately:

- **awesome-flagship-llms** — the frontier: the biggest, most capable models, benchmark notes, verified pricing.
- **awesome-flash-llms** — the efficiency tier: Flash-class models that trade a little capability for a lot of cost savings, plus where to deploy them.
- **awesome-fast-llms** — the speed axis: which models, providers, engines, and techniques maximize tokens/sec and minimize latency.
- **awesome-free-llms** — the price axis at zero: free API tiers, free chat apps, and open-weight models you can run locally.

Rule of thumb: flagship = "what's the best", flash = "what's the cheapest per unit of quality", fast = "what's the quickest", free = "what costs nothing".

## The decision & agent cluster

- **awesome-decisions-llms** — models, benchmarks, and frameworks for *decision-making*: game-theoretic evals, multi-criteria choice, debate pipelines.
- **awesome-ai-agents** — the agent ecosystem: frameworks, tools, and platforms for building agents.
- **awesome-jev** — a deep dive on one decision engine: TypeSafe's Jev (System One), with docs and runnable examples.
- **awesome-prompt-engineering** *(in progress)* — techniques and patterns for steering model behavior.

## The infrastructure cluster

- **awesome-ai-sandboxes** — sandboxes for running untrusted or generated code: managed, open-source, browser-based.
- **awesome-microVM** — the microVM substrate underneath many sandboxes, from Firecracker to macOS-native runtimes.
- **awesome-llm-observability** *(in progress)* — tracing, evals-ops, and monitoring for LLM systems in production.

## The frontier cluster

- **awesome-multimodal-llms** *(in progress)* — models that see: vision- and multimodal-capable LLMs.

## The house standard

Every list in the family follows the same contract:

- **Public and MIT licensed**, with machine-readable JSON under `data/`.
- **Verified or flagged**: entries are checked against official sources; anything unverified is explicitly marked — specs are never invented.
- **Green CI**: link-checked and data-validated on every push.
- **Docs + CONTRIBUTING**: each repo explains its scope and how to add entries.
