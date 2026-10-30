---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "When Protection Hurts: A Cytokine Storm Theory of Supply Chain Overreaction"
description: "This paper develops a decision-theoretic framework to model how defensive supply chain actions (such as hoarding and emergency sourcing) can inadvertently amplify operational costs and congestion, a phenomenon termed a Supply Chain Cytokine Storm. The author introduces Response-Induced Loss (RIL) and the Cytokine Storm Index (CSI) to characterize a unique optimal response threshold that balances disruption mitigation against self-induced losses. Furthermore, an extension to interconnected supply networks yields a spectral stability condition that governs whether decentralized responses propagate network-wide or remain bounded. Numerical experiments demonstrate that while optimal responses stay below the storm threshold, proportional response heuristics frequently exceed it."
resource: "https://arxiv.org/abs/2610.33750"
tags:
  - "stochastic-demands"
  - "time-series"
timestamp: "2026-10-30T11:08:01Z"

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
    description: "A phenomenon in supply chains where defensive responses exceed a critical threshold and generate greater losses than the original disruption itself."
datasets:
  []
open_questions:
  - name: "multi-agent-game-network-optimization"
    description: "Develop a complete multi-agent game analysis in which firms jointly optimize their protective response intensities across an interconnected supply network, moving beyond the current reduced-form behavioral propagation model."
skill: "GeneralMLSkill"
processed_at: "2026-10-30T11:08:01Z"
created_at: "2026-10-30T11:08:01Z"
---

# When Protection Hurts: A Cytokine Storm Theory of Supply Chain Overreaction

**Authors**: Gurkirat Wadhwa
**Date**: 2026-10-24
**Paper ID**: [openalex:2610.33750](https://arxiv.org/abs/2610.33750)

## Summary

This paper develops a decision-theoretic framework to model how defensive supply chain actions (such as hoarding and emergency sourcing) can inadvertently amplify operational costs and congestion, a phenomenon termed a Supply Chain Cytokine Storm. The author introduces Response-Induced Loss (RIL) and the Cytokine Storm Index (CSI) to characterize a unique optimal response threshold that balances disruption mitigation against self-induced losses. Furthermore, an extension to interconnected supply networks yields a spectral stability condition that governs whether decentralized responses propagate network-wide or remain bounded. Numerical experiments demonstrate that while optimal responses stay below the storm threshold, proportional response heuristics frequently exceed it.

## Key Contributions

- Developed a decision-theoretic framework where Protective Response Intensity (PRI) is endogenous, capturing Response-Induced Loss (RIL) from defensive actions.
- Derived a closed-form critical response threshold defining the Supply Chain Cytokine Storm, where response-induced losses exceed the original disruption.
- Introduced the Cytokine Storm Index (CSI) to quantify response-induced loss relative to the original disruption.
- Established a spectral stability condition for interconnected supply networks that distinguishes bounded decentralized responses from network-wide propagation.

## Open Questions & Future Work

- [[multi-agent-game-network-optimization]]

## Key Concepts

- [[supply-chain-cytokine-storm]]: A phenomenon in supply chains where defensive responses exceed a critical threshold and generate greater losses than the original disruption itself.

## Archivist Review

The paper introduces the novel 'Supply Chain Cytokine Storm' concept, which models overreaction and self-induced losses in supply networks. This concept is approved as a distinctive theoretical framework. The open question on multi-agent game network optimization is also approved as a substantive research direction, whereas empirical parameter estimation is rejected as routine calibration future work.

### Approved Concepts
- Supply Chain Cytokine Storm: Introduces a novel conceptual and mathematical framework for modeling when defensive supply chain responses cause more harm than the original disruption.

### Approved Open Questions
- Multi-Agent Game Network Optimization: Extending the single-firm optimization framework to a full game-theoretic equilibrium analysis across supply networks is crucial for understanding strategic behavior and welfare implications when multiple firms endogenously choose their defensive intensities.

### Rejected Candidates
- [open_question] Empirical Calibration of Disruption Parameters (`empirical-calibration-disruption-parameters`) - not_reusable: Routine call for parameter estimation and empirical calibration of a theoretical model using historical data.

## Links

- [Abstract](https://arxiv.org/abs/2610.33750)
- [PDF](https://arxiv.org/pdf/2610.33750)

