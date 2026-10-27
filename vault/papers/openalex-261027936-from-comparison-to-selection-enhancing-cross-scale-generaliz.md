---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for for Capacitated Vehicle Routing Problem"
description: "This paper investigates cross-scale generalization limitations in attention-based Pointer Networks trained via reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify node density shifts, attention dispersion, and graph context dilution as key drivers of performance degradation when upscaling or downscaling problem sizes. To address these limitations, they propose entropy-based attention scaling and permutation-invariant graph-context aggregation mechanisms, combining them via an approach selector that achieves up to 3.2% cost reductions across both seen and unseen problem scales."
resource: "https://arxiv.org/abs/2610.27936"
tags:
  - "reinforcement-learning"
  - "vehicle-routing-problem"
  - "demand-forecasting"
timestamp: "2026-10-27T10:09:34Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Sofiene Lassoued"
  - literal: "Devara Tertia"
  - literal: "Stefan Lier"
  - literal: "Andreas Schwung"
issued:
  date-parts:
    - [2026, 10, 20]

# Domain-specific custom fields
paper_id: "2610.27936"
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
processed_at: "2026-10-27T10:09:34Z"
created_at: "2026-10-27T10:09:34Z"
---

# From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for for Capacitated Vehicle Routing Problem

**Authors**: Sofiene Lassoued, Devara Tertia, Stefan Lier, Andreas Schwung
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27936](https://arxiv.org/abs/2610.27936)

## Summary

This paper investigates cross-scale generalization limitations in attention-based Pointer Networks trained via reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify node density shifts, attention dispersion, and graph context dilution as key drivers of performance degradation when upscaling or downscaling problem sizes. To address these limitations, they propose entropy-based attention scaling and permutation-invariant graph-context aggregation mechanisms, combining them via an approach selector that achieves up to 3.2% cost reductions across both seen and unseen problem scales.

## Key Contributions

- Identified three core factors degrading cross-scale generalization in Pointer Networks for CVRP: shifts in node density, attention dispersion, and mean-pooled graph context dilution.
- Proposed entropy-based attention scaling to reduce the CVRP20-to-CVRP100 performance gap by 1.41 percentage points.
- Developed a learned, permutation-invariant graph-context aggregation mechanism using weighted averages and Set2Set, improving CVRP100-to-CVRP20 transfer by 0.9 percentage points.
- Introduced an approach selector that improves routing cost by up to 3.2% across seen and unseen problem sizes.

## Limitations

Evaluated primarily on CVRP variants; generalizability to other routing problems with side constraints remains to be fully explored.

## Archivist Review

Applied rigorous filtering standards to reject paper-local concepts and narrow optimization questions. The approach selector and upscaling/downscaling unification question are too domain-specific to vehicle routing pointer networks to merit standalone vault entries.

### Rejected Candidates
- [concept] Approach Selector for Pointer Networks (`approach-selector-pointer-networks`) - paper_local: Too paper-local and specific to routing model selection across scales to warrant a permanent vault note.
- [open_question] Unifying Upscaling and Downscaling Levers (`unifying-upscaling-downscaling-levers`) - low_impact: Too specific to the architectural trade-offs of pointer networks in vehicle routing rather than a foundational open research direction.

## Links

- [Abstract](https://arxiv.org/abs/2610.27936)
- [PDF](https://arxiv.org/pdf/2610.27936)

