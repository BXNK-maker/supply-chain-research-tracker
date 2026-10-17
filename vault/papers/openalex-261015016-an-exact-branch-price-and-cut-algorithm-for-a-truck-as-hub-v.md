---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones"
description: "This paper studies the Truck-as-Hub Vehicle Routing Problem with Drones for rural last-mile logistics, where trucks serve as mobile synchronization hubs for drone fleets. The authors formulate a mixed-integer quadratic programming model and develop an exact branch-price-and-cut algorithm featuring network transformations and tailored pricing, cutting, and branching procedures. Computational results show that the proposed algorithm efficiently proves optimality or achieves small gaps under 4% for large-scale instances, significantly outperforming direct commercial solver applications."
resource: "https://arxiv.org/abs/2610.15016"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-17T08:58:45Z"

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
processed_at: "2026-10-17T08:58:45Z"
created_at: "2026-10-17T08:58:45Z"
---

# An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones

**Authors**: Fan Pu, Sivakumar Rathinam, Yunlong Zhang, Xiaopeng Li, Xiubin Wang, Yang Zhou, Fan Pu, Sivakumar Rathinam, Yunlong Zhang, Xiaopeng Li, Xiubin Wang, Yang Zhou
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15016](https://arxiv.org/abs/2610.15016)

## Summary

This paper studies the Truck-as-Hub Vehicle Routing Problem with Drones for rural last-mile logistics, where trucks serve as mobile synchronization hubs for drone fleets. The authors formulate a mixed-integer quadratic programming model and develop an exact branch-price-and-cut algorithm featuring network transformations and tailored pricing, cutting, and branching procedures. Computational results show that the proposed algorithm efficiently proves optimality or achieves small gaps under 4% for large-scale instances, significantly outperforming direct commercial solver applications.

## Key Contributions

- Formulates a mixed-integer quadratic programming model for the Truck-as-Hub Vehicle Routing Problem with Drones that captures customer delivery delays, truck return times, and operating costs.
- Develops an exact branch-price-and-cut algorithm incorporating network transformation, tailored pricing, cutting, branching, and parallel-computing procedures.
- Demonstrates through computational experiments that the proposed exact algorithm proves optimality for most large-scale test cases with remaining gaps under 4%, outperforming commercial solvers like Gurobi.

## Limitations

The exact algorithm faces scalability limits on extremely large instances, resulting in small optimality gaps of up to 4% rather than full optimality proofs for the hardest remaining cases.

## Archivist Review

Evaluated the candidates against vault standards. The problem formulation and its future extensions belong to operations research and vehicle routing rather than general machine learning concepts, so both candidates were rejected to maintain vault focus and quality.

### Rejected Candidates
- [concept] Truck-as-Hub Vehicle Routing Problem with Drones (`truck-as-hub-vehicle-routing-problem-with-drones`) - paper_local: This is a specialized operations research problem instance combining trucks and drones rather than a reusable ML method, architectural pattern, or foundational concept.
- [open_question] Integrated Network Design and Stochastic Heterogeneous Drone Routing (`integrated-network-design-stochastic-heterogeneous-drone-routing`) - low_impact: This represents a specialized operational extension for vehicle routing rather than a fundamental open bottleneck in machine learning generalization, optimization, or theory.

## Links

- [Abstract](https://arxiv.org/abs/2610.15016)
- [PDF](https://arxiv.org/pdf/2610.15016)

