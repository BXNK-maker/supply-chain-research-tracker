---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones"
description: "This paper studies a Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas where multiple trucks serve as mobile hubs for drone launches and retrievals at predesignated synchronization pads. The authors formulate a mixed-integer quadratic programming model and develop a custom branch-price-and-cut algorithm featuring specialized pricing, cutting, branching, and parallel-computing routines. Computational experiments demonstrate that the proposed exact algorithm significantly outperforms direct commercial solver applications on large-scale instances, providing practical insights into balancing service quality and operational costs."
resource: "https://arxiv.org/abs/2610.15016"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-10-19T10:27:45Z"

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
processed_at: "2026-10-19T10:27:45Z"
created_at: "2026-10-19T10:27:45Z"
---

# An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones

**Authors**: Fan Pu, Sivakumar Rathinam, Yunlong Zhang, Xiaopeng Li, Xiubin Wang, Yang Zhou, Fan Pu, Sivakumar Rathinam, Yunlong Zhang, Xiaopeng Li, Xiubin Wang, Yang Zhou
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15016](https://arxiv.org/abs/2610.15016)

## Summary

This paper studies a Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas where multiple trucks serve as mobile hubs for drone launches and retrievals at predesignated synchronization pads. The authors formulate a mixed-integer quadratic programming model and develop a custom branch-price-and-cut algorithm featuring specialized pricing, cutting, branching, and parallel-computing routines. Computational experiments demonstrate that the proposed exact algorithm significantly outperforms direct commercial solver applications on large-scale instances, providing practical insights into balancing service quality and operational costs.

## Key Contributions

- Formulates a mixed-integer quadratic programming model for a Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, jointly accounting for customer delivery delays, truck return times, and operating costs.
- Develops a network transformation method representing each feasible truck-drone route as a single path.
- Designs an exact branch-price-and-cut algorithm with tailored pricing, cutting, branching, and parallel-computing procedures that proves optimality for most large-scale test cases and limits optimality gaps to at most 4% for remaining cases.

## Archivist Review

No candidate concepts or open questions were submitted for review, and the paper's optimization techniques fall under specialized operational research routing methods rather than broad machine learning abstractions.

## Links

- [Abstract](https://arxiv.org/abs/2610.15016)
- [PDF](https://arxiv.org/pdf/2610.15016)

