---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones"
description: "This paper studies a Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, where trucks act as mobile hubs to launch and retrieve multiple drones simultaneously at predesignated synchronization pads. To solve this routing problem exactly, the authors formulate a mixed-integer quadratic programming model and develop a custom branch-price-and-cut algorithm featuring tailored pricing, cutting, branching, and parallel-computing procedures. Computational experiments demonstrate that the proposed algorithm successfully proves optimality for most large-scale test instances and maintains gaps below 4% on the rest, vastly outperforming direct commercial solvers."
resource: "https://arxiv.org/abs/2610.15016"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
  - "approximation-algorithms"
timestamp: "2026-10-21T09:47:47Z"

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
processed_at: "2026-10-21T09:47:47Z"
created_at: "2026-10-21T09:47:47Z"
---

# An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones

**Authors**: Fan Pu, Sivakumar Rathinam, Yunlong Zhang, Xiaopeng Li, Xiubin Wang, Yang Zhou, Yang Zhou
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15016](https://arxiv.org/abs/2610.15016)

## Summary

This paper studies a Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, where trucks act as mobile hubs to launch and retrieve multiple drones simultaneously at predesignated synchronization pads. To solve this routing problem exactly, the authors formulate a mixed-integer quadratic programming model and develop a custom branch-price-and-cut algorithm featuring tailored pricing, cutting, branching, and parallel-computing procedures. Computational experiments demonstrate that the proposed algorithm successfully proves optimality for most large-scale test instances and maintains gaps below 4% on the rest, vastly outperforming direct commercial solvers.

## Key Contributions

- Formulated a mixed-integer quadratic programming model for the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas that jointly accounts for customer delivery delays, truck return times, and operating costs.
- Developed an exact branch-price-and-cut algorithm with tailored pricing, cutting, branching, and parallel-computing procedures using a network transformation.
- Proved optimality for most large-scale test cases and achieved optimality gaps of no more than 4% for the remaining cases, significantly outperforming commercial solvers on the compact formulation.

## Archivist Review

No concepts or open questions from this operations research paper on truck-drone routing met the high standard for general ML/AI knowledge vault inclusion. The open question is specific to combinatorial vehicle routing and facility location.

### Rejected Candidates
- [open_question] Integrated Network Design and Uncertainty in Truck-Drone Routing (`integrated-network-design-and-uncertainty-in-truck-drone-routing`) - low_impact: This open question is domain-specific to operations research and vehicle routing problems rather than general machine learning methodology.

## Links

- [Abstract](https://arxiv.org/abs/2610.15016)
- [PDF](https://arxiv.org/pdf/2610.15016)

