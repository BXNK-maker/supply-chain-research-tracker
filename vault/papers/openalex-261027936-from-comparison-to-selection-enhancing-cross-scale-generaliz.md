---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Vehicle Routing Problem"
description: "This paper investigates the cross-scale generalization degradation of Pointer Networks trained with reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify shifts in node density, attention dispersion, and graph context dilution as key bottlenecks, evaluating architecture-wide, encoder-side, and decoder-side modifications. By combining entropy-based attention scaling for upscaling and a permutation-invariant graph-context aggregation mechanism for downscaling, they propose an approach selector that reduces solution costs across diverse scale pairs by up to 3.2%."
resource: "https://arxiv.org/abs/2610.27936"
tags:
  - "reinforcement-learning"
  - "vehicle-routing-problem"
  - "neural-routing-solver"
  - "combinatorial-optimization"
timestamp: "2026-10-30T11:07:55Z"

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
  - name: "combined-scaling-and-aggregation-multi-scale-training"
    description: "Investigate combining attention rescaling mechanisms and learned graph-context aggregation methods into a single unified model trained simultaneously across multiple problem scales."
  - name: "instance-feature-aware-approach-selection"
    description: "Develop instance-aware approach selection frameworks that incorporate detailed instance features such as client density, spatial distribution, or demand-to-capacity ratios rather than relying solely on global problem scale."
skill: "GeneralMLSkill"
processed_at: "2026-10-30T11:07:55Z"
created_at: "2026-10-30T11:07:55Z"
---

# From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Vehicle Routing Problem

**Authors**: Sofiene Lassoued, Devara Tertia, Stefan Lier, Andreas Schwung
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27936](https://arxiv.org/abs/2610.27936)

## Summary

This paper investigates the cross-scale generalization degradation of Pointer Networks trained with reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify shifts in node density, attention dispersion, and graph context dilution as key bottlenecks, evaluating architecture-wide, encoder-side, and decoder-side modifications. By combining entropy-based attention scaling for upscaling and a permutation-invariant graph-context aggregation mechanism for downscaling, they propose an approach selector that reduces solution costs across diverse scale pairs by up to 3.2%.

## Key Contributions

- Identified three primary factors contributing to cross-scale generalization degradation in Pointer Networks for CVRP: shifts in node density, attention dispersion, and dilution of the mean-pooled graph context.
- Proposed a learned, permutation-invariant graph-context aggregation mechanism (weighted average and Set2Set) improving downscaling transfer from CVRP100 to CVRP20 by approximately 0.9 percentage points.
- Employed entropy-based attention scaling to reduce the CVRP20-to-CVRP100 upscaling performance gap by 1.41 percentage points.
- Introduced an approach selector combining complementary mechanisms to reduce cost by up to 3.2% across seen train-test pairs and most unseen sizes (CVRP35, CVRP75, CVRP200).

## Open Questions & Future Work

- [[combined-scaling-and-aggregation-multi-scale-training]]
- [[instance-feature-aware-approach-selection]]

## Archivist Review

Approved both open questions as they highlight fundamental generalization and selection bottlenecks in neural combinatorial optimization. No concepts were proposed or warranted permanent vault notes.

### Approved Open Questions
- Combined Scale-Aware Multi-Scale Training: Crucial for developing truly size-agnostic neural combinatorial optimization solvers that perform robustly across arbitrary graph scales without requiring problem-specific fine-tuning.
- Instance-Feature-Aware Approach Selection: Enhances routing solution quality by dynamically adapting model selection to fine-grained topological and structural properties of individual test instances.

### Rejected Candidates
- [concept] Combined Scale-Aware Multi-Scale Training (`combined-scaling-and-aggregation-multi-scale-training`) - generic: The input proposed no concept candidates, and the open questions are appropriately scoped for the open_questions list rather than vaults concepts.

## Links

- [Abstract](https://arxiv.org/abs/2610.27936)
- [PDF](https://arxiv.org/pdf/2610.27936)

