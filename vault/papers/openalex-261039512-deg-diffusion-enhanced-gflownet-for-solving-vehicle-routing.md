---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "DEG: Diffusion-Enhanced GFlowNet for Solving Vehicle Routing Problems"
description: "Traditional neural solvers for vehicle routing problems (VRPs) often suffer from limited solution diversity, while Generative Flow Networks (GFlowNets) can struggle with insufficient flow expansion in high-reward regions. This paper proposes Diffusion-Enhanced GFlowNet (DEG), a novel framework that combines GFlowNet's edge-specific backward signals with a diffusion model's stochastic noise schedule and denoising process. DEG achieves richer flow expansion and stronger structural exploration guidance, scaling effectively up to 10,000 nodes with a scale-adaptive decoder."
resource: "https://arxiv.org/abs/2610.39512"
tags:
  - "neural-routing-solver"
  - "vehicle-routing-problem"
  - "reinforcement-learning"
timestamp: "2026-11-01T11:38:00Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Ni Zhang"
  - literal: "Zhiqin Zhang"
  - literal: "Ling Pan"
  - literal: "Hoong Chuin Lau"
  - literal: "Zhiguang Cao"
issued:
  date-parts:
    - [2026, 10, 29]

# Domain-specific custom fields
paper_id: "2610.39512"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "diffusion-enhanced-gflownet"
    description: "A novel framework integrating GFlowNet with a diffusion model to enhance exploration and flow expansion in high-reward regions for vehicle routing problems."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:38:00Z"
created_at: "2026-11-01T11:38:00Z"
---

# DEG: Diffusion-Enhanced GFlowNet for Solving Vehicle Routing Problems

**Authors**: Ni Zhang, Zhiqin Zhang, Ling Pan, Hoong Chuin Lau, Zhiguang Cao
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.39512](https://arxiv.org/abs/2610.39512)

## Summary

Traditional neural solvers for vehicle routing problems (VRPs) often suffer from limited solution diversity, while Generative Flow Networks (GFlowNets) can struggle with insufficient flow expansion in high-reward regions. This paper proposes Diffusion-Enhanced GFlowNet (DEG), a novel framework that combines GFlowNet's edge-specific backward signals with a diffusion model's stochastic noise schedule and denoising process. DEG achieves richer flow expansion and stronger structural exploration guidance, scaling effectively up to 10,000 nodes with a scale-adaptive decoder.

## Key Contributions

- Proposes Diffusion-Enhanced GFlowNet (DEG), integrating GFlowNets with diffusion models to improve solution diversity and flow expansion in high-reward combinatorial optimization regions.
- Leverages GFlowNet edge-specific backward signals perturbed by a stochastic diffusion noise schedule and subsequently denoised within the GFlowNet paradigm.
- Introduces a specialized decoder capable of dynamically adapting to diverse problem scales, scaling up to 10,000 nodes.
- Demonstrates superior performance across synthetic and real-world vehicle routing problem datasets compared to baseline neural solvers.

## Limitations

Limitations are not explicitly detailed in the abstract, though future work likely involves scaling to even larger or more heterogeneous routing instances.

## Key Concepts

- [[diffusion-enhanced-gflownet]]: A novel framework integrating GFlowNet with a diffusion model to enhance exploration and flow expansion in high-reward regions for vehicle routing problems.

## Archivist Review

Approved the core framework concept 'Diffusion-Enhanced GFlowNet' as it represents a distinct, reusable methodology combining GFlowNets and diffusion for combinatorial optimization. Rejected both proposed open questions because one is a narrow architectural trade-off and the other is standard application extension (applying the model to more problem variants) rather than an enduring foundational research question. No datasets met the criteria for standalone notes.

### Approved Concepts
- Diffusion-Enhanced GFlowNet: Introduces a novel framework that integrates GFlowNet with diffusion models to overcome limited solution diversity and enhance exploration in high-reward regions for combinatorial optimization.

### Rejected Candidates
- [open_question] Local Decision Capacity in NAR Solvers (`local-decision-capacity-nar-small-scale`) - low_impact: While discussing a real limitation, it is framed too narrowly around NAR versus AR model trade-offs in small-scale routing rather than a broad foundational research bottleneck.
- [open_question] Extending DEG to VRP Variants (`extending-deg-to-vrp-variants`) - low_impact: This is standard application extension (applying a method to new problem variants) rather than an explicit unresolved conceptual or technical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.39512)
- [PDF](https://arxiv.org/pdf/2610.39512)

