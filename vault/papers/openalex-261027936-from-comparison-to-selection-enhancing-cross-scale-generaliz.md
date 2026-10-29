---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Vehicle Routing Problem"
description: "This paper investigates the cross-scale generalization failure of reinforcement-learning-trained Pointer Networks on the Capacitated Vehicle Routing Problem (CVRP) when transferring across problem sizes. The authors identify three key degradation factors—node density shifts, attention dispersion, and graph-context dilution—and propose targeted modifications including entropy-based attention scaling and permutation-invariant graph-context aggregation. By combining these complementary techniques via an approach selector, the method achieves cost reductions of up to 3.2% across diverse seen and unseen problem scales."
resource: "https://arxiv.org/abs/2610.27936"
tags:
  - "reinforcement-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-29T11:14:26Z"

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
processed_at: "2026-10-29T11:14:26Z"
created_at: "2026-10-29T11:14:26Z"
---

# From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Vehicle Routing Problem

**Authors**: Sofiene Lassoued, Devara Tertia, Stefan Lier, Andreas Schwung
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27936](https://arxiv.org/abs/2610.27936)

## Summary

This paper investigates the cross-scale generalization failure of reinforcement-learning-trained Pointer Networks on the Capacitated Vehicle Routing Problem (CVRP) when transferring across problem sizes. The authors identify three key degradation factors—node density shifts, attention dispersion, and graph-context dilution—and propose targeted modifications including entropy-based attention scaling and permutation-invariant graph-context aggregation. By combining these complementary techniques via an approach selector, the method achieves cost reductions of up to 3.2% across diverse seen and unseen problem scales.

## Key Contributions

- Identified three core factors causing cross-scale generalization degradation in Pointer Networks for CVRP: node density shifts, attention dispersion, and graph-context dilution.
- Proposed a learned, permutation-invariant graph-context aggregation mechanism (weighted average and Set2Set) improving downscaling transfer (CVRP100-to-CVRP20) by 0.9 percentage points.
- Showed that entropy-based attention scaling reduces the CVRP20-to-CVRP100 upscaling performance gap by 1.41 percentage points.
- Introduced an approach selector combining complementary mechanisms to reduce costs by up to 3.2% across seen and unseen train-test problem sizes.

## Limitations

Evaluated primarily on CVRP as a proxy; generalization to other routing variants remains to be fully explored.

## Archivist Review

Strict adherence to the review policy was applied: no concepts were proposed, and the two open-source extension questions represent routine future work directions (combining components and using finer-grained features for selection) rather than foundational, long-lived research bottlenecks.

### Rejected Candidates
- [open_question] Unified Multi-Size Routing Models (`unified-multi-size-routing-models`) - not_novel: Routine exploration of combining existing architectural components and multi-size training strategies.
- [open_question] Instance-Aware Approach Selection (`instance-aware-approach-selection`) - low_impact: Standard proposal for extending meta-learning or algorithm selection with finer-grained features rather than addressing a fundamental theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.27936)
- [PDF](https://arxiv.org/pdf/2610.27936)

