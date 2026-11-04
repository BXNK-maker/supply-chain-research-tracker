---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Designing battery swapping and charging networks for electric freight transport under demand uncertainty"
description: "This paper investigates the electrification of long-haul truck transport using a 'Swap-Locally, Charge-Centrally' architecture that decouples battery swapping from grid-constrained charging locations. The authors formulate a multi-period, two-stage stochastic location-inventory-fleet model to coordinate station deployment and inventory management under demand uncertainty. By proving submodularity of the battery value function and affinity of fleet recourse, they develop a Lovász-cut Benders decomposition with analytic gradients. Empirical evaluation on a seven-state U.S. southeastern freight network demonstrates that the approach solves large-scale instances to high precision in minutes, outperforming standard extensive formulations and avoiding capacity shortfalls."
resource: "https://arxiv.org/abs/2610.39652"
tags:
  - "decarbonization"
  - "combinatorial-optimization"
  - "stochastic-demands"
  - "vehicle-routing-problem"
timestamp: "2026-11-04T12:46:31Z"

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
    description: "A network design framework that spatially decouples battery swapping near freight flows from grid-suitable central charging hubs."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-04T12:46:31Z"
created_at: "2026-11-04T12:46:31Z"
---

# Designing battery swapping and charging networks for electric freight transport under demand uncertainty

**Authors**: Yujia Xu, Walid Klibi, Benoit Montreuil
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.39652](https://arxiv.org/abs/2610.39652)

## Summary

This paper investigates the electrification of long-haul truck transport using a 'Swap-Locally, Charge-Centrally' architecture that decouples battery swapping from grid-constrained charging locations. The authors formulate a multi-period, two-stage stochastic location-inventory-fleet model to coordinate station deployment and inventory management under demand uncertainty. By proving submodularity of the battery value function and affinity of fleet recourse, they develop a Lovász-cut Benders decomposition with analytic gradients. Empirical evaluation on a seven-state U.S. southeastern freight network demonstrates that the approach solves large-scale instances to high precision in minutes, outperforming standard extensive formulations and avoiding capacity shortfalls.

## Key Contributions

- Proposed the 'Swap-Locally, Charge-Centrally' architecture for electric freight transport, decoupling local battery swapping from grid-suitable central charging hubs.
- Developed a multi-period, two-stage stochastic location-inventory-fleet model integrating station deployment, inventory, and grid-bounded charging capacity under demand uncertainty.
- Proved that the battery value function is submodular and that fleet recourse is affine in binary swap-station decisions, enabling an efficient Lovász-cut Benders decomposition.
- Demonstrated on a seven-state southeastern U.S. freight network that the proposed method reaches optimality gaps below 0.01% in minutes, outperforming strengthened extensive formulations.

## Limitations

The model focuses on specific regional freight corridors and relies on deterministic or scenario-based approximations of future grid capacity and demand distributions.

## Key Concepts

- [[swap-locally-charge-centrally-architecture]]: A network design framework that spatially decouples battery swapping near freight flows from grid-suitable central charging hubs.

## Archivist Review

Approved the core 'Swap-Locally, Charge-Centrally Architecture' concept as a highly reusable and distinct domain paradigm for freight electrification. Rejected the open question as a routine call for multi-stage extension without a sharp technical bottleneck.

### Approved Concepts
- Swap-Locally, Charge-Centrally Architecture: Central paradigm introduced for decoupling battery swapping locations from grid-constrained charging hubs in electric freight transport.

### Rejected Candidates
- [concept] Lovász-cut Benders Decomposition (`lovasz-cut-benders-decomposition`) - subcomponent_of_broader_mechanism: Specialized algorithmic solution technique combining Benders decomposition with Lovász extension cuts, better classified under broader optimization methodology.
- [open_question] Multistage Infrastructure Investment under Uncertainty (`multistage-infrastructure-investment`) - low_impact: Standard formulation extension request lacking specific unresolved technical bottlenecks beyond general multi-stage stochastic programming.

## Links

- [Abstract](https://arxiv.org/abs/2610.39652)
- [PDF](https://arxiv.org/pdf/2610.39652)

