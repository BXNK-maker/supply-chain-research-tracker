---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut"
description: "This paper challenges the column generation folklore that initial warm-start columns hurt branch-price-and-cut performance by demonstrating that imperfect, learned column pools combined with smoothed dual pricing significantly accelerate exact solvers. The proposed pipeline employs a neural edge scorer for column generation, a neural network to predict Wentges smoothing centers, and a GPU-accelerated bucket-graph labeling scheme. Evaluated on capacitated vehicle routing and parallel machine scheduling, the approach drastically reduces root pricing time and improves certified bound convergence."
resource: "https://arxiv.org/abs/2610.21001"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-27T10:11:23Z"

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
    description: "Extend the empirical evaluation and algorithmic design of learned column prefilling and dual stabilization beyond the root node to the entire branch-price-and-cut tree, measuring overall impact on total solution time and tree size across diverse problem instances."
skill: "GeneralMLSkill"
processed_at: "2026-10-27T10:11:23Z"
created_at: "2026-10-27T10:11:23Z"
---

# Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut

**Authors**: Haoran Liu, Yu Yang
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.21001](https://arxiv.org/abs/2610.21001)

## Summary

This paper challenges the column generation folklore that initial warm-start columns hurt branch-price-and-cut performance by demonstrating that imperfect, learned column pools combined with smoothed dual pricing significantly accelerate exact solvers. The proposed pipeline employs a neural edge scorer for column generation, a neural network to predict Wentges smoothing centers, and a GPU-accelerated bucket-graph labeling scheme. Evaluated on capacitated vehicle routing and parallel machine scheduling, the approach drastically reduces root pricing time and improves certified bound convergence.

## Key Contributions

- Introduces a learned column prefilling approach for branch-price-and-cut that uses a neural edge scorer and constructive generator to build an imperfect column pool.
- Applies Wentges smoothing with a learned center network to guide pricing queries and stabilize dual variables.
- Rebuilds bucket-graph labeling around a GPU-based dominance test with CPU certification to accelerate pricing.
- Achieves certified root bounds in 13.2% of vanilla RouteOpt's root pricing time on capacitated vehicle routing instances and certifies all parallel machine scheduling benchmarks 12x faster.

## Open Questions & Future Work

- [[full-bpc-tree-evaluation]]

## Archivist Review

No concepts or datasets met the strict novelty and reuse criteria for permanent vault notes. The proposed open question on full BPC tree evaluation directly duplicates an existing vault entry ('full-bpc-tree-evaluation'), and the second question on joint learning of components is a specialized sub-problem closely related to existing adaptation questions.

### Approved Open Questions
- Extending Evaluation to Full BPC Tree: Understanding tree-level behavior is crucial because root-node acceleration does not always guarantee overall branch-and-bound speedups due to interactions with branching and cutting planes.

### Rejected Candidates
- [open_question] Extending Evaluation to Full BPC Tree (`bpc-tree-level-evaluation`) - duplicate_existing: Duplicate or near-equivalent of existing vault open question 'full-bpc-tree-evaluation'.
- [open_question] Co-design of Learned Components (`joint-learning-pool-center`) - duplicate_existing: Similar to existing joint-policy-mitigation-co-adaptation and represents a specialized co-design of internal learned modules rather than a distinct broad vault question.

## Links

- [Abstract](https://arxiv.org/abs/2610.21001)
- [PDF](https://arxiv.org/pdf/2610.21001)

