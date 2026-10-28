---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut"
description: "This paper challenges the column generation folklore that warm-start initial columns slow down the root of branch-price-and-cut by demonstrating that imperfect, learned column prefilling combined with smoothed dual pricing significantly accelerates convergence. The authors introduce a neural edge scorer to construct a pool of ordinary routes and a second network to predict the initial center for Wentges smoothing, achieving massive speedups on both capacitated vehicle routing and unrelated parallel machine scheduling benchmarks."
resource: "https://arxiv.org/abs/2610.21001"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-10-28T11:00:22Z"

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
    description: "A machine-learning-guided column prefilling and smoothing technique for accelerating branch-price-and-cut solvers."
datasets:
  []
open_questions:
  - name: "bpc-tree-wide-impact-learned-column-prefilling"
    description: "Investigate the downstream effects of learned column prefilling and dual center prediction throughout the entire branch-and-bound tree in branch-price-and-cut algorithms, moving beyond root node performance evaluations to understand tree-wide scalability and interaction with branching and cutting decisions."
skill: "GeneralMLSkill"
processed_at: "2026-10-28T11:00:22Z"
created_at: "2026-10-28T11:00:22Z"
---

# Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut

**Authors**: Haoran Liu, Yu Yang
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.21001](https://arxiv.org/abs/2610.21001)

## Summary

This paper challenges the column generation folklore that warm-start initial columns slow down the root of branch-price-and-cut by demonstrating that imperfect, learned column prefilling combined with smoothed dual pricing significantly accelerates convergence. The authors introduce a neural edge scorer to construct a pool of ordinary routes and a second network to predict the initial center for Wentges smoothing, achieving massive speedups on both capacitated vehicle routing and unrelated parallel machine scheduling benchmarks.

## Key Contributions

- Proposes learned column prefilling using a neural edge scorer and constructive generator to accelerate the root node of branch-price-and-cut solvers.
- Combines learned column prefilling with Wentges smoothing, where a second network predicts the initial smoothing center to direct pricing queries.
- Accelerates the root pricing time of RouteOpt to 13.2% of vanilla solver time over 95 instances with 300 to 1000 customers.
- Certifies all 25 benchmark instances in an exact branch-price-and-cut solver for unrelated parallel machine scheduling, achieving a 12x speedup.

## Open Questions & Future Work

- [[bpc-tree-wide-impact-learned-column-prefilling]]

## Key Concepts

- [[learned-column-prefilling]]: A machine-learning-guided column prefilling and smoothing technique for accelerating branch-price-and-cut solvers.

## Archivist Review

Approved the central concept of learned column prefilling and the meaningful open question regarding tree-wide branch-price-and-cut evaluation. Rejected the co-design question as standard architectural combination future work.

### Approved Concepts
- Learned Column Prefilling: Challenges column generation folklore by showing that learned, imperfect initial columns accelerate branch-price-and-cut root node solving.

### Approved Open Questions
- Full BPC Tree-Wide Evaluation: Understanding whether root-level speedups translate to full branch-and-bound tree efficiency is critical for establishing the practical utility of learned column generation and dual stabilization methods in integer programming.

### Rejected Candidates
- [open_question] Co-design of Primal-Dual Learned Components (`co-design-primal-dual-learning-components`) - not_novel: Routine future work proposing joint training or model combination without a distinct structural bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.21001)
- [PDF](https://arxiv.org/pdf/2610.21001)

