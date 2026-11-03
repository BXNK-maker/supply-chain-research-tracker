---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Vehicle Routing Problem"
description: "This paper investigates the cross-scale generalization degradation of attention-based Pointer Networks trained via reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify node density shifts, attention dispersion, and graph context dilution as primary failure modes, and evaluate targeted encoder, decoder, and architecture modifications. By combining entropy-based attention scaling (effective for upscaling) with permutation-invariant graph-context aggregation methods like Set2Set (effective for downscaling), they introduce an approach selector that improves solution costs by up to 3.2% across various seen and unseen problem sizes."
resource: "https://arxiv.org/abs/2610.27936"
tags:
  - "vehicle-routing-problem"
  - "reinforcement-learning"
  - "neural-routing-solver"
  - "combinatorial-optimization"
timestamp: "2026-11-03T12:36:17Z"

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
  - name: "joint-multiscale-training-levers"
    description: "Investigate the joint integration and multi-size training of complementary upscaling levers (such as attention rescaling) and downscaling levers (such as learned graph-context aggregations) within a unified multi-size reinforcement learning training scheme."
  - name: "instance-aware-algorithm-selection"
    description: "Develop instance-aware algorithm selection mechanisms that incorporate instance-specific topological and operational features—such as client density distributions and demand-to-capacity ratios—rather than relying solely on global problem scale dimensions."
skill: "GeneralMLSkill"
processed_at: "2026-11-03T12:36:17Z"
created_at: "2026-11-03T12:36:17Z"
---

# From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Vehicle Routing Problem

**Authors**: Sofiene Lassoued, Devara Tertia, Stefan Lier, Andreas Schwung
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27936](https://arxiv.org/abs/2610.27936)

## Summary

This paper investigates the cross-scale generalization degradation of attention-based Pointer Networks trained via reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify node density shifts, attention dispersion, and graph context dilution as primary failure modes, and evaluate targeted encoder, decoder, and architecture modifications. By combining entropy-based attention scaling (effective for upscaling) with permutation-invariant graph-context aggregation methods like Set2Set (effective for downscaling), they introduce an approach selector that improves solution costs by up to 3.2% across various seen and unseen problem sizes.

## Key Contributions

- Identified three key factors driving cross-scale generalization degradation in attention-based Pointer Networks for CVRP: shifts in node density, attention dispersion, and mean-pooled graph context dilution.
- Demonstrated that entropy-based attention scaling effectively improves upscaling performance (reducing the CVRP20-to-CVRP100 performance gap by 1.41 percentage points).
- Proposed learned permutation-invariant graph-context aggregation methods (weighted average and Set2Set) improving downscaling transfer (CVRP100-to-CVRP20) by approximately 0.9 percentage points.
- Introduced an approach selector that leverages complementary mechanisms to reduce routing cost by up to 3.2% across seen and unseen problem sizes.

## Limitations

Evaluated primarily on CVRP as a controlled proxy; further scaling to larger and more diverse routing variants remains open.

## Open Questions & Future Work

- [[joint-multiscale-training-levers]]
- [[instance-aware-algorithm-selection]]

## Archivist Review

The approach-selector-for-cross-scale-routing concept candidate was rejected because an equivalent concept (approach-selector-for-cross-scale-generalization) already exists in the vault. The two open questions explore distinct, non-trivial research directions regarding multi-scale training and instance-aware algorithm selection in neural routing and are approved.

### Approved Open Questions
- Joint Multi-Scale Training Levers: Combining complementary architecture-wide and decoder-side interventions into a single model trained across diverse scales is crucial for developing universally robust neural combinatorial optimization solvers.
- Instance-Aware Algorithm Selection: Moving from scale-based to instance-aware selection can significantly improve routing solution quality by adapting to fine-grained spatial characteristics of individual problem instances.

### Rejected Candidates
- [concept] Approach Selector for Cross-Scale Routing (`approach-selector-for-cross-scale-routing`) - duplicate_existing: The vault already contains 'approach-selector-for-cross-scale-generalization' which covers the exact same conceptual mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2610.27936)
- [PDF](https://arxiv.org/pdf/2610.27936)

