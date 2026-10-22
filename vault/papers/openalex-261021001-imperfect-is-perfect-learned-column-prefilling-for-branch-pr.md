---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut"
description: "This paper demonstrates that column generation warm starts—traditionally believed to hurt root convergence due to dual bias—can substantially accelerate branch-price-and-cut when using imperfect columns and smoothed duals. The authors propose a learning pipeline featuring a neural edge scorer to build a pool of columns and a network to predict the initial center of Wentges smoothing. Integrated into exact solvers for capacitated vehicle routing and parallel machine scheduling, the approach drastically reduces root pricing time and certifies difficult instances previously unsolved by vanilla solvers."
resource: "https://arxiv.org/abs/2610.21001"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "machine-learning"
  - "approximation-algorithms"
timestamp: "2026-10-22T09:49:37Z"

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
    description: "A learning-based approach that supplies imperfect columns and smoothed dual centers to accelerate branch-price-and-cut root node pricing."
datasets:
  []
open_questions:
  - name: "full-bpc-tree-evaluation"
    description: "Extend the evaluation of the learned prefilling and dual center pipeline from root pricing and root relaxation bounds to the full branch-and-bound tree in branch-price-and-cut solvers."
skill: "GeneralMLSkill"
processed_at: "2026-10-22T09:49:37Z"
created_at: "2026-10-22T09:49:37Z"
---

# Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut

**Authors**: Haoran Liu, Yu Yang
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.21001](https://arxiv.org/abs/2610.21001)

## Summary

This paper demonstrates that column generation warm starts—traditionally believed to hurt root convergence due to dual bias—can substantially accelerate branch-price-and-cut when using imperfect columns and smoothed duals. The authors propose a learning pipeline featuring a neural edge scorer to build a pool of columns and a network to predict the initial center of Wentges smoothing. Integrated into exact solvers for capacitated vehicle routing and parallel machine scheduling, the approach drastically reduces root pricing time and certifies difficult instances previously unsolved by vanilla solvers.

## Key Contributions

- Achieves root pricing times in RouteOpt that are 13.2% of vanilla RouteOpt over 95 instances with 300 to 1000 customers (and 17.5x faster in the best case) using learned column prefilling and smoothing.
- Certifies all 25 unrelated parallel machine scheduling benchmark instances 12 times faster than vanilla column generation, which only certifies 20.
- Combines a neural edge scorer with a constructive generator to produce imperfect column pools and a network predicting the initial center of Wentges smoothing.
- Rebuilds bucket-graph labeling around its dominance test for GPU execution while certifying on the CPU to handle the dominance of exact pricing time.

## Limitations

Evaluated primarily on capacitated vehicle routing and parallel machine scheduling problems.

## Open Questions & Future Work

- [[full-bpc-tree-evaluation]]

## Key Concepts

- [[learned-column-prefilling]]: A learning-based approach that supplies imperfect columns and smoothed dual centers to accelerate branch-price-and-cut root node pricing.

## Archivist Review

Approved the concept of learned column prefilling as a novel and reusable algorithmic mechanism merging learning with branch-price-and-cut. Approved one open question regarding full branch-price-and-cut tree evaluation due to its methodological importance, while rejecting the co-design question as a routine architectural exploration.

### Approved Concepts
- Learned Column Prefilling: Introduces a learning-based warm start strategy using imperfect columns and smoothed duals to speed up branch-price-and-cut root solving.

### Approved Open Questions
- Evaluating Full Branch-Price-and-Cut Tree: Understanding the propagation of root-level accelerations through the entire branching tree is critical to confirm whether wall-clock savings at the root translate to overall exact solution times on very large instances.

### Rejected Candidates
- [open_question] Co-design of Learned Components (`joint-learned-components-codesign`) - not_novel: Routine architectural co-design and joint training exploration without a specific unresolved bottleneck that differentiates it from general ML systems practice.

## Links

- [Abstract](https://arxiv.org/abs/2610.21001)
- [PDF](https://arxiv.org/pdf/2610.21001)

