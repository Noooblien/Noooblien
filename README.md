# Noooblien

I work on execution layers, zk systems, and infra that has to handle real load.

---

## Stuff I'm building

**zkEVM prover**
Trying to actually prove EVM execution end-to-end. Not just small circuits — full state transitions, batching, making it practical.

**ScanX**
Indexer for multiple EVM chains.
Stores everything — blocks, txs, logs, traces.
Built for speed because most indexers are slow or incomplete.

**Sentinel**
Execution proxy layer.
Mostly about keeping things modular and not tightly coupled.

**Code Intelligence Engine**
Parses large codebases into structured graphs (calls, flows, dependencies).
Lets a model reason over execution instead of raw text.
Goal: debugging + deep understanding, not autocomplete.

**Low-latency LLM runtime**
Custom setup for running 7B models locally.
Focus on:

* fast inference
* memory efficiency
* streaming + tool usage

Making small models actually usable for real workflows.

---

**Task Execution Engine**
System where models don’t just suggest — they execute.
Handles:

* planning → action → verification loop
* file system + API operations
* failure recovery

Goal: reliable agents, not demo agents.

---

## Stack

Go, Rust, TypeScript
EVM, Cosmos SDK
zk (Groth16, circuits)
Distributed systems
LLMs (local inference, systems-level integration)

---

## Links

GitHub: https://github.com/Noooblien
Email: [rsm050501@gmail.com](mailto:rsm050501@gmail.com)

---

That’s it.
