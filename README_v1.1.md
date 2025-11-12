# AEDA Framework

**Adaptive Ethical Design Architecture for AI Alignment**

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Version](https://img.shields.io/badge/version-1.1-blue.svg)](https://github.com/aeda-framework/AEDA-Framework)

---

## 🎯 Overview

AEDA is an 8-layer modular framework designed to prevent catastrophic AI failure modes through pre-execution safety filtering, systemic coherence evaluation, and real-time ethical drift detection.

**Key Innovation:** Rather than relying on fixed rules or pure optimization, AEDA maintains stable ethical direction while adapting to context through asymptotic orientation.

---

## 🌟 What's New in v1.1

**Chapter 7: Detailed Case Studies** — Added comprehensive analysis across 10 diverse domains:

1. **Healthcare** — Pain management decisions (5 intervention levels)
2. **Autonomous Vehicles** — Emergency maneuver selection
3. **Resource Allocation** — Humanitarian crisis response
4. **Financial Systems** — High-frequency trading controls
5. **Bioengineering** — CRISPR germline editing decisions
6. **Military Drones** — Target engagement protocols
7. **Education Systems** — Adaptive learning path design
8. **Urban AI** — Traffic flow vs emergency response
9. **AI Moderation** — Content filtering decisions
10. **Climate Engineering** — Geoengineering intervention assessment

Each case study includes:
- Complete SSTF evaluation matrices (R, H, U scores)
- Layer-by-layer decision analysis (Ψ through Ω)
- Systemic coherence (Φ) calculations
- Turbulence index (T) measurements
- Comparative outcomes: Without AEDA vs With AEDA

---

## 🏗️ Architecture

### The 8 Layers

| Layer | Component | Function |
|-------|-----------|----------|
| **1** | Signal Modulator (Ψ) | Normalizes sensory and metric inputs |
| **2** | Temporal Operator (Θ) | Integrates historical context with exponential decay |
| **3** | Systemic Coherence (Φ) | Evaluates multi-agent alignment across extended system |
| **4** | Safe-State Threshold Filter (SSTF) | Blocks irreversible/harmful actions pre-execution |
| **5** | Differential Engine (Δ) | Computes behavioral adjustments |
| **6** | Asymptotic Ethical Orientation (AEO) | Maintains stable ethical direction without rigid convergence |
| **7** | Ethical Valuation Matrix (EVM) | Multi-criteria decision-making framework |
| **8** | Systemic Health Gate (Ω) | Circuit breaker for system stability |

### Monitor

**Turbulence Index (T)** — Real-time ethical drift detection measuring divergence from asymptotic orientation (η)

---

## 🛡️ Core Mechanisms

### Safe-State Threshold Filter (SSTF)

Evaluates every action **before execution** across three dimensions:

- **Irreversibility (R):** 0.0 (fully reversible) → 1.0 (permanent)
- **Harm Potential (H):** 0.0 (harmless) → 1.0 (catastrophic)
- **Uncertainty (U):** 0.0 (predictable) → 1.0 (chaotic)

**Classification:**
```
if R ≥ 0.8 or H ≥ 0.8:
    DANGEROUS → Block immediately
elif R < 0.3 and H < 0.2 and U < 0.3:
    SAFE → Allow
else:
    danger_score = 0.4*R + 0.4*H + 0.2*U
    UNCERTAIN if danger_score ≥ 0.35 else SAFE
```

### Systemic Coherence (Φ)

Evaluates alignment across **all affected agents**, not just local optimization:

```
Φ(a,t) = ∫ [alignment(a, agent_i) × influence(agent_i)] dΩ
```

### Turbulence Index (T)

Measures real-time drift from ethical orientation:

```
T(t) = ||η(t) - normalize(a*(t))||

T < 0.2:       Low turbulence (well-aligned)
0.2 ≤ T < 0.5: Moderate (monitor closely)
T ≥ 0.5:       High turbulence (review required)
```

---

## 📚 Documentation

### Core Documents

- **[Full Manual v1.1 (PDF)](AEDA_Manual_v1.1_English.pdf)** — Complete technical documentation (55-60 pages)
  - **New:** Chapter 7 with 10 detailed case studies
  - Mathematical formalism, implementation guidelines, emergent properties
  
- **[Full Manual v1.0 (PDF)](AEDA_Manual_v1.0_English.pdf)** — Original version (40 pages)
  - Core architecture and theoretical foundation

- **[Executive Summary](EXECUTIVE_SUMMARY.md)** — 2-page overview

- **[Architecture Diagram](AEDA_Framework_Infographic.png)** — Visual representation

---

## 🚀 Key Features

### Emergent Properties

These aren't hardcoded—they emerge from layer interactions:

1. **Directional Stability** — Ethical consistency across contexts
2. **Self-Contradiction Detection** — Identifies own inconsistencies via Φ + T
3. **Adaptation Without Drift** — Learning without value degradation
4. **Full Traceability** — Every decision auditable (R, H, U, Φ, T, Ω)

### Innovations (v1.0)

- **Systemic Coherence Operator (Φ)** — Multi-agent alignment evaluation
- **Systemic Health Gate (Ω)** — Circuit breaker for system stability
- **Turbulence Index (T)** — Real-time ethical drift detection

---

## 🎯 Use Cases

**Demonstrated across 10 domains in v1.1:**

| Domain | Key Challenge | AEDA Solution |
|--------|---------------|---------------|
| Healthcare | "Eliminate suffering" → Euthanasia | SSTF blocks R=1.0, H=1.0; Φ detects systemic conflict |
| CRISPR | Enhancement vs therapy | Multi-generational Φ + Ω; blocks eugenic applications |
| Climate | Geoengineering risks | Planetary Φ across 200+ nations; Ω vetoes high R/H interventions |
| Military | Autonomous lethal force | SSTF blocks R≥0.95, H≥0.70; Φ evaluates geopolitical impact |
| Education | Cognitive freedom | T detects over-correction; SSTF prevents forced curricula |
| Urban AI | Traffic vs ambulance | City-as-organism Φ; prioritizes life-preservation |
| Moderation | Free speech vs safety | Graduated response (SAFE/UNCERTAIN/DANGEROUS); T detects censorship drift |
| Vehicles | Emergency maneuvers | Real-time SSTF (<100ms); Φ balances passenger/pedestrian safety |
| Finance | Market manipulation | Ω circuit breaker; T detects ethical drift from fair markets |
| Resources | Allocation in crisis | Φ balances equity/urgency; Ω monitors sustainability |

---

## 🤝 Comparison with Existing Approaches

AEDA is **complementary**, not competitive:

| Approach | Strength | AEDA Complement |
|----------|----------|-----------------|
| Constitutional AI | Value learning from language | SSTF + Ω add pre-execution safety filter |
| RLHF | Learns preferences | AEO maintains orientation, T detects drift |
| IRL | Infers goals from behavior | Θ adds temporal context, Φ adds systemic view |

**Key difference:** AEDA provides **structural safeguards** that prevent catastrophic failures even when value specification is imperfect.

---

## 📖 What AEDA Addresses

✅ **Addresses:**
- Catastrophic failure mode reduction (literal interpretation disasters)
- Ethical coherence across contexts
- Context-adaptive decision-making
- Real-time drift detection and correction

❌ **Does NOT solve:**
- Value learning (what values to have initially)
- Inner alignment (mesa-optimizers)
- Corrigibility (accepting corrections gracefully)
- Deceptive alignment (AI pretending to be aligned)

---

## 🛠️ Implementation Status

### Current Status (v1.1)

- ✅ Complete theoretical framework
- ✅ Mathematical formalism
- ✅ 10 detailed case studies across diverse domains
- ✅ Implementation guidelines
- 🔄 Python reference implementation (Coming Q1 2026)

### Roadmap

**Q1 2026:**
- Python reference implementation
- Open-source code examples
- Integration tutorials

**Q2 2026:**
- AEDA v2.0 — Harmonic Light Attractor (Attracteur Harmonique Lumineux)
- Extended governance frameworks
- Multi-modal applications

---

## 📜 License

**CC0 1.0 Universal (Public Domain)**

This work is dedicated to the public domain. You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

**No attribution required. Ideas matter. Identity is optional.**

---

## 🤝 Contributing

All contributions welcome — anonymous or attributed.

**Areas where help is needed:**
- Mathematical proofs of stability properties
- Computational optimization (making Φ tractable at scale)
- Domain-specific threshold calibration
- Integration with existing alignment approaches
- Red-teaming (finding edge cases where AEDA fails)
- Python/PyTorch implementation
- Case study extensions

**How to contribute:**
1. Fork this repository
2. Create your feature branch
3. Submit a pull request

Or open an issue to discuss ideas.

---

## 📧 Contact

**GitHub Discussions:** Use the [Discussions](https://github.com/aeda-framework/AEDA-Framework/discussions) tab for questions and conversations.

**Email:** aeda.framework@proton.me

---

## 🙏 Acknowledgments

This framework builds on decades of work in AI safety, ethics, and alignment research. Special thanks to the communities at:
- LessWrong / AI Alignment Forum
- Future of Humanity Institute
- Machine Intelligence Research Institute (MIRI)
- Partnership on AI

And to researchers like Stuart Armstrong, Paul Christiano, Eliezer Yudkowsky, and many others whose work on value alignment, corrigibility, and AI safety has informed this approach.

---

## 📊 Citation

If you use AEDA in academic work:

```bibtex
@misc{aeda2025,
  title={AEDA: Adaptive Ethical Design Architecture for AI Alignment},
  author={AEDA Framework Contributors},
  year={2025},
  howpublished={\url{https://github.com/aeda-framework/AEDA-Framework}},
  note={Version 1.1}
}
```

---

**"Ideas matter. Identity is optional."**

---

*Last updated: November 2025 (v1.1)*
