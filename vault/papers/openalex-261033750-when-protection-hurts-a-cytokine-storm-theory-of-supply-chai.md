---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "When Protection Hurts: A Cytokine Storm Theory of Supply Chain Overreaction"
description: "This paper develops a decision-theoretic framework to study how excessive defensive actions in supply chains can paradoxically worsen disruptions, a phenomenon termed a Supply Chain Cytokine Storm. The author introduces Response-Induced Loss (RIL) and the Cytokine Storm Index (CSI), deriving a closed-form critical response threshold and a spectral stability condition for interconnected networks. Numerical experiments demonstrate that optimal responses remain below the storm threshold, whereas proportional heuristics can trigger network-wide divergence."
resource: "https://arxiv.org/abs/2610.33750"
tags:
  - "stochastic-demands"
  - "time-series"
timestamp: "2026-11-01T11:36:52Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Gurkirat Wadhwa"
issued:
  date-parts:
    - [2026, 10, 24]

# Domain-specific custom fields
paper_id: "2610.33750"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "supply-chain-cytokine-storm"
    description: "A theoretical phenomenon where defensive supply chain responses induce losses exceeding the original disruption intensity."
datasets:
  []
open_questions:
  - name: "multi-agent-game-and-empirical-calibration-for-supply-chain-cytokine-storms"
    description: "Develop a complete multi-agent game analysis in which multiple firms jointly optimize their defensive response intensities in a strategic equilibrium, moving beyond the current reduced-form behavioral propagation network model. Furthermore, estimate the reduced-form parameters (such as overreaction cost coefficients, mitigation effectiveness, and behavioral contagion) directly from empirical industry disruption events."
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:36:52Z"
created_at: "2026-11-01T11:36:52Z"
---

# When Protection Hurts: A Cytokine Storm Theory of Supply Chain Overreaction

**Authors**: Gurkirat Wadhwa
**Date**: 2026-10-24
**Paper ID**: [openalex:2610.33750](https://arxiv.org/abs/2610.33750)

## Summary

This paper develops a decision-theoretic framework to study how excessive defensive actions in supply chains can paradoxically worsen disruptions, a phenomenon termed a Supply Chain Cytokine Storm. The author introduces Response-Induced Loss (RIL) and the Cytokine Storm Index (CSI), deriving a closed-form critical response threshold and a spectral stability condition for interconnected networks. Numerical experiments demonstrate that optimal responses remain below the storm threshold, whereas proportional heuristics can trigger network-wide divergence.

## Key Contributions

- Developed a decision-theoretic framework modeling Protective Response Intensity (PRI) and Response-Induced Loss (RIL).
- Derived a closed-form critical response threshold (Supply Chain Cytokine Storm) where defensive losses exceed original disruption intensity.
- Proposed the Cytokine Storm Index (CSI) and established a spectral stability condition for network-wide propagation in interconnected supply networks.

## Limitations

Operational calibration of the framework requires further empirical work using real-world supply chain data.

## Open Questions & Future Work

- [[multi-agent-game-and-empirical-calibration-for-supply-chain-cytokine-storms]]

## Key Concepts

- [[supply-chain-cytokine-storm]]: A theoretical phenomenon where defensive supply chain responses induce losses exceeding the original disruption intensity.

## Archivist Review

Approved the core concept of the supply chain cytokine storm and its corresponding open question regarding multi-agent equilibria and empirical parameter calibration, as both offer rigorous and reusable modeling contributions for supply chain resilience literature.

### Approved Concepts
- Supply Chain Cytokine Storm: Introduces a novel biological analogy and mathematical threshold for when defensive supply chain actions worsen disruption.

### Approved Open Questions
- Multi-Agent Game and Empirical Parameter Calibration: Transitioning from reduced-form network models to rigorous game-theoretic equilibria and empirically grounded parameters is essential for translating theoretical cytokine storm models into actionable supply chain policy tools.

## Links

- [Abstract](https://arxiv.org/abs/2610.33750)
- [PDF](https://arxiv.org/pdf/2610.33750)

