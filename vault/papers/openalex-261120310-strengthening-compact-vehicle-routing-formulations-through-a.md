---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Strengthening Compact Vehicle Routing Formulations through Arc-Flow Aggregation and Refinement"
description: "This paper introduces a dual-guided aggregation and refinement framework to construct substantially smaller arc-flow formulations for mixed-integer programming relaxations of vehicle routing problems. By leveraging dual information to identify aggregatable states and guide node disaggregation, the framework achieves finite convergence to the full arc-flow bound without relying on column generation or pricing. Applied to the vehicle routing problem with time windows, the method yields strong root bounds competitive with specialized branch-and-price solvers while remaining solvable via general-purpose MILP solvers."
resource: "https://arxiv.org/abs/2611.20310"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-11-19T14:08:26Z"

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
processed_at: "2026-11-19T14:08:26Z"
created_at: "2026-11-19T14:08:26Z"
---

# Strengthening Compact Vehicle Routing Formulations through Arc-Flow Aggregation and Refinement

**Authors**: Julian Yarkony, Willem‐Jan van Hoeve, Anthony Karahalios, Martin Karyamsetty, Soheyl Khalilpourazari, Louis-Martin Rousseau, Xiaohang Zhu
**Date**: 2026-11-15
**Paper ID**: [openalex:2611.20310](https://arxiv.org/abs/2611.20310)

## Summary

This paper introduces a dual-guided aggregation and refinement framework to construct substantially smaller arc-flow formulations for mixed-integer programming relaxations of vehicle routing problems. By leveraging dual information to identify aggregatable states and guide node disaggregation, the framework achieves finite convergence to the full arc-flow bound without relying on column generation or pricing. Applied to the vehicle routing problem with time windows, the method yields strong root bounds competitive with specialized branch-and-price solvers while remaining solvable via general-purpose MILP solvers.

## Key Contributions

- Introduced a dual-guided aggregation and refinement framework that constructs substantially smaller arc-flow formulations while recovering the LP bound of original networks.
- Showed that the resulting procedure converges finitely to the arc-flow bound of the full arc-flow formulation without column generation or pricing.
- Demonstrated strong bounds on the vehicle routing problem with time windows competitive with branch-and-price solvers while using general-purpose MILP solvers.

## Archivist Review

No concepts or datasets met the strict novelty and reusability criteria for permanent vault entries.

## Links

- [Abstract](https://arxiv.org/abs/2611.20310)
- [PDF](https://arxiv.org/pdf/2611.20310)

