# Cairo Starklings Exercises

![Language](https://img.shields.io/badge/language-Cairo-blue)
![StarkNet](https://img.shields.io/badge/powered%20by-StarkNet-purple)
![Status](https://img.shields.io/badge/status-learning-success)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

_**My personal solutions for the Starklings exercises**_

---

## 📌 What is Cairo?
[Cairo](https://www.cairo-lang.org/) is a **Turing-complete programming language** designed for writing **provable programs**.  
It is the core language used to build **scalable and verifiable applications** on blockchain networks. Cairo allows developers to write programs that can be verified using **zero-knowledge proofs (ZKPs)**, making it a foundational technology for **scalability** in the blockchain ecosystem.

Key points:
- Built for **validity proofs** and **STARKs** (Scalable Transparent ARguments of Knowledge).
- Used to write **smart contracts** on StarkNet.
- Provides **low-level control** while supporting higher-level abstractions.

---

## 🌌 What is StarkNet?
[StarkNet](https://starknet.io/) is a **Layer 2 scaling solution** for Ethereum, built using Cairo.  
It leverages **zk-Rollup technology** based on STARKs to achieve:
- **Scalability**: Thousands of transactions per second with low fees.
- **Security**: Inherits Ethereum’s security through validity proofs.
- **Decentralization**: Anyone can deploy contracts and interact permissionlessly.

In short, **Cairo is the programming language**, while **StarkNet is the network** where Cairo smart contracts live.

---

## 🗺️ Architecture Overview

**Architecture relationship between Ethereum, StarkNet, and Cairo:**

- **Ethereum (Layer 1)** → Provides the base security layer.
- **StarkNet (Layer 2)** → A zk-Rollup built on top of Ethereum, using STARK proofs to scale transactions.
- **Cairo** → The programming language used to write smart contracts on StarkNet.
- **Applications** → DeFi protocols, NFTs, and various dApps are deployed on StarkNet using Cairo.

---

## ⚡ Getting Started

### Prerequisites
- [Cairo](https://github.com/starkware-libs/cairo)
- [Scarb](https://docs.swmansion.com/scarb/) (Cairo package manager & build tool)
- [snFoundry](https://foundry-rs.github.io/) (optional, for testing)

### Installation
Clone the repository:
```bash
git clone https://github.com/ParesSensei/cairo-starklings-exercises.git
cd cairo-starklings-exercises
```

### ⚠️ Note:
This repository is primarily a personal learning resource.
However, if you are struggling with Starklings exercises or want to compare your answers, you can use this repo as a reference.
Simply look inside the src folder, where each solution corresponds to its respective exercise.

--- 

## 🤝 Contribution
This repo reflects my personal learning path.
Contributions are not expected, but you can fork it and use it as a reference if you are also learning Cairo & StarkNet.

---

## 🌟 About Starklings

Starklings
is an interactive tutorial inspired by Rustlings, where you solve small Cairo exercises to learn the language and StarkNet development step by step.