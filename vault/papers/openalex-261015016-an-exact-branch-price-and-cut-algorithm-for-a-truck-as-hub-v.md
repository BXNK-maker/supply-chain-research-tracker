---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones"
description: "This paper investigates the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, where trucks act as mobile hubs launching and retrieving multiple drones simultaneously at predesignated synchronization pads. The authors formulate a mixed-integer quadratic programming model to optimize customer delivery delays, truck return times, and operating costs. To solve this problem exactly, they develop a custom branch-price-and-cut algorithm featuring tailored pricing, cutting, branching, and parallel-computing procedures. Computational results demonstrate that the proposed exact algorithm significantly outperforms direct commercial solver formulations on large-scale test instances."
resource: "https://arxiv.org/abs/2610.15016"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
  - "fleet-scheduling"
timestamp: "2026-10-18T09:17:32Z"

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
  - name: "integrated-network-design-stochastic-heterogeneous-drone-routing"
    description: "Jointly optimizing synchronization-pad locations and truck-drone routes to extend the framework toward integrated network design, alongside incorporating uncertain travel times and heterogeneous drone fleets to improve applicability to realistic rural delivery operations."
skill: "GeneralMLSkill"
processed_at: "2026-10-18T09:17:32Z"
created_at: "2026-10-18T09:17:32Z"
---

# An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones

**Authors**: Fan Pu, Sivakumar Rathinam, Yunlong Zhang, Xiaopeng Li, Xiubin Wang, Yang Zhou, Yang Zhou
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15016](https://arxiv.org/abs/2610.15016)

## Summary

This paper investigates the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, where trucks act as mobile hubs launching and retrieving multiple drones simultaneously at predesignated synchronization pads. The authors formulate a mixed-integer quadratic programming model to optimize customer delivery delays, truck return times, and operating costs. To solve this problem exactly, they develop a custom branch-price-and-cut algorithm featuring tailored pricing, cutting, branching, and parallel-computing procedures. Computational results demonstrate that the proposed exact algorithm significantly outperforms direct commercial solver formulations on large-scale test instances.

## Key Contributions

- Formulated a mixed-integer quadratic programming model for the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, accounting for customer delivery delays, truck return times, and operating costs.
- Developed an exact branch-price-and-cut algorithm incorporating tailored pricing, cutting, branching, and parallel-computing procedures.
- Demonstrated through computational experiments that the algorithm proves optimality for most large-scale test cases and maintains gaps under 4% for remaining instances, outperforming direct commercial solver applications.

## Limitations

Future work may explore more complex stochastic environments or larger fleets to further scale rural drone delivery models.

## Open Questions & Future Work

- [[integrated-network-design-stochastic-heterogeneous-drone-routing]]

## Archivist Review

Applied strict standards to ensure only reusable core contributions are added. No concepts were proposed or warranted since the paper focuses on an operations research exact solver for a specific vehicle routing variant. One open question addressing stochastic drone routing and integrated network design is approved as a valid research direction.

### Approved Open Questions

### Rejected Candidates
- [open_question] Integrated Network Design and Stochastic Drone Routing (`integrated-network-design-stochastic-heterogeneous-drone-routing`) - other: Approved as a valid open question.

## Links

- [Abstract](https://arxiv.org/abs/2610.15016)
- [PDF](https://arxiv.org/pdf/2610.15016)

