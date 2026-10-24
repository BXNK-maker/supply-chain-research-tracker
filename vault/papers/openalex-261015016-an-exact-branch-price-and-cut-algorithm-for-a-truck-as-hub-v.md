---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones"
description: "This paper studies the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, where trucks act as mobile hubs carrying drone fleets that launch and retrieve from predesignated passive synchronization pads. The authors formulate a mixed-integer quadratic programming model and develop an exact branch-price-and-cut algorithm featuring tailored pricing, cutting, branching, and parallel-computing procedures. Computational experiments demonstrate that the proposed algorithm proves optimality for most large-scale test cases with small remaining gaps, significantly outperforming standard commercial solvers applied to the compact formulation."
resource: "https://arxiv.org/abs/2610.15016"
tags:
  - "vehicle-routing-problem"
timestamp: "2026-10-24T09:15:54Z"

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
processed_at: "2026-10-24T09:15:54Z"
created_at: "2026-10-24T09:15:54Z"
---

# An Exact Branch-Price-and-Cut Algorithm for a Truck-as-Hub Vehicle Routing Problem with Drones

**Authors**: Fan Pu, Sivakumar Rathinam, Yunlong Zhang, Xiaopeng Li, Xiubin Wang, Yang Zhou
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15016](https://arxiv.org/abs/2610.15016)

## Summary

This paper studies the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, where trucks act as mobile hubs carrying drone fleets that launch and retrieve from predesignated passive synchronization pads. The authors formulate a mixed-integer quadratic programming model and develop an exact branch-price-and-cut algorithm featuring tailored pricing, cutting, branching, and parallel-computing procedures. Computational experiments demonstrate that the proposed algorithm proves optimality for most large-scale test cases with small remaining gaps, significantly outperforming standard commercial solvers applied to the compact formulation.

## Key Contributions

- Formulated a mixed-integer quadratic programming model for the Truck-as-Hub Vehicle Routing Problem with Drones in Rural Areas, jointly accounting for customer delivery delays, truck return times, and operating costs.
- Developed a network transformation method representing each feasible truck-drone route as a single path.
- Designed an exact branch-price-and-cut algorithm with tailored pricing, cutting, branching, and parallel-computing procedures that outperforms commercial solvers on large-scale instances.

## Limitations

Evaluated on simulated or structured test cases; performance depends on the density of passive synchronization pads and drone operating parameter ranges.

## Archivist Review

Applied strict standards for the vault. No concepts were provided, and the sole open question represents broad future facility location and uncertainty extensions rather than a standalone fundamental research bottleneck, so it was rejected.

### Rejected Candidates
- [open_question] Integrated Pad Location and Routing (`integrated-pad-location-routing-drone-fleet`) - not_novel: The open question is broad future work proposing facility location integration and uncertainty extensions rather than a specific, tightly scoped algorithmic or mathematical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.15016)
- [PDF](https://arxiv.org/pdf/2610.15016)

