---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut"
description: "The paper challenges column generation folklore by showing that warm-starting branch-price-and-cut with imperfect learned columns—rather than optimal ones—significantly accelerates the root node. By combining a neural edge scorer, a constructive generator for column pools, and a network for predicting Wentges smoothing centers, the proposed pipeline achieves dramatic speedups in state-of-the-art exact solvers for capacitated vehicle routing and parallel machine scheduling."
resource: "https://arxiv.org/abs/2610.21001"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-20T09:47:43Z"

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
    description: "A machine learning approach that generates imperfect initial columns using a neural edge scorer and constructive generator to warm-start branch-price-and-cut solvers."
datasets:
  []
open_questions:
  - name: "full-bpc-tree-evaluation"
    description: "The evaluation of learned column prefilling and dual stabilization is primarily concentrated at the root relaxation stage due to the computational scale of the benchmark instances, leaving the broader impact on the full branch-price-and-cut tree search an unresolved direction for future work."
skill: "GeneralMLSkill"
processed_at: "2026-10-20T09:47:43Z"
created_at: "2026-10-20T09:47:43Z"
---

# Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut

**Authors**: Haoran Liu, Yu Yang
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.21001](https://arxiv.org/abs/2610.21001)

## Summary

The paper challenges column generation folklore by showing that warm-starting branch-price-and-cut with imperfect learned columns—rather than optimal ones—significantly accelerates the root node. By combining a neural edge scorer, a constructive generator for column pools, and a network for predicting Wentges smoothing centers, the proposed pipeline achieves dramatic speedups in state-of-the-art exact solvers for capacitated vehicle routing and parallel machine scheduling.

## Key Contributions

- Introduces learned column prefilling using a neural edge scorer and constructive generator to warm-start branch-price-and-cut solvers with imperfect columns.
- Demonstrates that preloading a pool of ordinary routes priced at a smoothed dual speeds up the root node, whereas preloading optimal columns fails on half of the hardest instances.
- Achieves the same certified root bound in 13.2% of vanilla RouteOpt's root pricing time over 95 instances (300 to 1000 customers), and is 12 times faster in exact parallel machine scheduling.

## Limitations

None explicitly stated in the abstract.

## Open Questions & Future Work

- [[full-bpc-tree-evaluation]]

## Key Concepts

- [[learned-column-prefilling]]: A machine learning approach that generates imperfect initial columns using a neural edge scorer and constructive generator to warm-start branch-price-and-cut solvers.

## Archivist Review

Approved the central concept 'learned-column-prefilling' and mapped the open question on BPC tree evaluation to the existing canonical vault slug 'full-bpc-tree-evaluation'. Rejected the co-design question as standard modular consolidation future work.

### Approved Concepts
- Learned Column Prefilling: Central to the paper's novel approach of using imperfect learned columns rather than optimal ones to warm-start branch-price-and-cut.

### Approved Open Questions
- Extending Root Pricing to Full BPC Tree: Extending optimization enhancements from the root node to the full tree search is critical for understanding scalability in exact combinatorial solvers.

### Rejected Candidates
- [open_question] Co-design of Learned Column Generation Components (`co-design-of-learned-column-generation-components`) - not_novel: Routine future work proposal suggesting the combination of two independently designed modules into a joint architecture.

## Links

- [Abstract](https://arxiv.org/abs/2610.21001)
- [PDF](https://arxiv.org/pdf/2610.21001)

