---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut"
description: "This paper challenges the column generation folklore that initial warm-start columns harm branch-price-and-cut by demonstrating that imperfect, non-optimal route pools generated via neural edge scorers and smoothed dual centers can significantly accelerate root node solving. By integrating learned column prefilling, Wentges smoothing center prediction, and a GPU-accelerated bucket-graph labeling pricing solver, the proposed pipeline drastically reduces root pricing time in state-of-the-art exact solvers for capacitated vehicle routing and parallel machine scheduling."
resource: "https://arxiv.org/abs/2610.21001"
tags:
  - "combinatorial-optimization"
  - "reinforcement-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-25T09:33:28Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Haoran Liu"
  - literal: "Yu Yang"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.21001"
paper_source: "openalex"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "full-bpc-tree-evaluation"
    description: "Extend the current empirical analysis of learned column prefilling and dual center prediction from root pricing performance to the entire branch-price-and-cut search tree, evaluating how these components interact with branching decisions, cutting planes, and overall exact solution times on large-scale instances."
  - name: "joint-primal-dual-learning"
    description: "Develop a unified co-design methodology or joint neural architecture that simultaneously predicts the candidate column pool and the dual stabilization center, capturing the structural interdependencies between the primal column generation space and the dual pricing trajectory."
skill: "GeneralMLSkill"
processed_at: "2026-10-25T09:33:28Z"
created_at: "2026-10-25T09:33:28Z"
---

# Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut

**Authors**: Haoran Liu, Yu Yang
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.21001](https://arxiv.org/abs/2610.21001)

## Summary

This paper challenges the column generation folklore that initial warm-start columns harm branch-price-and-cut by demonstrating that imperfect, non-optimal route pools generated via neural edge scorers and smoothed dual centers can significantly accelerate root node solving. By integrating learned column prefilling, Wentges smoothing center prediction, and a GPU-accelerated bucket-graph labeling pricing solver, the proposed pipeline drastically reduces root pricing time in state-of-the-art exact solvers for capacitated vehicle routing and parallel machine scheduling.

## Key Contributions

- Introduced a learned column prefilling approach for branch-price-and-cut that uses ordinary routes instead of optimal solutions to warm-start column generation.
- Combined neural edge scoring with Wentges smoothing center prediction to accelerate root node pricing and dual stabilization.
- Engineered a GPU-accelerated bucket-graph labeling algorithm with CPU certification to handle exact pricing dominance.
- Accelerated RouteOpt root pricing time to 13.2% of vanilla time over large capacitated vehicle routing instances (300 to 1000 customers) and certified all instances in an unrelated parallel machine scheduling benchmark 12 times faster.

## Limitations

Limited to vehicle routing and parallel machine scheduling problem instances evaluated in the paper.

## Open Questions & Future Work

- [[full-bpc-tree-evaluation]]
- [[joint-primal-dual-learning]]

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 0 concept(s), 2 open question(s), and 0 dataset(s), with 1 rejected candidate note(s).

### Approved Open Questions
- Full Branch-Price-And-Cut Tree Evaluation: While root pricing is a critical bottleneck, practical exact solvers must optimize the complete branch-and-bound/price-and-cut tree; understanding downstream interactions is essential for holistic combinatorial optimization solver design.
- Joint Primal-Dual Learning Integration: Jointly learning primal column distributions and dual centers could mitigate misalignment between prefilled columns and dual stabilization queries, yielding tighter integration and further efficiency gains.

### Rejected Candidates
- [concept] learned column prefilling (`learned-column-prefilling`) - duplicate_existing: Already exists in the vault under 'learned-column-prefilling'.

## Links

- [Abstract](https://arxiv.org/abs/2610.21001)
- [PDF](https://arxiv.org/pdf/2610.21001)

