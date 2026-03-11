<div align="center">

<br>

# ABDR

**Builder of deterministic trading infrastructure on Solana.**

Software engineer focused on blockchain protocol integration, transaction pipelines, and systems reliability.

<br>

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white" />
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />

<br><br>

[![X](https://img.shields.io/badge/@Dev__ABDR-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/Dev_ABDR)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdr007)

<br>

---

<br>

### Featured Project

<br>

<a href="https://github.com/Abdr007/flash-terminal">
  <img src="https://img.shields.io/badge/Flash_Terminal-v1.0.0-26d97f?style=for-the-badge" />
</a>

**Deterministic CLI Trading Interface for Flash Trade on Solana**

Production-grade command line terminal for executing leveraged trades on the Flash Trade perpetual futures protocol. Built with strict TypeScript, deterministic execution, and layered safety systems.

<br>

<table>
<tr>
<td align="center"><strong>28K+</strong><br><sub>Lines of TypeScript</sub></td>
<td align="center"><strong>462</strong><br><sub>Automated Tests</sub></td>
<td align="center"><strong>94/100</strong><br><sub>Audit Score</sub></td>
<td align="center"><strong>0</strong><br><sub>Critical Issues</sub></td>
</tr>
</table>

<br>

```
flash [live] > open 5x long SOL $500

  CONFIRM TRANSACTION
  ─────────────────────────────────
    Market:      SOL LONG
    Leverage:    5x
    Collateral:  $500.00
    Size:        $2,500.00
    Est. Fee:    $2.00

    Est. Entry:  $148.52
    Est. Liq:    $121.79
    Distance:    18.0%
    Risk:        HIGH

  Type "yes" to sign or "no" to cancel
```

<br>

| System | Description |
|:-------|:------------|
| **Signing Guard** | Rate limiting, trade limits, confirmation gates, audit logging |
| **Circuit Breaker** | Halts trading on configurable loss thresholds |
| **Kill Switch** | Emergency stop for all trade operations |
| **Transaction Pipeline** | Program whitelist, instruction freeze, pre-send simulation |
| **Crash Recovery** | Trade journal with atomic writes, startup verification |
| **State Reconciliation** | Blockchain-authoritative position sync |
| **RPC Failover** | Multi-endpoint with slot lag detection and leader-aware routing |
| **TP/SL Automation** | Take-profit and stop-loss with spike protection |

<br>

<a href="https://github.com/Abdr007/flash-terminal">Repository</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://flash-terminal-docs.vercel.app">Documentation</a>

<br>

---

<br>

### Projects

<br>

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/Abdr007/flash-terminal">Flash Terminal</a></h3>
<p align="center">Deterministic CLI trading terminal for Flash Trade perpetuals on Solana</p>
<p align="center">
<img src="https://img.shields.io/badge/TypeScript-black?style=flat-square&logo=typescript" />
<img src="https://img.shields.io/badge/Solana-black?style=flat-square&logo=solana" />
</p>
<p align="center"><sub>On-chain execution · Risk preview · RPC failover · Trade simulation · Protocol analytics</sub></p>

</td>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/Abdr007/nexus">Nexus</a></h3>
<p align="center">AI-powered crypto intelligence platform with real-time market data</p>
<p align="center">
<img src="https://img.shields.io/badge/TypeScript-black?style=flat-square&logo=typescript" />
<img src="https://img.shields.io/badge/AI-black?style=flat-square&logo=openai" />
</p>
<p align="center"><sub>Multi-LLM routing · Market analysis · Glassmorphic UI</sub></p>

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
<p align="center"><sub>Liquidation risk · Position monitoring · Protocol inspection</sub></p>

</td>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/Abdr007/prism-ai">Prism AI</a></h3>
<p align="center">Cross-exchange AI risk intelligence for perpetual futures</p>
<p align="center">
<img src="https://img.shields.io/badge/TypeScript-black?style=flat-square&logo=typescript" />
<img src="https://img.shields.io/badge/AI-black?style=flat-square&logo=openai" />
</p>
<p align="center"><sub>Multi-exchange · Risk scoring · AI analysis</sub></p>

</td>
</tr>
</table>

<br>

---

<br>

### Engineering Focus

**Trading Systems** — Deterministic execution, on-chain transaction pipelines, risk engines<br>
**Blockchain Infrastructure** — RPC failover, state reconciliation, protocol integration<br>
**CLI Tooling** — Terminal interfaces, protocol inspectors, observability tools<br>
**System Reliability** — Defensive engineering, crash recovery, bounded caches, audit logging

<br>

---

<br>

### Architecture Philosophy

```
Deterministic systems over probabilistic behavior.
Protocol-aligned calculations over reimplementation.
Defensive engineering over optimistic assumptions.
Blockchain state as the single source of truth.
```

<br>

---

<br>

<img src="https://github-readme-stats.vercel.app/api?username=Abdr007&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=26d97f&icon_color=26d97f&text_color=c9d1d9" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abdr007&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=26d97f&text_color=c9d1d9" width="48%" />

<br><br>

---

<br>

<sub>Open to collaborations · Building open infrastructure for the Flash Trade ecosystem</sub>

<br>

</div>
