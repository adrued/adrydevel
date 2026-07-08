<div align="center">

# adrydevel

**Building Bastion — autonomous, verifiable AI trading systems on Robinhood Chain.**

</div>

<p align="center">
  <a href="https://github.com/adrydevel"><img src="https://img.shields.io/badge/GitHub-adrydevel-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://bastiontrade.xyz"><img src="https://img.shields.io/badge/Site-bastiontrade.xyz-111111?style=flat-square&logo=vercel&logoColor=white" alt="Site"></a>
</p>

---

I build autonomous trading systems and on-chain agent infrastructure. Focused on agent swarms, verifiable reasoning, and tokenized-asset trading on Robinhood Chain. Reasoning runs on open-weights ([Nous Research](https://nousresearch.com) Hermes). Most of what I build ends up open source.

## Currently building

- **[bastion](https://github.com/adrydevel/bastion)** — autonomous, verifiable AI fund for tokenized stocks on Robinhood Chain. ![stars](https://img.shields.io/github/stars/adrydevel/bastion?style=flat-square&label=&color=181717)

## What I believe

- **Auditable beats autonomous.** — an agent that cannot show its evidence trail is a demo, not infrastructure.
- **Consensus over conviction.** — no single agent should move capital; a quorum should, or the desk stays flat.
- **Non-custodial or nothing.** — keys stay on the operator's machine, the chain stays the source of truth.

## Selected open-source work

### Agent Infrastructure

| Repo | What it does | Signal |
|------|--------------|--------|
| **[bastion](https://github.com/adrydevel/bastion)** | Swarm of AI agents that trades tokenized stocks and proves every trade on-chain | ![stars](https://img.shields.io/github/stars/adrydevel/bastion?style=flat-square&label=%E2%98%85&color=181717) |
| **[robinhood-chain-mcp](https://github.com/adrydevel/robinhood-chain-mcp)** | MCP server — typed tools that let any agent read Stock Tokens and place swaps | ![stars](https://img.shields.io/github/stars/adrydevel/robinhood-chain-mcp?style=flat-square&label=%E2%98%85&color=181717) |

### SDKs & Tooling

| Repo | What it does | Signal |
|------|--------------|--------|
| **[robinhood-chain-sdk](https://github.com/adrydevel/robinhood-chain-sdk)** | Typed TypeScript client — Stock Tokens, oracle NAV, swaps | ![stars](https://img.shields.io/github/stars/adrydevel/robinhood-chain-sdk?style=flat-square&label=%E2%98%85&color=181717) |
| **[bastion-rs](https://github.com/adrydevel/bastion-rs)** | Rust port of the agent core — small single binary | ![stars](https://img.shields.io/github/stars/adrydevel/bastion-rs?style=flat-square&label=%E2%98%85&color=181717) |

### Curation

| Repo | What it does | Signal |
|------|--------------|--------|
| **[awesome-robinhood-chain](https://github.com/adrydevel/awesome-robinhood-chain)** | Curated ecosystem list for Robinhood Chain | ![stars](https://img.shields.io/github/stars/adrydevel/awesome-robinhood-chain?style=flat-square&label=%E2%98%85&color=181717) |

## Build surface

```text
Agents   →  swarm councils, quorum voting, policy gates, Hermes-native routing
Trading  →  Kelly/CVaR risk kernels, regime detection, execution infra
Chain    →  Robinhood Chain (viem), tokenized stocks, on-chain proof anchoring
Proof    →  keccak256 attestation, TEE-signed reasoning, provenance trails
```

---

<div align="center">

**Building agent infrastructure or autonomous trading systems?**

[bastiontrade.xyz](https://bastiontrade.xyz)

</div>
