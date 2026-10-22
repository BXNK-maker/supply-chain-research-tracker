---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones"
description: "This paper studies a Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, formulating it as a mixed-integer quadratic programming model to optimize customer delivery delays, truck return times, and operating costs. To solve the problem exactly, the authors propose a branch-price-and-cut algorithm incorporating tailored pricing, cutting, branching, and parallel-computing procedures on a transformed network. Computational experiments show that the algorithm successfully proves optimality for most large-scale instances and maintains small optimality gaps on the rest, significantly outperforming direct exact solvers."
resource: "https://arxiv.org/abs/2610.15016"
tags:
  - "vehicle-routing-problem"
timestamp: "2026-10-22T09:48:58Z"

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
processed_at: "2026-10-22T09:48:58Z"
created_at: "2026-10-22T09:48:58Z"
---

# An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones

**Authors**: Fan Pu, Sivakumar Rathinam, Yunlong Zhang, Xiaopeng Li, Xiubin Wang, Yang Zhou, Yang Zhou
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15016](https://arxiv.org/abs/2610.15016)

## Summary

This paper studies a Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, formulating it as a mixed-integer quadratic programming model to optimize customer delivery delays, truck return times, and operating costs. To solve the problem exactly, the authors propose a branch-price-and-cut algorithm incorporating tailored pricing, cutting, branching, and parallel-computing procedures on a transformed network. Computational experiments show that the algorithm successfully proves optimality for most large-scale instances and maintains small optimality gaps on the rest, significantly outperforming direct exact solvers.

## Key Contributions

- Formulates a mixed-integer quadratic programming model for a Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas that jointly accounts for delivery delays, truck return times, and operating costs.
- Develops an exact branch-price-and-cut algorithm featuring tailored pricing, cutting, branching, and parallel-computing procedures based on a network transformation representing feasible routes as single paths.
- Demonstrates through computational experiments that the exact algorithm proves optimality for most large-scale test cases and achieves gaps under 4% for remaining instances, outperforming direct commercial solver applications.

## Archivist Review

Applied strict selection standards: the proposed concepts and open questions are specific to operations research and vehicle routing problems rather than machine learning algorithms, architectures, or core methodology. Consequently, all candidates were rejected to maintain the vault's focus on general ML innovations.

### Rejected Candidates
- [concept] Truck-as-Hub Vehicle Routing Problem with Drones (`truck-as-hub-vrp-drones`) - not_reusable: This is a specific application variant of vehicle routing rather than a general methodological or architectural machine learning concept.
- [open_question] Joint Pad Location and Routing (`joint-pad-location-routing-optimization`) - low_impact: This is a domain-specific operations research extension rather than a broad foundational bottleneck in machine learning or AI.
- [open_question] Stochastic and Heterogeneous Drone Fleets (`stochastic-heterogeneous-drone-routing`) - low_impact: This is a standard future work suggestion for stochastic vehicle routing extensions rather than a vault-worthy conceptual bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.15016)
- [PDF](https://arxiv.org/pdf/2610.15016)

