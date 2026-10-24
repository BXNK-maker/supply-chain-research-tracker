---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Drone Delivery Routing"
description: "This paper investigates the cross-scale generalization degradation of attention-based Pointer Networks trained via reinforcement learning for capacitated drone delivery routing. The authors identify three key failure factors—node density shifts, attention dispersion, and graph context dilution—and propose a learned, permutation-invariant graph-context aggregation mechanism alongside entropy-based attention scaling. Combining these complementary strategies into an approach selector successfully reduces routing costs by up to 3.2 percent across both seen and unseen problem sizes."
resource: "https://arxiv.org/abs/2610.27936"
tags:
  - "reinforcement-learning"
  - "neural-routing-solver"
  - "vehicle-routing-problem"
timestamp: "2026-10-24T09:17:05Z"

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
  - name: "learned-graph-context-aggregation-mechanism"
    description: "A permutation-invariant graph-context aggregation method implemented via weighted averages or Set2Set to improve cross-scale generalization in Pointer Networks."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-24T09:17:05Z"
created_at: "2026-10-24T09:17:05Z"
---

# From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Drone Delivery Routing

**Authors**: Sofiene Lassoued, Devara Tertia, Stefan Lier, Andreas Schwung
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27936](https://arxiv.org/abs/2610.27936)

## Summary

This paper investigates the cross-scale generalization degradation of attention-based Pointer Networks trained via reinforcement learning for capacitated drone delivery routing. The authors identify three key failure factors—node density shifts, attention dispersion, and graph context dilution—and propose a learned, permutation-invariant graph-context aggregation mechanism alongside entropy-based attention scaling. Combining these complementary strategies into an approach selector successfully reduces routing costs by up to 3.2 percent across both seen and unseen problem sizes.

## Key Contributions

- Identified three core factors behind cross-scale generalization degradation in attention-based Pointer Networks: node density shifts, attention dispersion, and graph context dilution.
- Proposed a learned, permutation-invariant graph-context aggregation mechanism using weighted averages and Set2Set to improve cross-scale generalization.
- Demonstrated that entropy-based attention scaling reduces the CVRP20-to-CVRP100 performance gap by 1.41 percentage points.
- Introduced an approach selector that reduces routing cost across seen and unseen train-test problem sizes by up to 3.2 percent.

## Limitations

Evaluated primarily on controlled Capacitated Vehicle Routing Problem (CVRP) proxies for drone delivery routing with fixed capacities.

## Key Concepts

- [[learned-graph-context-aggregation-mechanism]]: A permutation-invariant graph-context aggregation method implemented via weighted averages or Set2Set to improve cross-scale generalization in Pointer Networks.

## Archivist Review

Approved the learned graph-context aggregation mechanism as a reusable and distinct architectural improvement for graph-based routing solvers. Rejected the approach selector as a paper-local ensemble heuristic and rejected the open question as a routine call for larger-scale experiments.

### Approved Concepts
- Learned Graph-Context Aggregation Mechanism: Addresses the dilution of the mean-pooled graph context that causes cross-scale generalization degradation in attention-based Pointer Networks.

### Rejected Candidates
- [concept] Approach Selector (`approach-selector`) - paper_local: This is a paper-specific model selection heuristic rather than a standalone architectural primitive or algorithm that will recur broadly across literature.
- [open_question] Scaling Neural Routing Solvers (`large-scale-cvrp-generalization`) - low_impact: This is a standard call for larger-scale experiments and broader training protocols rather than a deep unresolved structural bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.27936)
- [PDF](https://arxiv.org/pdf/2610.27936)

