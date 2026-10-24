---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut"
description: "The paper introduces a learned column prefilling approach for branch-price-and-cut solvers, challenging the conventional wisdom that initial warm-start columns slow down root node convergence due to dual bias. By generating a pool of non-optimal, ordinary routes via a neural edge scorer and combining it with a neural network predicting Wentges smoothing centers, the proposed pipeline drastically accelerates root node pricing. Evaluated on capacitated vehicle routing and unrelated parallel machine scheduling benchmarks, the method achieves dramatic speedups and solves previously intractable instances."
resource: "https://arxiv.org/abs/2610.21001"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
  - "reinforcement-learning"
timestamp: "2026-10-24T09:16:58Z"

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
    description: "A machine learning approach for preloading imperfect columns to warm-start branch-price-and-cut solvers without causing dual bias."
datasets:
  []
open_questions:
  - name: "full-bpc-tree-evaluation"
    description: "Extending the evaluation of learned prefilling and dual stabilization from root pricing to the entire branch-price-and-cut tree, including how prefilled columns and learned initial centers affect downstream branching, cut selection, and overall exact solution time across diverse problem classes."
skill: "GeneralMLSkill"
processed_at: "2026-10-24T09:16:58Z"
created_at: "2026-10-24T09:16:58Z"
---

# Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut

**Authors**: Haoran Liu, Yu Yang
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.21001](https://arxiv.org/abs/2610.21001)

## Summary

The paper introduces a learned column prefilling approach for branch-price-and-cut solvers, challenging the conventional wisdom that initial warm-start columns slow down root node convergence due to dual bias. By generating a pool of non-optimal, ordinary routes via a neural edge scorer and combining it with a neural network predicting Wentges smoothing centers, the proposed pipeline drastically accelerates root node pricing. Evaluated on capacitated vehicle routing and unrelated parallel machine scheduling benchmarks, the method achieves dramatic speedups and solves previously intractable instances.

## Key Contributions

- Proposes learned column prefilling using a neural edge scorer and constructive generator to warm-start branch-price-and-cut root nodes.
- Introduces a neural network to predict the initial center of Wentges smoothing, guiding smoothed pricing queries efficiently.
- Rebuilds bucket-graph labeling around GPU dominance tests with CPU certification to handle exact pricing dominance.
- Achieves certified root bounds in 13.2% of vanilla RouteOpt's root pricing time over 95 large capacitated vehicle routing instances (300 to 1000 customers).
- Certifies all 25 unrelated parallel machine scheduling benchmark instances 12 times faster than standard column generation.

## Open Questions & Future Work

- [[full-bpc-tree-evaluation]]

## Key Concepts

- [[learned-column-prefilling]]: A machine learning approach for preloading imperfect columns to warm-start branch-price-and-cut solvers without causing dual bias.

## Archivist Review

Approved learned-column-prefilling because it represents a distinct, reusable paradigm shift in column generation warm-starting. Approved full-bpc-tree-evaluation as a concrete unresolved bottleneck regarding tree-level propagation. Rejected the second open question as a generic modular co-design request applicable to any multi-network pipeline.

### Approved Concepts
- Learned Column Prefilling: Introduces a paradigm shift in column generation for branch-price-and-cut by showing that imperfect, learned columns can warm-start the root LP effectively without dual bias issues.

### Approved Open Questions
- Evaluating Full Branch-Price-and-Cut Tree: Understanding the downstream effects on the full branch-and-bound tree is crucial to determine whether root-level speedups translate to overall exact solution time improvements.

### Rejected Candidates
- [open_question] Co-designing Learned Generation Components (`co-design-learned-components`) - generic: This open question requests a generic architectural co-design (jointly training separate models) that applies broadly to any pipeline with multiple learned submodules rather than being a specific algorithmic bottleneck unique to branch-price-and-cut solvers.

## Links

- [Abstract](https://arxiv.org/abs/2610.21001)
- [PDF](https://arxiv.org/pdf/2610.21001)

