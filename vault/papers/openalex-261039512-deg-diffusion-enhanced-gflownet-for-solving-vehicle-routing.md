---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "DEG: Diffusion-Enhanced GFlowNet for Solving Vehicle Routing Problems"
description: "This paper introduces Diffusion-Enhanced GFlowNet (DEG), a novel framework that combines Generative Flow Networks with diffusion models to address the limited solution diversity and insufficient flow expansion of traditional neural VRP solvers. By using GFlowNet to supply edge-level signals for diffusion perturbation and denoising within the GFlowNet paradigm, DEG achieves superior exploration and high-quality solutions. Extensive experiments demonstrate that DEG scales effectively to problem instances with up to 10,000 nodes."
resource: "https://arxiv.org/abs/2610.39512"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "reinforcement-learning"
timestamp: "2026-11-02T12:59:47Z"

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
    description: "A novel framework that integrates GFlowNet with a diffusion model to encourage richer flow expansion toward high-reward regions in combinatorial optimization."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-02T12:59:47Z"
created_at: "2026-11-02T12:59:47Z"
---

# DEG: Diffusion-Enhanced GFlowNet for Solving Vehicle Routing Problems

**Authors**: Ni Zhang, Zhiqin Zhang, Ling Pan, Hoong Chuin Lau, Zhiguang Cao
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.39512](https://arxiv.org/abs/2610.39512)

## Summary

This paper introduces Diffusion-Enhanced GFlowNet (DEG), a novel framework that combines Generative Flow Networks with diffusion models to address the limited solution diversity and insufficient flow expansion of traditional neural VRP solvers. By using GFlowNet to supply edge-level signals for diffusion perturbation and denoising within the GFlowNet paradigm, DEG achieves superior exploration and high-quality solutions. Extensive experiments demonstrate that DEG scales effectively to problem instances with up to 10,000 nodes.

## Key Contributions

- Proposed Diffusion-Enhanced GFlowNet (DEG), integrating GFlowNet with a diffusion model to improve exploration and flow expansion in high-reward regions for vehicle routing problems.
- Utilizes GFlowNet diversity to generate edge-specific backward signals, perturbing them with a diffusion noise schedule and denoising within the GFlowNet paradigm.
- Introduced a specialized decoder capable of dynamically adapting to diverse problem scales up to 10,000 nodes.

## Key Concepts

- [[diffusion-enhanced-gflownet]]: A novel framework that integrates GFlowNet with a diffusion model to encourage richer flow expansion toward high-reward regions in combinatorial optimization.

## Archivist Review

Approved the core methodological concept 'Diffusion-Enhanced GFlowNet' which already exists in the vault. Rejected open questions as standard future work extensions (routing variants and local scale adjustments). No datasets qualified.

### Approved Concepts
- Diffusion-Enhanced GFlowNet: Central methodological framework of the paper, combining GFlowNet and diffusion models for combinatorial optimization.

### Rejected Candidates
- [open_question] Small-Scale Local Decision-Making in VRP Solvers (`enhancing-small-scale-local-decision-making-in-non-autoregressive-vrp-solvers`) - paper_local: not_novel
- [open_question] Extending Diffusion-Enhanced GFlowNets to VRP Variants (`extending-diffusion-enhanced-gflownets-to-diverse-vrp-variants`) - generic: not_novel

## Links

- [Abstract](https://arxiv.org/abs/2610.39512)
- [PDF](https://arxiv.org/pdf/2610.39512)

