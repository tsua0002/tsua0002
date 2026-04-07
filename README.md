# Thomas Suau

Research engineer at the intersection of **applied category theory**, **Bitcoin (UTXO / Script)**, and **coordination systems** (protocols, agents).

**Themes:** closing the semantic gap between off-chain intent and on-chain truth • formal / auditable meta-protocols • UTXO-native design (security through structure, not VM complexity) • **relational / geometric semantics** for **LLMs** and for **protocol objects** (algebraic topology, differential geometry, Galois-theoretic angles) • **PI coding agents** in the research loop.

**Mathematical semantics:** I use **algebraic topology**, **differential geometry**, and **Galois-theoretic** perspectives to study **semantic structure**—both for **LLMs** (compositionality, limits, and obstructions in high-dimensional learned systems) and for **Bitcoin transactions** as rigid, auditable state transitions. The parallel is intentional: both settings benefit from **invariant-centric** explanations and explicit structure, with Bitcoin as the anchored reference case and LLMs as the open, high-dimensional one.

---

## Flagship work

**[BTSL — Bitcoin Transaction Schema Language](https://github.com/tsua0002/btsl-standard)** — declarative “policy-as-code” layer on top of **BIP174/BIP370 (PSBT)**: schemas describe expected structure, `calc` + `ASSERT` encode economic invariants, external Checkers get an explicit predicate set for zero-trust replay.  

**Release (normative baseline):** [v1.0.0 — Reference Specification [FINAL]](https://github.com/tsua0002/btsl-standard/releases/tag/v1.0.0) — spec §9.3.1 checker predicates (**S-1…A-5**), full **BTSL_ERR_00…13**, implementation guide + checker annex.

**Live explorer:** [BTSL Playground](https://btsl-playground.vercel.app/) (Maker + Validator paths; implementation is tracked to the FINAL spec over time).

---

## Selected repositories & writing

| Focus | Link |
|------|------|
| Formal semantics for Bitcoin metaprotocols (Ordinals / Inscriptions, semantic-gap framing) | [formal-metaprotocol-semantics](https://github.com/tsua0002/formal-metaprotocol-semantics) |
| Curated Bitcoin research notes (socio-technical layer, permanence, censorship resistance) | [bitcoin_research](https://github.com/tsua0002/bitcoin_research) |
| Technical posts & **French translations** of Bitcoin research (ecosystem outreach) | [LinkedIn](https://www.linkedin.com/in/thomas-s-92932889/) |

---

## Agents & decentralized coordination (research)

Experimentation with **Model Context Protocol (MCP)**-driven tool use, multi-agent setups, and “sovereign” agent design—research questions: coordination surfaces, trust boundaries, and anchoring assertions in UTXO-time rather than mutable off-chain state. Exploratory deployments across social surfaces and Bitcoin-adjacent tooling (e.g. [lasereyes](https://lasereyes.build)).

---

## Background (compact)

- **Education:** Computer Science (M1) — [AMU](https://www.univ-amu.fr/) & [ULB](https://www.ulb.be/) • **Mathematics & Applications** (Master, research & teaching track) — AMU  
- **Industry:** CTO (Tokenomeme, infra / GCP) • Blockchain dev — [Juneo](https://github.com/Juneo-io) (Avalanche-class fork; e.g. [juneojs-examples](https://github.com/tsua0002/juneojs-examples))  
- **Community:** Speaker supervisor — [UrLab](https://github.com/UrLab) (ULB hackerspace) • [CIVIS](https://civis.eu/en) ambassador (AMU) • steward / contributor — [DAO Brussels](https://github.com/daobrussels) ([manifesto](https://dao.brussels/manifesto))

---

## Stack & research tools

**Formal methods**  
[![Agda](https://img.shields.io/badge/Agda-555555?style=for-the-badge&logo=haskell&logoColor=white)]() [![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)]() [![Category Theory](https://img.shields.io/badge/Applied_Category_Theory-FF69B4?style=for-the-badge)]()

**Core dev**  
[![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)]() [![Rust](https://img.shields.io/badge/rust-%23DEA584.svg?style=for-the-badge&logo=rust&logoColor=black)]() [![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)]() [![PI coding agents](https://img.shields.io/badge/PI_coding_agents-6f42c1?style=for-the-badge)]()

**Bitcoin / PSBT**  
[![Bitcoin](https://img.shields.io/badge/Bitcoin-F79327?style=for-the-badge&logo=bitcoin&logoColor=white)]() [![PSBT](https://img.shields.io/badge/PSBT_BIP174_/_370-333?style=for-the-badge)]() [![Taproot](https://img.shields.io/badge/Taproot_%2F_MAST-E89933?style=for-the-badge&logo=bitcoin&logoColor=white)]()

**Workflow**  
[![Neovim](https://img.shields.io/badge/NeoVim-%2357A143.svg?&style=for-the-badge&logo=neovim&logoColor=white)]() [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)]() [![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)]()

---

## Conviction

Bitcoin’s consensus layer is a **long-horizon anchor for truth and coordination**. I work on **explicit semantics and verifiable artifacts** (schemas, proofs, static pipelines) so that things built *above* that anchor stay honest when humans and agents automate the middle layers—without smuggling account-model assumptions back into UTXO-native designs.

---

_Open to collaboration and critique on Bitcoin formalization, PSBT / BTSL, category-theoretic protocol semantics, mathematical semantics of LLMs, and agent coordination._
