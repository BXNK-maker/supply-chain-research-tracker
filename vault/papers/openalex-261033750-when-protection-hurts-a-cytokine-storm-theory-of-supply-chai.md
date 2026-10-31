---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "When Protection Hurts: A Cytokine Storm Theory of Supply Chain Overreaction"
description: "This paper develops a decision-theoretic framework to model how defensive supply chain actions such as hoarding and duplicate ordering can amplify disruptions, introducing the concept of a Supply Chain Cytokine Storm. The author defines Response-Induced Loss (RIL) and derives a closed-form critical response threshold alongside the Cytokine Storm Index (CSI) to quantify overreaction risks. Furthermore, a spectral stability condition is established for interconnected networks, showing that proportional heuristics risk triggering network-wide instability."
resource: "https://arxiv.org/abs/2610.33750"
tags:
  - "time-series"
  - "demand-forecasting"
  - "stochastic-demands"
timestamp: "2026-10-31T10:41:48Z"

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
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-31T10:41:48Z"
created_at: "2026-10-31T10:41:48Z"
---

# When Protection Hurts: A Cytokine Storm Theory of Supply Chain Overreaction

**Authors**: Gurkirat Wadhwa
**Date**: 2026-10-24
**Paper ID**: [openalex:2610.33750](https://arxiv.org/abs/2610.33750)

## Summary

This paper develops a decision-theoretic framework to model how defensive supply chain actions such as hoarding and duplicate ordering can amplify disruptions, introducing the concept of a Supply Chain Cytokine Storm. The author defines Response-Induced Loss (RIL) and derives a closed-form critical response threshold alongside the Cytokine Storm Index (CSI) to quantify overreaction risks. Furthermore, a spectral stability condition is established for interconnected networks, showing that proportional heuristics risk triggering network-wide instability.

## Key Contributions

- Developed a decision-theoretic framework where Protective Response Intensity (PRI) is an endogenous decision variable to model supply chain overreaction.
- Introduced Response-Induced Loss (RIL) and derived a closed-form critical response threshold termed a Supply Chain Cytokine Storm beyond which RIL exceeds the original disruption.
- Proposed the Cytokine Storm Index (CSI) to measure response-induced loss relative to original disruption intensity.
- Derived a spectral stability condition in interconnected supply networks to distinguish bounded decentralized responses from network-wide propagation.

## Limitations

The framework relies on mathematical abstraction and numerical experiments; empirical calibration of the Cytokine Storm Index (CSI) using real-world operational data remains to be fully explored.

## Archivist Review

The paper discusses supply-chain overreactions and introduces the concept of a Supply Chain Cytokine Storm, but that concept is already present in the vault under 'supply-chain-cytokine-storm'. The open question proposed about game-theoretic multi-firm optimization is standard future work proposing to replace a reduced-form model with a multi-agent game, which is too low impact for a permanent vault entry.

### Rejected Candidates
- [open_question] Game-Theoretic Multi-Firm Supply Chain Optimization (`game-theoretic-multi-firm-supply-chain-optimization`) - low_impact: This is a standard future work suggestion proposing to extend a reduced-form model to a full multi-agent game, lacking the specific unresolved theoretical mechanism needed for a permanent vault note.

## Links

- [Abstract](https://arxiv.org/abs/2610.33750)
- [PDF](https://arxiv.org/pdf/2610.33750)

