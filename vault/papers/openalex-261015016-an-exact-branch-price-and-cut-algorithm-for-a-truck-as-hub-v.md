---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones"
description: "This paper studies the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, where trucks act as mobile hubs carrying drone fleets to service sparse rural demands. The authors formulate a mixed-integer quadratic programming model capturing delivery delays, return times, and operating costs. To solve this problem exactly, they introduce a network transformation to represent feasible routes as single paths and develop a specialized branch-price-and-cut algorithm. Computational experiments demonstrate that the proposed exact algorithm outperforms direct commercial solver applications on large-scale instances."
resource: "https://arxiv.org/abs/2610.15016"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
  - "fleet-scheduling"
timestamp: "2026-10-23T09:45:09Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Fan Pu"
  - literal: "Sivakumar Rathinam"
  - literal: "Yunlong Zhang"
  - literal: "Xiaopeng Li"
  - literal: "Xiubin Wang"
  - literal: "Yang Zhou"
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
processed_at: "2026-10-23T09:45:09Z"
created_at: "2026-10-23T09:45:09Z"
---

# An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones

**Authors**: Fan Pu, Sivakumar Rathinam, Yunlong Zhang, Xiaopeng Li, Xiubin Wang, Yang Zhou, Yang Zhou
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15016](https://arxiv.org/abs/2610.15016)

## Summary

This paper studies the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, where trucks act as mobile hubs carrying drone fleets to service sparse rural demands. The authors formulate a mixed-integer quadratic programming model capturing delivery delays, return times, and operating costs. To solve this problem exactly, they introduce a network transformation to represent feasible routes as single paths and develop a specialized branch-price-and-cut algorithm. Computational experiments demonstrate that the proposed exact algorithm outperforms direct commercial solver applications on large-scale instances.

## Key Contributions

- Formulates a mixed-integer quadratic programming model for the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, accounting for customer delivery delays, truck return times, and operating costs.
- Develops a network transformation enabling each feasible route to be represented as a single path.
- Proposes a tailored branch-price-and-cut algorithm with custom pricing, cutting, branching, and parallel-computing procedures that proves optimality for most large-scale instances.

## Limitations

Computational time limits and scalability constraints common to exact branch-price-and-cut frameworks on extremely large instances.

## Archivist Review

Applied strict selectivity filters for operational research and vehicle routing topics. The branch-price-and-cut algorithm and future work directions are too application-specific and paper-local to justify permanent standalone vault notes.

### Rejected Candidates
- [concept] Branch-Price-and-Cut Algorithm for Truck-as-Hub VRPD (`branch-price-and-cut-algorithm-truck-hub-vrpd`) - paper_local: Paper-local exact solution methodology tied specifically to the truck-as-hub vehicle routing problem with drones rather than a broadly reusable general ML/optimization pattern.
- [open_question] Integrated Pad Location and Routing (`integrated-pad-location-and-routing-optimization`) - low_impact: Standard application-specific future work extension rather than a fundamental theoretical bottleneck.
- [open_question] Stochastic and Heterogeneous Drone Routing (`stochastic-heterogeneous-drone-routing`) - low_impact: Standard application-specific future work extension for vehicle routing models.

## Links

- [Abstract](https://arxiv.org/abs/2610.15016)
- [PDF](https://arxiv.org/pdf/2610.15016)

