# PoM: Proof of Materials  
### A Materials-Backed Decentralized Value Layer for SurroDFT  
Author: Kepei Miao  
Year: 2025  

---

## 1. Overview

Proof of Materials (PoM) is a conceptual decentralized value framework that converts material performance metrics into quantifiable value and token issuance.

PoM is designed as the economic and value layer of SurroDFT, extending the platform from a decentralized computational engine into a materials-backed digital economy.

SurroDFT handles:

- Decentralized AI / DFT computation  
- Molecular and material property prediction  
- Distributed data contribution  
- Storage, verification, and model evaluation  

PoM handles:

- Value formation  
- Token issuance rules  
- Materials-backed credit  
- Economic incentives  
- Mining based on material performance, not raw computation  

Together, SurroDFT + PoM form a unified system:

> A decentralized materials discovery network + a materials-backed asset system.

---

## 2. Motivation

### 2.1 Materials as the foundation of civilization

Battery cathodes, solid electrolytes, catalysts, semiconductors and structural alloys form the physical basis of modern technology. Their performance directly constrains what is technologically possible.

### 2.2 Material properties are objective and quantifiable

Examples of measurable properties:

- Energy density  
- Ionic diffusivity  
- Cycle life  
- Band gap  
- Thermal stability  
- Mechanical modulus  
- Formation energy  

These are natural, scientific sources of value.

### 2.3 Web3 lacks a value system anchored to physical matter

- Proof of Work (PoW) anchors value to computation.  
- Proof of Stake (PoS) anchors value to stake concentration.  
- Stablecoins anchor value to fiat.

None of them anchor value to physics, chemistry, or material limits.

PoM fills this gap by proposing a scientific, materials-based decentralized value standard.

---

## 3. Material Performance Score (MPS)

PoM defines a generic scoring function for any material.

Instead of LaTeX, we use plain text:

- Let M1, M2, ..., Mn be measurable material properties.  
- Let N(Mi) be each property normalized into the range [0, 1].  
- Let wi be the weight for property i.

Then:

> MPS = w1 * N(M1) + w2 * N(M2) + ... + wn * N(Mn)

Examples of metrics for battery materials:

- Gravimetric energy density  
- Volumetric energy density  
- Cycle life  
- Safety / thermal stability  
- Ionic conductivity  
- Raw material cost  
- Environmental impact  

Examples for general materials:

- Band gap  
- Formation energy  
- Elastic modulus  
- Corrosion resistance  
- Abundance / extraction cost  

Different domains can define different sets of Mi and wi.

---

## 4. Token Issuance in PoM

Token supply is a function of the Material Performance Score.

We write this simply as:

> Token_Supply = f(MPS)

Some possible forms:

- Linear:  
  Token_Supply = k * MPS  

- Exponential:  
  Token_Supply = a * exp(b * MPS)  

- Or any bounded / piecewise function that fits ecosystem needs.

The exact design depends on the desired incentive structure.

---

## 5. Mining in PoM

Mining in PoM does not reward wasteful computation.  
Instead, it rewards scientifically meaningful contributions related to materials.

Possible contributions include:

- New experimental datasets  
- New DFT calculations  
- New AI-predicted material properties  
- New material or molecular structures  
- Optimized compositions and configurations  
- Surrogate model training and evaluation runs  

SurroDFT acts as the execution and computation engine for these tasks.  
PoM converts these contributions into decentralized economic value according to the MPS and token issuance rules.

---

## 6. SurroDFT × PoM Architecture

SurroDFT provides:

- Distributed compute  
- Surrogate AI / DFT models  
- Multi-node inference  
- Dataset validation  
- Molecular and material simulation tools  

PoM provides:

- Material value scoring (MPS)  
- Token issuance logic  
- Contribution rewards  
- Economic governance  
- A materials-backed currency standard  

Together they form:

> A decentralized materials discovery protocol + economic engine.

In this view, SurroDFT is the "computation layer",  
and PoM is the "value layer" built on top of it.

---

## 7. Long-Term Vision

PoM aims to enable:

- A global index of materials value  
- A decentralized incentive system for materials discovery  
- A scientific alternative to PoW / PoS  
- A new asset class anchored in physical matter  
- A unified data → compute → value pipeline

Ultimately:

> Materials themselves become the foundation of a decentralized currency system.  
> Nature becomes consensus.

---

## 8. Status of This Document

This document is a conceptual framework, not a finalized cryptoeconomic protocol.

It intends to:

- Define the term "Proof of Materials (PoM)"  
- Claim the conceptual territory of materials-backed decentralized value  
- Clarify the relationship between SurroDFT and PoM  
- Provide a starting point for future technical and economic design

Future versions may specify:

- Cryptographic verification schemes  
- ZK-DFT / ZK-Science style proofs  
- Smart contract architecture  
- Detailed tokenomics  
- Governance mechanisms  

---

## 9. License

This document is released under:

Creative Commons Attribution 4.0 International (CC BY 4.0)

All derivative works must credit the original author:

Kepei Miao, creator of the PoM concept (Proof of Materials), 2025.
