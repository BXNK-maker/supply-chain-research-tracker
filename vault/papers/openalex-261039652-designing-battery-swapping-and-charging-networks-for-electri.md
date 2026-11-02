---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Designing battery swapping and charging networks for electric freight transport under demand uncertainty"
description: "Long-haul freight electrification requires balancing rapid energy replenishment near freight flows with localized electrical grid capacity constraints. To address this, the authors introduce a 'Swap-Locally, Charge-Centrally' infrastructure architecture within a relay freight network, formulated as a multi-period, two-stage stochastic location-inventory-fleet model. They establish theoretical properties including the submodularity of the battery value function and affinity of fleet recourse, and develop an advanced Lovász-cut Benders decomposition method. Tested on a seven-state southeastern U.S. freight network, the proposed decomposition reaches optimality gaps below 0.01% in under four minutes, outperforming strengthened extensive formulations."
resource: "https://arxiv.org/abs/2610.39652"
tags:
  - "decarbonization"
  - "demand-forecasting"
  - "combinatorial-optimization"
  - "stochastic-demands"
timestamp: "2026-11-02T13:06:12Z"

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
    description: "A freight network infrastructure design separating local battery swapping from centralized grid-suitable charging hubs."
datasets:
  []
open_questions:
  - name: "multistage-stochastic-electric-freight-network-design"
    description: "Future research should explore multistage investment frameworks, joint sizing of inventory and transit buffers for remote links, integer batch quantities, corridor-level adoption heterogeneity, endogenous route choices, and enhanced stochastic chance-constrained formulations to optimize long-haul electric freight networks under more comprehensive operating conditions."
skill: "GeneralMLSkill"
processed_at: "2026-11-02T13:06:12Z"
created_at: "2026-11-02T13:06:12Z"
---

# Designing battery swapping and charging networks for electric freight transport under demand uncertainty

**Authors**: Yujia Xu, Walid Klibi, Benoit Montreuil
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.39652](https://arxiv.org/abs/2610.39652)

## Summary

Long-haul freight electrification requires balancing rapid energy replenishment near freight flows with localized electrical grid capacity constraints. To address this, the authors introduce a 'Swap-Locally, Charge-Centrally' infrastructure architecture within a relay freight network, formulated as a multi-period, two-stage stochastic location-inventory-fleet model. They establish theoretical properties including the submodularity of the battery value function and affinity of fleet recourse, and develop an advanced Lovász-cut Benders decomposition method. Tested on a seven-state southeastern U.S. freight network, the proposed decomposition reaches optimality gaps below 0.01% in under four minutes, outperforming strengthened extensive formulations.

## Key Contributions

- Proposed the 'Swap-Locally, Charge-Centrally' architecture to decouple local battery swapping from centralized, grid-suitable charging hubs in long-haul electric freight networks.
- Developed a multi-period, two-stage stochastic location-inventory-fleet model coordinating station deployment, inventory, and grid-bounded charging capacity under demand uncertainty.
- Proved the submodularity of the battery value function via a scalar partial-minimization proof and showed that fleet recourse is affine in binary swap-station decisions.
- Developed a Lovász-cut Benders decomposition featuring hub-period block cuts and a convex battery oracle with analytic gradients and memoization, achieving optimality gaps below 0.01% within four minutes on large southeastern U.S. freight instances.

## Limitations

None explicitly stated in the abstract.

## Open Questions & Future Work

- [[multistage-stochastic-electric-freight-network-design]]

## Key Concepts

- [[swap-locally-charge-centrally-architecture]]: A freight network infrastructure design separating local battery swapping from centralized grid-suitable charging hubs.

## Archivist Review

The core infrastructure concept was approved because it is already present in the vault and represents a distinctive, reusable paradigm in heavy-duty electric vehicle network planning. The open question was preserved as it addresses long-term research directions in multistage stochastic infrastructure design.

### Approved Concepts
- Swap-Locally, Charge-Centrally Architecture: It forms the core infrastructure paradigm introduced and modeled for long-haul electric freight transport under grid capacity constraints.

### Approved Open Questions
- Multistage Stochastic Electric Freight Networks: Extending stochastic energy infrastructure network models to handle multi-stage dynamic investments and tighter buffer/inventory coupling is critical for scaling long-haul freight electrification under real-world operational complexities.

## Links

- [Abstract](https://arxiv.org/abs/2610.39652)
- [PDF](https://arxiv.org/pdf/2610.39652)

