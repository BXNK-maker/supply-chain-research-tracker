---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "DEG: Diffusion-Enhanced GFlowNet for Solving Vehicle Routing Problems"
description: "The paper introduces Diffusion-Enhanced GFlowNet (DEG), a novel framework that integrates Generative Flow Networks with diffusion models to solve vehicle routing problems. Traditional GFlowNets suffer from limited flow expansion in high-reward regions, while diffusion models provide strong structural exploration guidance. DEG combines these paradigms by using GFlowNet to generate edge-specific backward signals, perturbing them with diffusion noise schedules, and denoising them within the GFlowNet paradigm. Evaluated on synthetic and real-world datasets with up to 10,000 nodes, DEG demonstrates superior solution quality and scalability compared to baseline methods."
resource: "https://arxiv.org/abs/2610.39512"
tags:
  - "vehicle-routing-problem"
  - "reinforcement-learning"
  - "neural-routing-solver"
timestamp: "2026-11-03T12:36:09Z"

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
    description: "A novel framework integrating Generative Flow Networks with diffusion models to encourage richer flow expansion toward high-reward regions in vehicle routing problems."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-03T12:36:09Z"
created_at: "2026-11-03T12:36:09Z"
---

# DEG: Diffusion-Enhanced GFlowNet for Solving Vehicle Routing Problems

**Authors**: Ni Zhang, Zhiqin Zhang, Ling Pan, Hoong Chuin Lau, Zhiguang Cao
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.39512](https://arxiv.org/abs/2610.39512)

## Summary

The paper introduces Diffusion-Enhanced GFlowNet (DEG), a novel framework that integrates Generative Flow Networks with diffusion models to solve vehicle routing problems. Traditional GFlowNets suffer from limited flow expansion in high-reward regions, while diffusion models provide strong structural exploration guidance. DEG combines these paradigms by using GFlowNet to generate edge-specific backward signals, perturbing them with diffusion noise schedules, and denoising them within the GFlowNet paradigm. Evaluated on synthetic and real-world datasets with up to 10,000 nodes, DEG demonstrates superior solution quality and scalability compared to baseline methods.

## Key Contributions

- Proposed Diffusion-Enhanced GFlowNet (DEG), integrating GFlowNet with diffusion models to provide stronger structural exploration and improve flow expansion in high-reward regions for vehicle routing problems.
- Developed a mechanism where GFlowNet supplies edge-level backward signals perturbed by stochastic diffusion noise schedules and denoised within the GFlowNet paradigm.
- Introduced a specialized decoder capable of dynamically adapting to diverse problem scales to enhance scalability up to 10,000 nodes.
- Demonstrated consistent performance improvements on both synthetic and real-world vehicle routing problem benchmarks compared to baseline methods.

## Key Concepts

- [[diffusion-enhanced-gflownet]]: A novel framework integrating Generative Flow Networks with diffusion models to encourage richer flow expansion toward high-reward regions in vehicle routing problems.

## Archivist Review

Approved the core concept 'diffusion-enhanced-gflownet' which is already present in the existing vault (matching its canonical slug). Rejected the open question because it focuses on a paper-local limitation regarding small-scale parallel decoding trade-offs rather than a broad, highly reusable research bottleneck.

### Approved Concepts
- Diffusion-Enhanced GFlowNet: Proposes a novel hybrid framework bridging GFlowNet and diffusion models for combinatorial optimization and routing problems.

### Rejected Candidates
- [open_question] Enhancing Small-Scale Decoding in Non-Autoregressive Solvers (`enhancing-small-scale-decoding-capacity-in-non-autoregressive-vsp-solvers`) - low_impact: The open question is largely tied to a specific architectural trade-off between autoregressive and non-autoregressive routing solvers rather than a broadly reusable core theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.39512)
- [PDF](https://arxiv.org/pdf/2610.39512)

