<div align="center">

<br>

# ABDR

**Systems engineer. Building trading infrastructure on Solana.**

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

### Featured Project

<br>

<a href="https://github.com/Abdr007/flash-terminal">
  <img src="https://img.shields.io/badge/Flash_Terminal-v1.2.3-26d97f?style=for-the-badge" />
</a>

<br><br>

**Production CLI for trading Solana perpetual futures on Flash Trade.**

97 commands. 32+ markets. Simulation mode. 10-layer safety stack. Published on npm.

<br>

<table>
<tr>
<td align="center"><strong>97</strong><br><sub>Commands</sub></td>
<td align="center"><strong>32+</strong><br><sub>Markets</sub></td>
<td align="center"><strong>1,743</strong><br><sub>Tests</sub></td>
<td align="center"><strong>48K</strong><br><sub>Lines of Code</sub></td>
</tr>
</table>

<br>

```
flash [sim] > open 5x long SOL $500

  CONFIRM TRANSACTION
  ─────────────────────────────────
  Market:      SOL LONG
  Leverage:    5x
  Collateral:  $500.00 USDC
  Size:        $2,500.00
  Est. Fee:    $2.00

  Proceed? [y/N]
```

<br>

| Layer | Purpose |
|:------|:--------|
| **Signing Guard** | Per-trade limits, rate limiter, audit log |
| **Circuit Breaker** | Halts trading on session/daily loss thresholds |
| **Kill Switch** | Master toggle — disables all trades instantly |
| **Pre-flight Simulation** | Every TX simulated on-chain before broadcast |
| **Program Whitelist** | Only Flash Trade + Solana system programs allowed |
| **RPC Failover** | Multi-endpoint with slot lag detection |
| **State Reconciliation** | Blockchain-authoritative sync every 60s |

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
<p align="center">CLI trading terminal for Flash Trade perpetuals on Solana</p>
<p align="center">
<img src="https://img.shields.io/badge/TypeScript-black?style=flat-square&logo=typescript" />
<img src="https://img.shields.io/badge/Solana-black?style=flat-square&logo=solana" />
</p>
<p align="center"><sub>97 commands &middot; 10-layer safety &middot; On-chain execution &middot; 1,743 tests</sub></p>

</td>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/Abdr007/flash-risk-engine">Flash Risk Engine</a></h3>
<p align="center">Read-only risk intelligence engine for Flash Trade perpetuals</p>
<p align="center">
<img src="https://img.shields.io/badge/TypeScript-black?style=flat-square&logo=typescript" />
<img src="https://img.shields.io/badge/Solana-black?style=flat-square&logo=solana" />
</p>
<p align="center"><sub>Liquidation risk &middot; Position monitoring &middot; Protocol inspection</sub></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/Abdr007/nexus">Nexus</a></h3>
<p align="center">AI-powered crypto intelligence platform with real-time market data</p>
<p align="center">
<img src="https://img.shields.io/badge/TypeScript-black?style=flat-square&logo=typescript" />
<img src="https://img.shields.io/badge/AI-black?style=flat-square&logo=openai" />
</p>
<p align="center"><sub>Multi-LLM routing &middot; Market analysis &middot; Glassmorphic UI</sub></p>

</td>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/Abdr007/prism-ai">Prism AI</a></h3>
<p align="center">Cross-exchange risk intelligence for perpetual futures</p>
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
TRADING SYSTEMS        Deterministic execution, on-chain TX pipelines, safety infrastructure
BLOCKCHAIN INFRA       RPC failover, state reconciliation, protocol-level integration
RISK ENGINEERING       Circuit breakers, exposure controls, signing guards, kill switches
CLI TOOLING            Terminal interfaces, protocol inspectors, market monitoring
```

<div align="center">

<br>

---

<br>

### Principles

<br>

</div>

```
Deterministic over probabilistic.      Every trade follows a fixed, auditable pipeline.
Chain state over local state.           Blockchain is the single source of truth.
Safety as infrastructure.               Risk gates are not optional. They're load-bearing.
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

<sub>Building open infrastructure for the Flash Trade ecosystem</sub>

<br>

</div>
