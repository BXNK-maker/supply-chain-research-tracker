---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Designing battery swapping and charging networks for electric freight transport under demand uncertainty"
description: "This paper studies the electrification of long-haul freight transport using a 'Swap-Locally, Charge-Centrally' network architecture that separates local battery swapping from grid-constrained charging hubs. The authors formulate a multi-period, two-stage stochastic location-inventory-fleet model to co-optimize station deployment, battery stocks, and fleet requirements under demand uncertainty. To solve this problem efficiently, they develop a Lovász-cut Benders decomposition supported by structural submodularity results and a convex battery oracle. Evaluated on a seven-state southeastern U.S. freight network, the proposed approach achieves high solution accuracy within minutes, significantly outperforming standard extensive formulations."
resource: "https://arxiv.org/abs/2610.39652"
tags:
  - "decarbonization"
  - "demand-forecasting"
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-11-01T11:37:52Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Yujia Xu"
  - literal: "Walid Klibi"
  - literal: "Benoit Montreuil"
issued:
  date-parts:
    - [2026, 10, 29]

# Domain-specific custom fields
paper_id: "2610.39652"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "swap-locally-charge-centrally-architecture"
    description: "A network design architecture for electric freight transport that decouples local battery swapping from centralized, grid-constrained charging locations."
datasets:
  []
open_questions:
  - name: "multistage-stochastic-electric-freight-network-design"
    description: "Future work needs to extend current stochastic infrastructure design models to explicitly incorporate multistage investment frameworks, jointly optimize the multiple inventory buffers on remote links rather than relying on decoupled approximations, account for integer batch quantities without continuous relaxations, incorporate corridor-level adoption heterogeneity, model endogenous route choices rather than fixed relay paths, and support multiple charging suppliers per swapping hub under more advanced shortfall-recourse or chance-constrained capacity models."
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:37:52Z"
created_at: "2026-11-01T11:37:52Z"
---

# Designing battery swapping and charging networks for electric freight transport under demand uncertainty

**Authors**: Yujia Xu, Walid Klibi, Benoit Montreuil
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.39652](https://arxiv.org/abs/2610.39652)

## Summary

This paper studies the electrification of long-haul freight transport using a 'Swap-Locally, Charge-Centrally' network architecture that separates local battery swapping from grid-constrained charging hubs. The authors formulate a multi-period, two-stage stochastic location-inventory-fleet model to co-optimize station deployment, battery stocks, and fleet requirements under demand uncertainty. To solve this problem efficiently, they develop a Lovász-cut Benders decomposition supported by structural submodularity results and a convex battery oracle. Evaluated on a seven-state southeastern U.S. freight network, the proposed approach achieves high solution accuracy within minutes, significantly outperforming standard extensive formulations.

## Key Contributions

- Proposed a 'Swap-Locally, Charge-Centrally' architecture and a multi-period, two-stage stochastic location-inventory-fleet model for long-haul truck electrification under demand uncertainty.
- Established mathematical properties including a scalar partial-minimization proof of battery value function submodularity and affinity of fleet recourse in binary swap-station decisions.
- Developed a Lovász-cut Benders decomposition featuring hub-period block cuts and a convex battery oracle with analytic gradients and memoization.
- Demonstrated on a seven-state southeastern U.S. freight network that the proposed method achieves optimality gaps below 0.01% in under four minutes, outperforming a strengthened extensive formulation.

## Open Questions & Future Work

- [[multistage-stochastic-electric-freight-network-design]]

## Key Concepts

- [[swap-locally-charge-centrally-architecture]]: A network design architecture for electric freight transport that decouples local battery swapping from centralized, grid-constrained charging locations.

## Archivist Review

Approved the core Swap-Locally, Charge-Centrally Architecture concept as a reusable, domain-specific network design paradigm for electric freight transport under grid constraints. Approved the multistage stochastic electric freight network design open question as it highlights structural modeling gaps in multi-echelon inventory and infrastructure optimization under uncertainty.

### Approved Concepts
- Swap-Locally, Charge-Centrally Architecture: Defines the core structural methodology for decoupling local energy replenishment from centralized grid-suitable charging hubs in electric freight transport.

### Approved Open Questions
- Multistage Electric Freight Network Design: Identifying these modeling extensions is crucial for scaling electric freight network design to handle real-world operational complexities, dynamic decision-making under uncertainty, and precise multi-echelon inventory-fleet trade-offs.

## Links

- [Abstract](https://arxiv.org/abs/2610.39652)
- [PDF](https://arxiv.org/pdf/2610.39652)

