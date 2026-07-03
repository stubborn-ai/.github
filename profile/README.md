# Stubborn AI

**Deterministic LLM context compiler for SCIP-indexed codebases.**

Architecture-led, AI-assisted engineering: the developer defines pipeline shape and contracts; AI implements most of the code; the product is **deterministic Python** — same SCIP → same context.

---

### Repositories

| Repository | Role | Status |
|------------|------|--------|
| [stubborn-hub](https://github.com/stubborn-ai/stubborn-hub) | Program docs & architecture | Active |
| [stubborn](https://github.com/stubborn-ai/stubborn) | Core compiler — SCIP → SQLite → prune → weave | **Beta** (`0.9.0b3`) |
| [stubborn-mcp](https://github.com/stubborn-ai/stubborn-mcp) | MCP server for agents | **Beta** (`0.1.0b1`) |

SCIP symbol graph → token-bounded stub text for agents and CI · Java-first beta

[Start here →](https://github.com/stubborn-ai/stubborn-hub/blob/main/docs/START-HERE.md)

---

### Optional consumer

Weak integration with [anchor-migration](https://github.com/anchor-migration) for legacy modernization runbooks — Stubborn is **not** part of the SSOT pipeline.
