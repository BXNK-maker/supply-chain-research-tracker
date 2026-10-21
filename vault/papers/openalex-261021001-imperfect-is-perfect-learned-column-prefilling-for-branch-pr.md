---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut"
description: "The paper challenges the conventional wisdom that initial columns hurt column generation by showing that imperfect, non-optimal column pools generated via a neural edge scorer can significantly accelerate branch-price-and-cut root convergence. Combined with a neural network predicting the initial center for Wentges smoothing, the proposed pipeline drastically reduces root pricing time across large-scale capacitated vehicle routing and parallel machine scheduling instances."
resource: "https://arxiv.org/abs/2610.21001"
tags:
  - "combinatorial-optimization"
  - "neural-routing-solver"
timestamp: "2026-10-21T09:48:07Z"

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
  - name: "learned-column-prefilling"
    description: "A learning-based warm-starting technique for branch-price-and-cut that uses a neural edge scorer to generate a pool of imperfect columns, accelerating root node convergence."
datasets:
  []
open_questions:
  - name: "full-bpc-tree-evaluation"
    description: "Extend the performance evaluation and impact analysis of the learned column prefilling and dual stabilization pipeline from the root pricing phase to the entire branch-price-and-cut tree, specifically examining how these components affect tree size, total nodes explored, and overall end-to-end solving time across large-scale optimization instances."
skill: "GeneralMLSkill"
processed_at: "2026-10-21T09:48:07Z"
created_at: "2026-10-21T09:48:07Z"
---

# Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut

**Authors**: Haoran Liu, Yu Yang
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.21001](https://arxiv.org/abs/2610.21001)

## Summary

The paper challenges the conventional wisdom that initial columns hurt column generation by showing that imperfect, non-optimal column pools generated via a neural edge scorer can significantly accelerate branch-price-and-cut root convergence. Combined with a neural network predicting the initial center for Wentges smoothing, the proposed pipeline drastically reduces root pricing time across large-scale capacitated vehicle routing and parallel machine scheduling instances.

## Key Contributions

- Demonstrates that imperfect, non-optimal column pools generated via neural networks accelerate branch-price-and-cut roots compared to optimal column preloading.
- Proposes a learned center prediction method for Wentges smoothing to guide smoothed pricing queries.
- Achieves the same certified root bound in 13.2% of vanilla RouteOpt's root pricing time over 95 instances (300 to 1000 customers).
- Certifies all 25 parallel machine scheduling benchmark instances 12 times faster than vanilla column generation.

## Limitations

Evaluated primarily on capacitated vehicle routing and parallel machine scheduling solvers; effectiveness on broader combinatorial optimization problems requires further study.

## Open Questions & Future Work

- [[full-bpc-tree-evaluation]]

## Key Concepts

- [[learned-column-prefilling]]: A learning-based warm-starting technique for branch-price-and-cut that uses a neural edge scorer to generate a pool of imperfect columns, accelerating root node convergence.

## Archivist Review

Approved the core concept 'Learned Column Prefilling' which is already present in the vault and maps directly to the paper's primary contribution. Reused the existing canonical slug 'full-bpc-tree-evaluation' for the open question, while rejecting the second open question as routine future work.

### Approved Concepts
- Learned Column Prefilling: Introduces a paradigm shift in column generation warm-starting by demonstrating that imperfect, non-optimal column pools generated via neural networks accelerate branch-price-and-cut roots compared to optimal column preloading.

### Approved Open Questions
- Branch-Price-And-Cut Tree Evaluation: Understanding the downstream effects of root-level column prefilling and dual center learning on the complete branch-and-bound tree is crucial for determining whether these speed-ups translate to overall end-to-end exact solution times for large-scale NP-hard problems.

### Rejected Candidates
- [open_question] Joint Co-Design of Learned Components (`joint-co-design-learned-components`) - not_novel: Generic future work suggestion about joint model design that lacks specific algorithmic formulation.

## Links

- [Abstract](https://arxiv.org/abs/2610.21001)
- [PDF](https://arxiv.org/pdf/2610.21001)

