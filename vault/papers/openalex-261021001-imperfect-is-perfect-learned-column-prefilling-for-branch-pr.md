---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut"
description: "The paper challenges the conventional folklore that initial columns hurt column generation by demonstrating that an imperfectly constructed pool of columns can significantly accelerate the root of branch-price-and-cut. By combining a neural edge scorer, a learned initial center for Wentges smoothing, and a GPU-accelerated bucket-graph labeling solver, the proposed pipeline drastically reduces root pricing time across large capacitated vehicle routing and parallel machine scheduling benchmarks."
resource: "https://arxiv.org/abs/2610.21001"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-26T10:43:34Z"

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
    description: "Determine the effect of learned prefilling, dual stabilization, and GPU-accelerated exact pricing on the full branch-price-and-cut tree beyond the root node relaxation."
skill: "GeneralMLSkill"
processed_at: "2026-10-26T10:43:34Z"
created_at: "2026-10-26T10:43:34Z"
---

# Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut

**Authors**: Haoran Liu, Yu Yang
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.21001](https://arxiv.org/abs/2610.21001)

## Summary

The paper challenges the conventional folklore that initial columns hurt column generation by demonstrating that an imperfectly constructed pool of columns can significantly accelerate the root of branch-price-and-cut. By combining a neural edge scorer, a learned initial center for Wentges smoothing, and a GPU-accelerated bucket-graph labeling solver, the proposed pipeline drastically reduces root pricing time across large capacitated vehicle routing and parallel machine scheduling benchmarks.

## Key Contributions

- Proposes a learned column prefilling approach for branch-price-and-cut that uses a neural edge scorer and constructive generator to build an imperfect column pool, achieving a 13.2% root pricing time compared to vanilla RouteOpt on capacitated vehicle routing problems.
- Introduces a neural network to predict the initial center of Wentges smoothing from instance files, guiding smoothed pricing queries and accelerating convergence.
- Rebuilds bucket-graph labeling around its dominance test for GPUs with CPU certification, enabling scalable exact pricing for large-scale routing instances.

## Open Questions & Future Work

- [[full-bpc-tree-evaluation]]

## Archivist Review

Applied strict review standards regarding concept novelty and prevention of open-question duplication. The open question about full branch-price-and-cut tree evaluation is already present in the vault under 'full-bpc-tree-evaluation', and the second candidate was deemed a routine architectural combination rather than a foundational research bottleneck. No new concepts or datasets met the strict bar for permanent vault storage.

### Approved Open Questions
- Full Tree Branch-Price-and-Cut Impact: Understanding whether root-node speedups translate into overall tree-level performance improvements is critical for assessing the practical utility of machine-learning-accelerated branch-price-and-cut solvers.

### Rejected Candidates
- [open_question] Full Tree Branch-Price-and-Cut Impact (`full-tree-bpc-impact`) - duplicate_existing: This question is essentially identical to the existing vault open question 'full-bpc-tree-evaluation' and should be merged or dropped to prevent duplication.
- [open_question] Joint Co-Design of Learned Components (`joint-co-design-learned-components`) - not_novel: While interesting, the co-design of separate components is a routine engineering future direction rather than a distinct conceptual bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.21001)
- [PDF](https://arxiv.org/pdf/2610.21001)

