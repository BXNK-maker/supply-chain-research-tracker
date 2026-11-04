---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "When Protection Hurts: A Cytokine Storm Theory of Supply Chain Overreaction"
description: "This paper introduces a decision-theoretic framework to model how defensive supply chain actions can backfire, a phenomenon termed a 'Supply Chain Cytokine Storm'. The author defines Protective Response Intensity (PRI) and Response-Induced Loss (RIL) to derive a closed-form critical threshold beyond which overreactions worsen disruptions. Furthermore, the paper proposes the Cytokine Storm Index (CSI) and derives spectral stability conditions for interconnected supply networks. Numerical experiments demonstrate that while optimal responses stay below the storm threshold, proportional response heuristics can exceed it and cause network-wide divergence."
resource: "https://arxiv.org/abs/2610.33750"
tags:
  - "time-series"
  - "stochastic-demands"
  - "fleet-scheduling"
timestamp: "2026-11-04T12:45:36Z"

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
    description: "A phenomenon where excessive defensive responses in a supply chain generate losses exceeding the original disruption intensity."
datasets:
  []
open_questions:
  - name: "multi-agent-strategic-game-supply-chain-overreaction"
    description: "Develop a complete multi-agent game framework where multiple firms jointly and strategically optimize their protective response intensities rather than relying on a reduced-form behavioral propagation model."
skill: "GeneralMLSkill"
processed_at: "2026-11-04T12:45:36Z"
created_at: "2026-11-04T12:45:36Z"
---

# When Protection Hurts: A Cytokine Storm Theory of Supply Chain Overreaction

**Authors**: Gurkirat Wadhwa
**Date**: 2026-10-24
**Paper ID**: [openalex:2610.33750](https://arxiv.org/abs/2610.33750)

## Summary

This paper introduces a decision-theoretic framework to model how defensive supply chain actions can backfire, a phenomenon termed a 'Supply Chain Cytokine Storm'. The author defines Protective Response Intensity (PRI) and Response-Induced Loss (RIL) to derive a closed-form critical threshold beyond which overreactions worsen disruptions. Furthermore, the paper proposes the Cytokine Storm Index (CSI) and derives spectral stability conditions for interconnected supply networks. Numerical experiments demonstrate that while optimal responses stay below the storm threshold, proportional response heuristics can exceed it and cause network-wide divergence.

## Key Contributions

- Developed a decision-theoretic framework modeling Protective Response Intensity (PRI) and Response-Induced Loss (RIL) to formalize how defensive supply chain actions can backfire.
- Derived a closed-form critical response threshold and proposed the Cytokine Storm Index (CSI) to quantify when self-induced losses exceed original disruption intensity.
- Established a spectral stability condition for interconnected supply networks that distinguishes bounded decentralized responses from network-wide propagation and divergence.

## Limitations

Future work includes calibrating the Cytokine Storm Index using empirical operational data across multi-echelon industrial supply chains.

## Open Questions & Future Work

- [[multi-agent-strategic-game-supply-chain-overreaction]]

## Key Concepts

- [[supply-chain-cytokine-storm]]: A phenomenon where excessive defensive responses in a supply chain generate losses exceeding the original disruption intensity.

## Archivist Review

Approved the central theoretical concept of a supply chain cytokine storm along with the corresponding open question on multi-agent game formulations. Rejected routine extensions or unapproved items to maintain high vault quality standards.

### Approved Concepts
- Supply Chain Cytokine Storm: Introduces a novel biological analogy and theoretical framework to quantify when defensive supply chain actions exacerbate rather than mitigate shocks.

### Approved Open Questions
- Multi-Agent Strategic Game Analysis: Transitioning from reduced-form behavioral propagation to full game-theoretic equilibrium analysis is crucial to understand strategic hoarding and competitive overreaction in multi-firm supply networks.

## Links

- [Abstract](https://arxiv.org/abs/2610.33750)
- [PDF](https://arxiv.org/pdf/2610.33750)

