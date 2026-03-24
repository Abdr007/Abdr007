<div align="center">

<br>

# ABDR

**Systems engineer. Building autonomous trading infrastructure on Solana.**

I design deterministic execution systems where every parameter comes from chain state,
every decision passes through safety gates, and every outcome feeds back into learning.

<br>

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white" />
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />

<br><br>

[![X](https://img.shields.io/badge/@Dev__ABDR-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/Dev_ABDR)
[![GitHub](https://img.shields.io/badge/Abdr007-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdr007)

<br>

---

<br>

### Currently Building

<br>

<a href="https://github.com/Abdr007/flash-terminal">
  <img src="https://img.shields.io/badge/Flash_Terminal-v1.0.5-26d97f?style=for-the-badge" />
</a>

<br><br>

**Deterministic on-chain trading infrastructure for Solana perpetual futures.**

Full execution engine with an autonomous Q-learning agent, 10-layer safety stack, and every value derived from chain state. Not a wrapper. Not a dashboard. A trading system.

<br>

<table>
<tr>
<td align="center"><strong>32</strong><br><sub>Live Markets</sub></td>
<td align="center"><strong>1,926</strong><br><sub>Test Assertions</sub></td>
<td align="center"><strong>10</strong><br><sub>Safety Layers</sub></td>
<td align="center"><strong>0</strong><br><sub>Fabricated Values</sub></td>
</tr>
</table>

<br>

```
flash [live] > open 2x long SOL $100

  CONFIRM TRANSACTION
  ─────────────────────────────────
  Market:      SOL LONG
  Leverage:    2x
  Collateral:  $100.00
  Size:        $200.00
  Fees:        Open: $0.16 | Est. close: $0.16
  Liq Distance: 48.2%

  Type "yes" to sign or "no" to cancel
```

<br>

| System | What It Does |
|:-------|:-------------|
| **Autonomous Agent** | Q-learning with 36 entry states, 540 exit states. Learns what works, disables what doesn't. |
| **Signal Fusion** | 6 strategies (momentum, mean-rev, whale, volume, funding, microstructure) combined via Bayesian fusion |
| **Edge Validation** | 200-trade production validator. Strategies below 20bps EV auto-disable. |
| **Signing Guard** | Pre-sign confirmation, per-trade limits, rate limiting (10/min, 3s delay) |
| **Circuit Breaker** | Halts trading on session/daily loss thresholds. Manual reset required. |
| **Kill Switch** | Master toggle. Blocks all trade operations. Monitoring continues. |
| **TX Pipeline** | Program whitelist, instruction freeze, on-chain simulation before broadcast |
| **Crash Recovery** | Trade journal with pending TX verification on restart |
| **State Reconciliation** | Blockchain-authoritative position sync every 60s |
| **RPC Failover** | Multi-endpoint with slot lag detection and leader-aware TPU routing |

<br>

<a href="https://github.com/Abdr007/flash-terminal">Repository</a>&nbsp;&nbsp;&middot;&nbsp;&nbsp;<a href="https://flash-terminal-docs.vercel.app">Documentation</a>&nbsp;&nbsp;&middot;&nbsp;&nbsp;<a href="https://www.npmjs.com/package/flash-terminal">npm</a>

<br>

---

<br>

### Projects

<br>

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/Abdr007/flash-terminal">Flash Terminal</a></h3>
<p align="center">Autonomous trading engine for Flash Trade perpetuals on Solana</p>
<p align="center">
<img src="https://img.shields.io/badge/TypeScript-black?style=flat-square&logo=typescript" />
<img src="https://img.shields.io/badge/Solana-black?style=flat-square&logo=solana" />
</p>
<p align="center"><sub>Q-learning agent &middot; 10-layer safety &middot; On-chain execution &middot; 32 markets &middot; 1,926 tests</sub></p>

</td>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/Abdr007/nexus">Nexus</a></h3>
<p align="center">AI-powered crypto intelligence platform with real-time market data</p>
<p align="center">
<img src="https://img.shields.io/badge/TypeScript-black?style=flat-square&logo=typescript" />
<img src="https://img.shields.io/badge/AI-black?style=flat-square&logo=openai" />
</p>
<p align="center"><sub>Multi-LLM routing &middot; Market analysis &middot; Glassmorphic UI</sub></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/Abdr007/flash-risk-engine">Flash Risk Engine</a></h3>
<p align="center">Read-only risk intelligence engine for Flash Trade perpetuals</p>
<p align="center">
<img src="https://img.shields.io/badge/TypeScript-black?style=flat-square&logo=typescript" />
<img src="https://img.shields.io/badge/Solana-black?style=flat-square&logo=solana" />
</p>
<p align="center"><sub>Liquidation risk &middot; Position monitoring &middot; Protocol inspection</sub></p>

</td>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/Abdr007/prism-ai">Prism AI</a></h3>
<p align="center">Cross-exchange AI risk intelligence for perpetual futures</p>
<p align="center">
<img src="https://img.shields.io/badge/TypeScript-black?style=flat-square&logo=typescript" />
<img src="https://img.shields.io/badge/AI-black?style=flat-square&logo=openai" />
</p>
<p align="center"><sub>Multi-exchange &middot; Risk scoring &middot; AI analysis</sub></p>

</td>
</tr>
</table>

<br>

---

<br>

### What I Build

<br>

</div>

```
TRADING SYSTEMS        Autonomous agents, deterministic execution, on-chain TX pipelines
BLOCKCHAIN INFRA       RPC failover, state reconciliation, protocol-level integration
RISK ENGINEERING       Circuit breakers, exposure controls, signing guards, kill switches
LEARNING SYSTEMS       Q-learning policies, edge validation, strategy pruning, regime detection
CLI TOOLING            Terminal interfaces, protocol inspectors, observability engines
```

<div align="center">

<br>

---

<br>

### Design Principles

<br>

</div>

```
Deterministic over probabilistic.      Every trade follows a fixed, auditable pipeline.
Chain state over local state.           Blockchain is the single source of truth.
Safety as infrastructure.               Risk gates are not optional. They're load-bearing.
Learning from outcomes.                 Systems that measure their own edge and adapt.
Bounded by design.                      Every cache, buffer, and retry has a hard limit.
```

<div align="center">

<br>

---

<br>

<img src="https://github-readme-stats.vercel.app/api?username=Abdr007&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=26d97f&icon_color=26d97f&text_color=c9d1d9" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abdr007&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=26d97f&text_color=c9d1d9" width="48%" />

<br><br>

---

<br>

<sub>Building open infrastructure for the Flash Trade ecosystem &middot; Open to collaborations</sub>

<br>

</div>
