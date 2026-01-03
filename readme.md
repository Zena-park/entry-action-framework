# Entry Action Framework

> **"Trust is not an algorithm, but a context"**

A new design paradigm for vouching networks.

---

## 📄 Papers

- **[English Version](./docs/paper_en_v2.md)** - Vouching Networks: Design and Implementation as General-Purpose Social Graph Infrastructure
- **[Korean Version](./docs/paper_kr_v2.md)** - 보증 네트워크: 범용 소셜 그래프 인프라로서의 설계와 구현

---

## 🎯 Overview

This work presents three fundamental contributions:

1. **Impossibility Result** - Formally proves that pure address-based systems cannot guarantee Sybil attack defense without external identity verification. Corrects 15 years of research direction since SybilGuard (2006).

2. **Entry Action Framework** - Proposes a new paradigm where the value of vouching networks lies in **entry condition design**, not sophisticated scoring algorithms.

3. **Scalability Proof** - Demonstrates O(n²) → O(1) complexity improvement through ZK-Rollup architecture with mathematical proof and empirical validation.

---

## 🛠️ Reference Implementation

This theoretical framework is based on analysis of the **SYB (Social Vouch System)** project:

**Primary Repository:**
- **[tokamak-sybil-resistance-mvp](https://github.com/tokamak-network/tokamak-sybil-resistance-mvp)** - Complete ZK-Rollup system (Contracts, Circuits, Sequencer)

**Component Repositories:**
- **[syb-contracts](https://github.com/tokamak-network/syb-contracts)** - Smart contracts
- **[syb-circuits](https://github.com/tokamak-network/syb-circuits)** - ZK circuits
- **[syb-frontend](https://github.com/tokamak-network/syb-frontend)** - User interface
- **[syb-mvp-smart-contracts](https://github.com/tokamak-network/syb-mvp-smart-contracts)** - MVP contracts

**Deployment:**
- Sepolia Testnet: `0x8F7AB8C5A57D5429B409D3515e2D847dE3f1986D`
- Network: 50 users, 450+ vouches

---

## 🤝 Relationship to SYB Project

This work represents **a reinterpretation** of the SYB project from the author's perspective:

- **Same deliverables**: Contracts, circuits, architecture remain unchanged
- **Different interpretation**: Not "incomplete Sybil defense" but "proof of new paradigm"
- **Independent research**: Created to evaluate SYB from a fresh angle

The SYB team has not endorsed this interpretation. This represents a formalization of the author's ideas and perspective.

---

## 📜 License

This work is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to share and adapt this work for any purpose, even commercially, as long as you give appropriate credit.

The referenced SYB implementation repositories are maintained by Tokamak Network and have their own licenses.

---

**Last Updated**: January 2025
