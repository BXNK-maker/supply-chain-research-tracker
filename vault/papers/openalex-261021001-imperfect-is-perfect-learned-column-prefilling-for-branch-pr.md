---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut"
description: "This paper challenges the conventional wisdom that warm-starting column generation hurts branch-price-and-cut performance by demonstrating that imperfect columns and learned smoothed dual initialization drastically speed up root node convergence. The authors introduce a pipeline combining a neural edge scorer for column prefilling, a neural predictor for Wentges smoothing centers, and GPU-accelerated bucket-graph labeling. Evaluated on large capacitated vehicle routing and parallel machine scheduling problems, the approach achieves dramatic speedups and certifies instances that standard solvers fail to complete."
resource: "https://arxiv.org/abs/2610.21001"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
  - "machine-learning"
timestamp: "2026-10-19T10:28:03Z"

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
    description: "A machine learning technique that feeds imperfect columns and predicted smoothing centers into column generation solvers to dramatically accelerate branch-price-and-cut root node convergence."
datasets:
  []
open_questions:
  - name: "full-bpc-tree-evaluation"
    description: "Extending the evaluation of the learned prefill and dual stabilization pipeline from root pricing to the full branch-price-and-cut search tree across large-scale optimization instances."
skill: "GeneralMLSkill"
processed_at: "2026-10-19T10:28:03Z"
created_at: "2026-10-19T10:28:03Z"
---

# Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut

**Authors**: Haoran Liu, Yu Yang
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.21001](https://arxiv.org/abs/2610.21001)

## Summary

This paper challenges the conventional wisdom that warm-starting column generation hurts branch-price-and-cut performance by demonstrating that imperfect columns and learned smoothed dual initialization drastically speed up root node convergence. The authors introduce a pipeline combining a neural edge scorer for column prefilling, a neural predictor for Wentges smoothing centers, and GPU-accelerated bucket-graph labeling. Evaluated on large capacitated vehicle routing and parallel machine scheduling problems, the approach achieves dramatic speedups and certifies instances that standard solvers fail to complete.

## Key Contributions

- Proposes learned column prefilling using imperfect columns and smoothed dual initialization to accelerate branch-price-and-cut root nodes, overcoming traditional folklore against warm-starting column generation.
- Achieves root pricing time reduction to 13.2% of vanilla RouteOpt's time over 95 large-scale capacitated vehicle routing instances (300 to 1000 customers).
- Certifies all 25 unrelated parallel machine scheduling benchmark instances 12 times faster than vanilla column generation, which only certifies 20.

## Open Questions & Future Work

- [[full-bpc-tree-evaluation]]

## Key Concepts

- [[learned-column-prefilling]]: A machine learning technique that feeds imperfect columns and predicted smoothing centers into column generation solvers to dramatically accelerate branch-price-and-cut root node convergence.

## Archivist Review

Approved the core concept of learned column prefilling and the open question evaluating full branch-price-and-cut tree performance. Rejected the routine future work on joint model co-design and omitted generic benchmark datasets.

### Approved Concepts
- Learned Column Prefilling: Introduces a learned column prefilling approach with imperfect columns and smoothed dual initialization to accelerate branch-price-and-cut root nodes.

### Approved Open Questions
- Extending Evaluation to Full BPC Trees: Evaluating performance solely at the root node leaves open whether these learned column generation accelerations translate to net speedups across full exact branch-and-bound tree searches.

### Rejected Candidates
- [open_question] Co-designing Learned Components (`co-design-learned-components`) - not_novel: Generic future work proposing to jointly train or co-design independently developed neural modules.

## Links

- [Abstract](https://arxiv.org/abs/2610.21001)
- [PDF](https://arxiv.org/pdf/2610.21001)

