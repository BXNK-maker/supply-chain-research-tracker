---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones"
description: "This paper studies the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, where trucks act as mobile hubs carrying drone fleets to service sparse rural demands. The authors formulate a mixed-integer quadratic programming model capturing customer delays, truck return times, and operating costs. To solve it exactly, they develop a network-transformed branch-price-and-cut algorithm equipped with tailored pricing, cutting, branching, and parallel-computing routines. Computational results show the algorithm proves optimality for most large-scale instances and achieves small optimality gaps under 4% where exact proofs are not reached within time limits."
resource: "https://arxiv.org/abs/2610.15016"
tags:
  - "vehicle-routing-problem"
  - "fleet-scheduling"
timestamp: "2026-10-20T09:47:17Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Fan Pu"
  - literal: "Sivakumar Rathinam"
  - literal: "Yunlong Zhang"
  - literal: "Xiaopeng Li"
  - literal: "Xiubin Wang"
  - literal: "Yang Zhou"
  - literal: "Fan Pu"
  - literal: "Sivakumar Rathinam"
  - literal: "Yunlong Zhang"
  - literal: "Xiaopeng Li"
  - literal: "Xiubin Wang"
  - literal: "Yang Zhou"
issued:
  date-parts:
    - [2026, 10, 10]

# Domain-specific custom fields
paper_id: "2610.15016"
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
processed_at: "2026-10-20T09:47:17Z"
created_at: "2026-10-20T09:47:17Z"
---

# An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones

**Authors**: Fan Pu, Sivakumar Rathinam, Yunlong Zhang, Xiaopeng Li, Xiubin Wang, Yang Zhou, Fan Pu, Sivakumar Rathinam, Yunlong Zhang, Xiaopeng Li, Xiubin Wang, Yang Zhou
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15016](https://arxiv.org/abs/2610.15016)

## Summary

This paper studies the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, where trucks act as mobile hubs carrying drone fleets to service sparse rural demands. The authors formulate a mixed-integer quadratic programming model capturing customer delays, truck return times, and operating costs. To solve it exactly, they develop a network-transformed branch-price-and-cut algorithm equipped with tailored pricing, cutting, branching, and parallel-computing routines. Computational results show the algorithm proves optimality for most large-scale instances and achieves small optimality gaps under 4% where exact proofs are not reached within time limits.

## Key Contributions

- Formulated a mixed-integer quadratic programming model for a Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, jointly accounting for customer delivery delays, truck return times, and operating costs.
- Developed an exact branch-price-and-cut algorithm incorporating network transformation, tailored pricing, cutting, branching, and parallel-computing procedures.
- Demonstrated through computational experiments that the proposed algorithm proves optimality for most large-scale instances and achieves optimality gaps of under 4% for the remainder, outperforming direct Gurobi solves on compact formulations.

## Archivist Review

Applied strict selectivity criteria. The paper proposes a domain-specific branch-price-and-cut algorithm for a specific vehicle routing variant (Truck-as-Hub VRP with Drones), which is too application-specific and specialized for permanent vault notes. The proposed open questions are standard operational extensions (facility location integration and stochasticity/heterogeneity) rather than fundamental or reusable methodological bottlenecks.

### Rejected Candidates
- [open_question] Joint Optimization of Pad Location and Routing (`joint-optimization-pad-location-routing`) - low_impact: Standard facility location-routing extension without a specific algorithmic bottleneck or conceptual mechanism defined.
- [open_question] Uncertainty and Heterogeneous Fleet in TH-VRPD (`uncertainty-heterogeneous-fleet-th-vrpd`) - low_impact: Standard extension into stochasticity and heterogeneity for a specific application domain rather than a fundamental theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.15016)
- [PDF](https://arxiv.org/pdf/2610.15016)

