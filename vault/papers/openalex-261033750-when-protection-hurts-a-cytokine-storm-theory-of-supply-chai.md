---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "When Protection Hurts: A Cytokine Storm Theory of Supply Chain Overreaction"
description: "This paper develops a decision-theoretic framework to study how defensive supply chain actions—such as hoarding and duplicate ordering—can paradoxically amplify disruptions, a phenomenon the author terms a Supply Chain Cytokine Storm. The author introduces Protective Response Intensity (PRI), Response-Induced Loss (RIL), and the Cytokine Storm Index (CSI) to model and quantify these self-inflicted costs. Furthermore, the work derives a spectral stability condition for interconnected networks, showing that optimal responses remain below the storm threshold while proportional heuristics can dangerously exceed it."
resource: "https://arxiv.org/abs/2610.33750"
tags:
  - "machine-learning"
timestamp: "2026-11-02T13:04:26Z"

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
processed_at: "2026-11-02T13:04:26Z"
created_at: "2026-11-02T13:04:26Z"
---

# When Protection Hurts: A Cytokine Storm Theory of Supply Chain Overreaction

**Authors**: Gurkirat Wadhwa
**Date**: 2026-10-24
**Paper ID**: [openalex:2610.33750](https://arxiv.org/abs/2610.33750)

## Summary

This paper develops a decision-theoretic framework to study how defensive supply chain actions—such as hoarding and duplicate ordering—can paradoxically amplify disruptions, a phenomenon the author terms a Supply Chain Cytokine Storm. The author introduces Protective Response Intensity (PRI), Response-Induced Loss (RIL), and the Cytokine Storm Index (CSI) to model and quantify these self-inflicted costs. Furthermore, the work derives a spectral stability condition for interconnected networks, showing that optimal responses remain below the storm threshold while proportional heuristics can dangerously exceed it.

## Key Contributions

- Developed a decision-theoretic framework modeling Protective Response Intensity (PRI) as an endogenous variable balancing disruption mitigation against Response-Induced Loss (RIL).
- Derived a closed-form critical response threshold (Supply Chain Cytokine Storm) beyond which defensive actions worsen the original disruption.
- Proposed the Cytokine Storm Index (CSI) to quantify response-induced loss relative to initial disruption intensity.
- Derived a spectral stability condition for interconnected supply networks to distinguish bounded decentralized responses from network-wide propagation.

## Limitations

Future work could focus on calibrating the Cytokine Storm Index using large-scale empirical operational data across diverse industry sectors.

## Archivist Review

Applied high selectivity standards: the core concepts and open questions proposed by this paper either duplicate existing entries in the vault (such as supply-chain-cytokine-storm and its associated multi-agent game calibration open question) or represent subcomponents of the broader framework. Therefore, no new standalone notes are added.

### Rejected Candidates
- [concept] Protective Response Intensity (`protective-response-intensity`) - subcomponent_of_broader_mechanism: Subcomponent of the broader supply-chain cytokine storm framework, and already largely captured by existing vault notes on supply chain contagion and network dynamics.
- [concept] Supply Chain Cytokine Storm (`supply-chain-cytokine-storm`) - duplicate_existing: Synonymous with or extremely close to the existing vault concept 'supply-chain-cytokine-storm' (already present in the vault).
- [open_question] Game-Theoretic Supply Chain Cytokine Storms (`multi-agent-game-supply-chain-cytokine-storms`) - duplicate_existing: Overlaps significantly with the existing vault open question 'multi-agent-game-and-empirical-calibration-for-supply-chain-cytokine-storms'.

## Links

- [Abstract](https://arxiv.org/abs/2610.33750)
- [PDF](https://arxiv.org/pdf/2610.33750)

