## BitRouter - A Peer-to-Peer Intelligence Router

### Manifesto

Computers used to retrieve bytes. Now they generate tokens.

That is not an incremental improvement. It is a paradigm shift — the same magnitude as moving from physical mail to the internet, from gold to programmable money. The atomic unit of computing changed.

The routing infrastructure has not caught up.

BitTorrent routed bytes.
Bitcoin routed value.
Bittensor routes intelligence supply.
**BitRouter routes intelligence demand.**

Agents today are locked to single providers, paying opaque prices, generating no signal that makes the next call smarter. The centralized routing layer exists. The peer-to-peer version does not.

We are building toward that layer.

Starting with what is immediately real: an open intelligence router for LLM agents. Single binary. Zero infrastructure dependencies. Built in Rust.

Not a wrapper. Not a proxy. A foundation.

---

### Start Here

- [**bitrouter/bitrouter**](https://github.com/bitrouter/bitrouter) — The core router. Single binary, built in Rust. Routing, guardrails, observability, MCP gateway, and agentic payments.
- [**bitrouter/x402-kit**](https://github.com/bitrouter/x402-kit) — Rust SDK for x402 payment integration. The payment primitive for agent-to-agent and agent-to-API transactions.
- [**bitrouter/agent-skills**](https://github.com/bitrouter/agent-skills) — Agent Skills for Claude Code, Copilot, Cursor, and Codex. Give your agent the knowledge to register, configure, and serve on the BitRouter network.
- [**bitrouter/agents-database**](https://github.com/bitrouter/agents-database) — An open-source database of AI agents. Models have models.dev. Tools have MCP registries. Agents needed this.

### Participate

- **Use it** — `cargo install bitrouter` and point your agent harness at `localhost:8787`
- **Register your agent** — one TOML file, one PR at [agents.bitrouter.ai](https://agents.bitrouter.ai)
- **Build on it** — add a provider, extend guardrails, integrate a new protocol
- **Discuss it** — [Discord](https://discord.gg/G3zVrZDa5C) · [Issues](https://github.com/bitrouter/bitrouter/issues)

> The peer-to-peer layer gets built by the people who need it.
