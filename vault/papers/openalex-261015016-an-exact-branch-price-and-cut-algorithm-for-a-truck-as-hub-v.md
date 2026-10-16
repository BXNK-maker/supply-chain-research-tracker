---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones"
description: "This paper studies the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, where trucks act as mobile synchronization hubs for drone fleets. The authors formulate a mixed-integer quadratic programming model and develop an exact branch-price-and-cut algorithm incorporating network transformation, tailored pricing, cutting, branching, and parallel-computing procedures. Computational experiments show that the proposed exact algorithm significantly outperforms direct solvers like Gurobi on large-scale instances, proving optimality for most cases and achieving small optimality gaps on the rest."
resource: "https://arxiv.org/abs/2610.15016"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-10-16T09:29:01Z"

# CSL-compatible fields (Retained as custom)
author:
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
processed_at: "2026-10-16T09:29:01Z"
created_at: "2026-10-16T09:29:01Z"
---

# An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones

**Authors**: Fan Pu, Sivakumar Rathinam, Yunlong Zhang, Xiaopeng Li, Xiubin Wang, Yang Zhou
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15016](https://arxiv.org/abs/2610.15016)

## Summary

This paper studies the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, where trucks act as mobile synchronization hubs for drone fleets. The authors formulate a mixed-integer quadratic programming model and develop an exact branch-price-and-cut algorithm incorporating network transformation, tailored pricing, cutting, branching, and parallel-computing procedures. Computational experiments show that the proposed exact algorithm significantly outperforms direct solvers like Gurobi on large-scale instances, proving optimality for most cases and achieving small optimality gaps on the rest.

## Key Contributions

- Formulates a mixed-integer quadratic programming model for the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, accounting for customer delivery delays, truck return times, and operating costs.
- Develops an exact branch-price-and-cut algorithm incorporating network transformation, tailored pricing, cutting, branching, and parallel-computing procedures.
- Demonstrates through computational experiments that the proposed algorithm proves optimality for most large-scale test cases and achieves gaps under 4% for remaining instances, outperforming standard Gurobi compact formulation solvers.

## Limitations

The approach assumes deterministic travel times and operating conditions; future work could extend the model to handle stochastic travel times and weather uncertainties for drones.

## Archivist Review

Applied strict filtering criteria to reject the domain-specific problem variant as a standalone vault concept, ensuring the vault retains only generalizable ML methods, architectural patterns, and broad research bottlenecks. No datasets or open questions were proposed or approved.

### Rejected Candidates
- [concept] Truck-as-Hub Vehicle Routing Problem with Drones (`truck-as-hub-vehicle-routing-problem-with-drones`) - paper_local: This represents a specific application-domain problem variant rather than a foundational ML method, model architecture, or reusable algorithmic concept.

## Links

- [Abstract](https://arxiv.org/abs/2610.15016)
- [PDF](https://arxiv.org/pdf/2610.15016)

