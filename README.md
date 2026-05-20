# Orpheus 🌌

> **Orpheus**: The stateless, low-overhead orchestration framework and token-generation pipeline for the **Sovereign Narrative Engine (SNE)**.

[![Zenodo DOI](https://img.shields.io/badge/Zenodo-DOI%2010.5281%2Fzenodo.11242308-blue)](https://doi.org/10.5281/zenodo.11242308)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-WSL2%20%7C%20Ubuntu-orange)](https://ubuntu.com)

Orpheus is a decoupled AI architecture that entirely rejects prompt-driven intervention and high-overhead natural language constraint tuning. Instead, it reframes narrative progression as a deterministic simulation governed by a coupled dynamical tensor system, utilizing **Computational Narrative Physics** to achieve infinite-horizon textual consistency.

---

## 🏛️ Architectural Overview

Standard LLM architectures treat long-form synthesis as disconnected, prompt-output transactions, resulting in systemic semantic flatlining and identity drift. Orpheus solves this by establishing a strict separation of concerns:

* **Tier 2 (The Substrate/Physics):** A multi-threaded C++ state engine tracking psychological trajectories, environmental deformations, and temporal constraints. System states are mathematically bound using contractive mappings under the **Banach Fixed-Point Stability Theorem** to suppress drift.
* **Tier 3 (The Typewriter):** A stateless, highly parallelized local inference layer powered by a hive-mind of local LLMs orchestrated via **vLLM** and **Ollama** within a virtualized Linux topology (WSL2/Ubuntu).

---

## 📄 Documentation & Specification

The foundational mathematical proofs, system invariants, and theoretical frameworks are permanently archived on Zenodo:

👉 **[Access the Master Specification Record via Zenodo](https://doi.org/10.5281/zenodo.11242308)**

### Citation
If you utilize this architecture or build upon the SNE paradigm in your own research, please use the following metadata citation:

```bibtex
@misc{schermerhorn2026sne,
  author       = {Schermerhorn, T. L.},
  title        = {The Sovereign Narrative Engine: A First-Principles Approach to Computational Narrative Physics},
  month        = may,
  year         = 2026,
  publisher    = {Zenodo},
  version      = {1.0.0},
  doi          = {10.5281/zenodo.11242308},
  url          = {[https://doi.org/10.5281/zenodo.11242308](https://doi.org/10.5281/zenodo.11242308)}
}
