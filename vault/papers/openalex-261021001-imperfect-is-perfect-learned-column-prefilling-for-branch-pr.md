---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut"
description: "The paper challenges the conventional wisdom that initial columns hurt branch-price-and-cut by demonstrating that imperfect, learned column pools combined with predicted Wentges smoothing centers dramatically accelerate root node convergence. Using neural network generators for column prefilling and smoothing guidance, alongside GPU-accelerated bucket-graph labeling, the proposed pipeline achieves order-of-magnitude speedups on capacitated vehicle routing and parallel machine scheduling solvers without sacrificing exactness."
resource: "https://arxiv.org/abs/2610.21001"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "machine-learning"
timestamp: "2026-10-18T09:18:35Z"

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
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-18T09:18:35Z"
created_at: "2026-10-18T09:18:35Z"
---

# Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut

**Authors**: Haoran Liu, Yu Yang
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.21001](https://arxiv.org/abs/2610.21001)

## Summary

The paper challenges the conventional wisdom that initial columns hurt branch-price-and-cut by demonstrating that imperfect, learned column pools combined with predicted Wentges smoothing centers dramatically accelerate root node convergence. Using neural network generators for column prefilling and smoothing guidance, alongside GPU-accelerated bucket-graph labeling, the proposed pipeline achieves order-of-magnitude speedups on capacitated vehicle routing and parallel machine scheduling solvers without sacrificing exactness.

## Key Contributions

- Introduces learned column prefilling using a neural edge scorer and constructive generator to build imperfect initial column pools, achieving significant root pricing time reductions in branch-price-and-cut solvers.
- Develops a neural network to predict the initial center of Wentges smoothing, guiding smoothed pricing queries and stabilizing dual updates.
- Rebuilds bucket-graph labeling around its dominance test for GPU acceleration with CPU certification, enabling high-performance exact pricing.
- Achieves root pricing times reduced to 13.2% of vanilla RouteOpt over 95 large-scale CVRPTW/CVRP instances and certifies all 25 parallel machine scheduling instances 12x faster.

## Archivist Review

Reviewed the candidates against the vault policy and decided to reject all of them. The proposed concept of learned column prefilling is too specific to branch-price-and-cut operations research solvers, and the open questions are paper-local evaluation and module co-design questions rather than foundational ML research bottlenecks.

### Rejected Candidates
- [concept] Learned Column Prefilling (`learned-column-prefilling`) - low_impact: This is a specialized technique combining neural network column generation and Wentges smoothing tailored specifically for branch-price-and-cut solvers, representing a narrow domain application rather than a broadly reusable ML vault concept.
- [open_question] Evaluating Full Branch-Price-and-Cut Tree (`bpc-tree-evaluation`) - paper_local: This asks for evaluating full branch-and-bound tree solving times for a specific operations research solver, which is too paper-local and solver-specific rather than a foundational ML research bottleneck.
- [open_question] Co-designing Learned Components (`co-design-learned-components`) - not_novel: This is a standard boilerplate future work suggestion about jointly training two independent modules rather than a distinct, widely applicable open research question.

## Links

- [Abstract](https://arxiv.org/abs/2610.21001)
- [PDF](https://arxiv.org/pdf/2610.21001)

