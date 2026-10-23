---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut"
description: "This paper challenges column generation folklore by demonstrating that imperfect, learned column prefilling combined with neural dual smoothing centers dramatically accelerates branch-price-and-cut solvers. The proposed pipeline leverages a neural edge scorer to construct a pool of suboptimal columns and predicts Wentges smoothing centers, avoiding the dual bias that typically plagues optimal warm-starts. Integrated into state-of-the-art exact solvers for capacitated vehicle routing and parallel machine scheduling, the approach achieves massive speedups while certifying optimal bounds on large-scale benchmarks."
resource: "https://arxiv.org/abs/2610.21001"
tags:
  - "combinatorial-optimization"
  - "machine-learning"
  - "neural-routing-solver"
timestamp: "2026-10-23T09:45:38Z"

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
    description: "A warm-start technique for branch-price-and-cut that uses a neural generator to construct a pool of imperfect columns paired with learned dual smoothing centers."
datasets:
  []
open_questions:
  - name: "full-bpc-tree-evaluation"
    description: "The current evaluation primarily focuses on root pricing and the root bound certification stage. Extending the analysis to evaluate the impact of learned column prefilling, learned dual centers, and GPU-accelerated exact pricing across the entire branch-price-and-cut tree (including branching decisions, subsequent cut rounds, and overall wall-clock time to proven optimality) remains an open challenge."
skill: "GeneralMLSkill"
processed_at: "2026-10-23T09:45:38Z"
created_at: "2026-10-23T09:45:38Z"
---

# Imperfect Is Perfect: Learned Column Prefilling for Branch-Price-and-Cut

**Authors**: Haoran Liu, Yu Yang
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.21001](https://arxiv.org/abs/2610.21001)

## Summary

This paper challenges column generation folklore by demonstrating that imperfect, learned column prefilling combined with neural dual smoothing centers dramatically accelerates branch-price-and-cut solvers. The proposed pipeline leverages a neural edge scorer to construct a pool of suboptimal columns and predicts Wentges smoothing centers, avoiding the dual bias that typically plagues optimal warm-starts. Integrated into state-of-the-art exact solvers for capacitated vehicle routing and parallel machine scheduling, the approach achieves massive speedups while certifying optimal bounds on large-scale benchmarks.

## Key Contributions

- Introduces learned column prefilling using a neural edge scorer and constructive generator to rapidly construct pools of imperfect warm-start columns for branch-price-and-cut.
- Combines column prefilling with a neural predictor for Wentges smoothing centers, mitigating dual bias and accelerating root pricing queries.
- Reaches the same certified root bound in 13.2% of vanilla RouteOpt's root pricing time across large capacitated vehicle routing instances (300 to 1000 customers).
- Certifies all 25 benchmark instances in unrelated parallel machine scheduling, achieving a 12x speedup over vanilla column generation.

## Open Questions & Future Work

- [[full-bpc-tree-evaluation]]

## Key Concepts

- [[learned-column-prefilling]]: A warm-start technique for branch-price-and-cut that uses a neural generator to construct a pool of imperfect columns paired with learned dual smoothing centers.

## Archivist Review

The concept 'Learned Column Prefilling' is already present in the vault as an existing concept and is approved. The open question 'Full Branch-Price-And-Cut Tree Evaluation' is also already in the vault as an existing entry and is approved. The second open question about co-designing learned components is rejected as a routine future work suggestion.

### Approved Concepts
- Learned Column Prefilling: Introduces a paradigm shift in branch-price-and-cut warm-starting by showing that imperfect, learned column pools outperform optimal columns when combined with smoothed dual pricing.

### Approved Open Questions
- Full Branch-Price-And-Cut Tree Evaluation: Understanding tree-level impacts is crucial for establishing whether root-node accelerations translate into end-to-end wall-clock speedups for full branch-and-bound exact optimization.

### Rejected Candidates
- [open_question] Co-Design of Learned Components (`co-design-learned-components`) - low_impact: Routine future work suggesting joint modeling of independently designed neural subcomponents.

## Links

- [Abstract](https://arxiv.org/abs/2610.21001)
- [PDF](https://arxiv.org/pdf/2610.21001)

