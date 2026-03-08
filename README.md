# Abdul Rahman

I build developer tools and trading infrastructure for blockchain protocols.

My work focuses on reliable systems that interact with on-chain state — transaction pipelines, RPC failover, risk engines, and AI-assisted command interfaces.

---

## Current Work

### [Flash AI Terminal](https://github.com/Abdr007/flash-ai-terminal)

A command-line trading terminal for the [Flash Trade](https://www.flash.trade/) protocol on Solana.

Provides AI-assisted command parsing, real-time market analysis, risk monitoring, and safe on-chain execution. Designed for traders and protocol developers who need direct access to perpetual futures markets from the terminal.

**Scope:** 60+ source files across 20 subsystems — AI interpreter, multi-strategy scanner, transaction pipeline, RPC failover, protocol inspector, plugin system, and more.

---

## Focus Areas

- **Blockchain infrastructure** — RPC management, transaction pipelines, on-chain state reconciliation
- **Trading systems** — Position management, risk monitoring, market scanning, signal aggregation
- **Developer tooling** — CLI interfaces, protocol inspectors, dry-run simulation, plugin architectures
- **AI-assisted interfaces** — Natural language command parsing with structured validation

---

## Tech Stack

```
TypeScript    Solana/web3.js    Node.js    Flash SDK
Pyth Oracles  Zod               CLI/REPL   ESM
```

---

## Principles

- Infrastructure should be deterministic and auditable
- External data is untrusted until validated
- Blockchain state is authoritative over local state
- Every trade requires explicit confirmation before signing
- No fabricated data — live feeds only, graceful degradation on failure

---

## Contact

Open an issue on any of my repositories, or reach out through GitHub.
