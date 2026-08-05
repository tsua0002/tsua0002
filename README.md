# Thomas Suau

AI solution architect and research engineer. I work on **agentic systems**, **formal methods**, and the **mathematical semantics of learned representations**, with **Bitcoin (UTXO / Script)** as my anchored application domain for verifiable coordination.

**Themes:** geometric and relational semantics for **LLMs** (compositionality, limits, and obstructions in high-dimensional learned systems, via algebraic topology and differential geometry) • **agent coordination**: MCP-driven tool use, multi-agent orchestration, trust boundaries • **policy-as-code**: turning regulation and protocol rules into executable, auditable artifacts • closing the semantic gap between off-chain intent and on-chain truth.

**Why the pairing:** LLMs and Bitcoin transactions sit at opposite ends of the same question. One is an open, high-dimensional system where structure must be discovered; the other is a rigid, auditable state-transition system where structure is explicit. Both benefit from invariant-centric explanations. I study each with the other in view.

---

## Flagship work

**[Code The Law](https://codethelaw.eu)** — a fully automated agentic pipeline that translates articles of EU financial regulation (MiCA) into executable proof-of-concept applications. One prototype per day through a complete CI/CD chain: generation, review, deployment, publication. A working demonstration of policy-as-code applied to regulation.

**[BTSL — Bitcoin Transaction Schema Language](https://github.com/tsua0002/btsl-standard)** — a declarative policy-as-code validation layer on top of BIP174/BIP370 (PSBT): schemas describe expected structure, `calc` + `ASSERT` encode economic invariants, external checkers get an explicit predicate set for zero-trust replay.
**Release:** [v1.0.0 — Reference Specification [FINAL]](https://github.com/tsua0002/btsl-standard/releases/tag/v1.0.0) · **Live explorer:** [BTSL Playground](https://btsl-playground.vercel.app/)

---

## Selected repositories & writing

| Focus | Link |
|------|------|
| Applied AI writing: tools in LLMs, a taxonomy of agentic workflows, *Intelligere* (essay on agentic AI) | [LinkedIn](https://www.linkedin.com/in/thomas-suau-92932889?) |
| Design note: a domain-specialized LLM (corpus construction, open-weights fine-tuning, tool layer, evaluation) | [DelvingBitcoin](https://delvingbitcoin.org/u/tsua00021/summary) |
| Formal semantics for metaprotocols (semantic-gap framing) | [formal-metaprotocol-semantics](https://github.com/tsua0002/formal-metaprotocol-semantics) |
| Curated research notes (socio-technical layer, permanence, censorship resistance) | [bitcoin_research](https://github.com/tsua0002/bitcoin_research) |

---

## Agents & coordination (research)

Two agentic systems in production, embodying two orchestration philosophies:

- **Code The Law pipeline**: a daily autonomous routine driven by declarative instruction files (BOOT.md), decomposed into dedicated tasks through to deployment. Instruction-as-code orchestration.
- **p2p-mom** (Prompt2Production): a Slack-driven blueprint runner built on a fork of [pi](https://github.com/badlogic/pi-mono), Mario Zechner's open-source coding agent. Inspired by Stripe's internal agent workflows, with deliberately higher autonomy calibrated to a lower risk profile: one run takes a blueprint through to a complete project, typically a PR plus a Vercel deployment. Private for now.

Broader experimentation with **Model Context Protocol (MCP)** tool use, multi-agent setups, and sovereign agent design. Research questions: coordination surfaces, trust boundaries, autonomy calibration against risk profile, and anchoring assertions in verifiable state rather than mutable off-chain records.

---

## Background (compact)

- **Education:** Mathematics & Applications (Master, research & teaching track) — [AMU](https://www.univ-amu.fr/) • Computer Science (M1) — [ULB](https://www.ulb.be/)
- **Industry:** independent AI advisory practice (architecture, agentic pipelines, LLMOps) • CTO (Tokenomeme, infra / GCP) • blockchain dev — [Juneo](https://github.com/Juneo-io)
- **Community:** speaker & workshop lead — [DAO Brussels](https://github.com/daobrussels), [UrLab](https://github.com/UrLab) (ULB hackerspace) • [CIVIS](https://civis.eu/en) ambassador (AMU)

---

## Stack & research tools

**AI & agents**
[![Anthropic](https://img.shields.io/badge/Claude_/_Anthropic-D97757?style=for-the-badge)]() [![MCP](https://img.shields.io/badge/Model_Context_Protocol-333?style=for-the-badge)]() [![PI coding agents](https://img.shields.io/badge/PI_coding_agents-6f42c1?style=for-the-badge)]() [![LLMOps](https://img.shields.io/badge/LLMOps-2496ED?style=for-the-badge)]()

**Core dev**
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)]() [![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)]() [![Rust](https://img.shields.io/badge/rust-%23DEA584.svg?style=for-the-badge&logo=rust&logoColor=black)]() [![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)]()

**Formal methods**
[![Agda](https://img.shields.io/badge/Agda-555555?style=for-the-badge&logo=haskell&logoColor=white)]() [![Category Theory](https://img.shields.io/badge/Applied_Category_Theory-FF69B4?style=for-the-badge)]() [![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)]()

**Bitcoin / PSBT**
[![Bitcoin](https://img.shields.io/badge/Bitcoin-F79327?style=for-the-badge&logo=bitcoin&logoColor=white)]() [![PSBT](https://img.shields.io/badge/PSBT_BIP174_/_370-333?style=for-the-badge)]() [![Taproot](https://img.shields.io/badge/Taproot_%2F_MAST-E89933?style=for-the-badge&logo=bitcoin&logoColor=white)]()

---

## Conviction

Automated systems, whether trading agents, coding agents, or regulatory pipelines, only stay honest if their semantics are explicit and their artifacts verifiable. I build schemas, proofs, and static pipelines so that what humans intend and what machines execute remain provably aligned. Bitcoin's consensus layer is my reference case: a long-horizon anchor where this discipline is not optional.

---

_Open to collaboration and critique on the mathematical semantics of LLMs, agent coordination, policy-as-code, Bitcoin formalization, and PSBT / BTSL._
