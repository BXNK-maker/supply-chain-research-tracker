---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Strengthening Compact Vehicle Routing Formulations through Arc-Flow Aggregation and Refinement"
description: "This paper introduces a dual-guided aggregation and refinement framework to construct substantially smaller arc-flow formulations for mixed-integer programming relaxations of vehicle routing problems. By leveraging dual information to aggregate and selectively disaggregate states, the approach recovers the exact linear programming bound of the full arc-flow network with finite convergence. The formulation retains original decision variables so that cutting planes can be added directly and solved using general-purpose MILP solvers without column generation. Computational experiments on vehicle routing problems with time windows show that the method achieves root bounds competitive with specialized branch-and-price solvers."
resource: "https://arxiv.org/abs/2611.20310"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-11-20T13:46:43Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Julian Yarkony"
  - literal: "Willem‐Jan van Hoeve"
  - literal: "Anthony Karahalios"
  - literal: "Martin Karyamsetty"
  - literal: "Soheyl Khalilpourazari"
  - literal: "Louis-Martin Rousseau"
  - literal: "Xiaohang Zhu"
issued:
  date-parts:
    - [2026, 11, 15]

# Domain-specific custom fields
paper_id: "2611.20310"
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
processed_at: "2026-11-20T13:46:43Z"
created_at: "2026-11-20T13:46:43Z"
---

# Strengthening Compact Vehicle Routing Formulations through Arc-Flow Aggregation and Refinement

**Authors**: Julian Yarkony, Willem‐Jan van Hoeve, Anthony Karahalios, Martin Karyamsetty, Soheyl Khalilpourazari, Louis-Martin Rousseau, Xiaohang Zhu
**Date**: 2026-11-15
**Paper ID**: [openalex:2611.20310](https://arxiv.org/abs/2611.20310)

## Summary

This paper introduces a dual-guided aggregation and refinement framework to construct substantially smaller arc-flow formulations for mixed-integer programming relaxations of vehicle routing problems. By leveraging dual information to aggregate and selectively disaggregate states, the approach recovers the exact linear programming bound of the full arc-flow network with finite convergence. The formulation retains original decision variables so that cutting planes can be added directly and solved using general-purpose MILP solvers without column generation. Computational experiments on vehicle routing problems with time windows show that the method achieves root bounds competitive with specialized branch-and-price solvers.

## Key Contributions

- Introduced a dual-guided aggregation and refinement framework that constructs substantially smaller arc-flow formulations while recovering the LP bound of original networks for vehicle routing problems.
- Proved that the proposed aggregation and refinement procedure converges finitely to the arc-flow bound of the full arc-flow formulation without relying on column generation or pricing.
- Demonstrated that the framework retains original decision variables, enabling cutting planes to be added directly in the original variable space and solved via general-purpose MILP solvers.
- Achieved root bounds competitive with the specialized branch-and-price solver RouteOpt on the vehicle routing problem with time windows using heavily aggregated networks.

## Archivist Review

Applied strict standards for the vault. No concepts or open questions met the bar for long-term reusability and broad ML or operations research impact, as the proposed framework and open question are highly specific to arc-flow formulations and routing relaxations.

### Rejected Candidates
- [open_question] Dynamic In-Tree Arc-Flow Refinement (`dynamic-in-tree-arc-flow-refinement`) - paper_local: This is a paper-local extension proposing to embed the paper's specific aggregation technique inside a branch-and-bound tree.

## Links

- [Abstract](https://arxiv.org/abs/2611.20310)
- [PDF](https://arxiv.org/pdf/2611.20310)

