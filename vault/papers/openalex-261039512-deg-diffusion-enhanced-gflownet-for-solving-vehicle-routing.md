---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "DEG: Diffusion-Enhanced GFlowNet for Solving Vehicle Routing Problems"
description: "Traditional neural solvers for vehicle routing problems often struggle with limited solution diversity and insufficient flow expansion in high-reward regions. To address this, the authors propose Diffusion-Enhanced GFlowNet (DEG), which combines GFlowNet's diverse edge-level signals with the structural guidance and noise scheduling of diffusion models. DEG perturbs and denoises backward signals within the GFlowNet paradigm and incorporates a scale-adaptive decoder to scale up to 10,000 nodes. Extensive evaluations show that DEG achieves superior performance over existing baseline methods across synthetic and real-world datasets."
resource: "https://arxiv.org/abs/2610.39512"
tags:
  - "reinforcement-learning"
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "neural-routing-solver"
timestamp: "2026-11-04T12:44:19Z"

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
    description: "A framework integrating Generative Flow Networks with diffusion models to improve exploration and solution diversity in vehicle routing problems."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-04T12:44:19Z"
created_at: "2026-11-04T12:44:19Z"
---

# DEG: Diffusion-Enhanced GFlowNet for Solving Vehicle Routing Problems

**Authors**: Ni Zhang, Zhiqin Zhang, Ling Pan, Hoong Chuin Lau, Zhiguang Cao
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.39512](https://arxiv.org/abs/2610.39512)

## Summary

Traditional neural solvers for vehicle routing problems often struggle with limited solution diversity and insufficient flow expansion in high-reward regions. To address this, the authors propose Diffusion-Enhanced GFlowNet (DEG), which combines GFlowNet's diverse edge-level signals with the structural guidance and noise scheduling of diffusion models. DEG perturbs and denoises backward signals within the GFlowNet paradigm and incorporates a scale-adaptive decoder to scale up to 10,000 nodes. Extensive evaluations show that DEG achieves superior performance over existing baseline methods across synthetic and real-world datasets.

## Key Contributions

- Proposes Diffusion-Enhanced GFlowNet (DEG), a novel framework combining GFlowNet with diffusion models to enhance exploration and flow expansion in high-reward regions for vehicle routing problems.
- Introduces a specialized decoder that dynamically adapts to diverse problem scales to improve scalability.
- Demonstrates consistent, favorable performance on synthetic and real-world instances with up to 10,000 nodes compared to baseline methods.

## Key Concepts

- [[diffusion-enhanced-gflownet]]: A framework integrating Generative Flow Networks with diffusion models to improve exploration and solution diversity in vehicle routing problems.

## Archivist Review

Approved the overarching concept 'Diffusion-Enhanced GFlowNet' since it represents a distinct methodological synergy between GFlowNets and diffusion models for combinatorial optimization. Rejected the open question as it is a paper-local performance comparison limitation between non-autoregressive and autoregressive solvers on small scales.

### Approved Concepts
- Diffusion-Enhanced GFlowNet: Combines GFlowNet and diffusion models for combinatorial optimization, offering a novel paradigm for exploring high-reward solution spaces.

### Rejected Candidates
- [open_question] Enhancing Small-Scale Non-Autoregressive Decoding (`non-autoregressive-small-scale-performance`) - paper_local: The open question focuses heavily on specific small-scale performance limitations of a local NAR vs AR solver comparison, which is too paper-local and narrow for a permanent vault note.

## Links

- [Abstract](https://arxiv.org/abs/2610.39512)
- [PDF](https://arxiv.org/pdf/2610.39512)

