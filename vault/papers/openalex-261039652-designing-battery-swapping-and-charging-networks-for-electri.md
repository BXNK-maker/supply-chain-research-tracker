---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Designing battery swapping and charging networks for electric freight transport under demand uncertainty"
description: "This paper investigates long-haul truck electrification using a 'Swap-Locally, Charge-Centrally' architecture within a relay freight network to bypass local grid capacity bottlenecks. The authors formulate a multi-period, two-stage stochastic location-inventory-fleet model to coordinate station deployment and battery replenishment under demand uncertainty. To solve this efficiently, they prove the submodularity of the battery value function and introduce a Lovász-cut Benders decomposition paired with a convex battery oracle. Evaluations on a regional U.S. freight network show that the method achieves near-exact solutions within minutes, outperforming standard extensive formulations while avoiding the shortfalls of mean-value planning."
resource: "https://arxiv.org/abs/2610.39652"
tags:
  - "decarbonization"
  - "fleet-scheduling"
  - "stochastic-demands"
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-11-03T12:37:27Z"

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
  - name: "lovasz-cut-benders-decomposition"
    description: "A specialized Benders decomposition method leveraging Lovász extension cuts and analytic gradient oracles to solve large-scale stochastic network design problems."
datasets:
  []
open_questions:
  - name: "multistage-stochastic-network-design-ev-swapping"
    description: "Future work involves extending the current two-stage stochastic model to a multistage investment framework, incorporating joint sizing of both remote inventory buffers, handling integer batch quantities, modeling corridor-level adoption heterogeneity, enabling endogenous route choice, and introducing shortfall-recourse or chance-constrained capacity models. Additionally, extensions that change served battery demand or charging durations require re-establishing the validity of the submodular cut relaxations."
skill: "GeneralMLSkill"
processed_at: "2026-11-03T12:37:27Z"
created_at: "2026-11-03T12:37:27Z"
---

# Designing battery swapping and charging networks for electric freight transport under demand uncertainty

**Authors**: Yujia Xu, Walid Klibi, Benoit Montreuil
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.39652](https://arxiv.org/abs/2610.39652)

## Summary

This paper investigates long-haul truck electrification using a 'Swap-Locally, Charge-Centrally' architecture within a relay freight network to bypass local grid capacity bottlenecks. The authors formulate a multi-period, two-stage stochastic location-inventory-fleet model to coordinate station deployment and battery replenishment under demand uncertainty. To solve this efficiently, they prove the submodularity of the battery value function and introduce a Lovász-cut Benders decomposition paired with a convex battery oracle. Evaluations on a regional U.S. freight network show that the method achieves near-exact solutions within minutes, outperforming standard extensive formulations while avoiding the shortfalls of mean-value planning.

## Key Contributions

- Proposed the 'Swap-Locally, Charge-Centrally' architecture to decouple local battery swapping from grid-suitable centralized charging hubs for long-haul truck electrification.
- Formulated a multi-period, two-stage stochastic location-inventory-fleet model accounting for demand uncertainty, scenario-dependent battery stocks, and competing diesel operation.
- Proved the submodularity of the battery value function and the affineness of fleet recourse, developing a Lovász-cut Benders decomposition with hub-period block cuts and a convex battery oracle.
- Demonstrated on a seven-state southeastern U.S. freight network that the proposed decomposition reaches gaps below 0.01% in under four minutes, vastly outperforming a strengthened extensive formulation.

## Limitations

None explicitly stated in the abstract, but scope is tailored to regional long-haul freight relay networks with specific grid capacity bounds.

## Open Questions & Future Work

- [[multistage-stochastic-network-design-ev-swapping]]

## Key Concepts

- [[lovasz-cut-benders-decomposition]]: A specialized Benders decomposition method leveraging Lovász extension cuts and analytic gradient oracles to solve large-scale stochastic network design problems.

## Archivist Review

Approved the Lovasz-cut Benders Decomposition concept as it is a reusable optimization technique. Rejected the Swap-Locally, Charge-Centrally Architecture concept because it is already stored in the vault. Approved the multistage stochastic network design open question as a substantial research direction.

### Approved Concepts
- Lovasz-cut Benders Decomposition: It provides the primary algorithmic innovation enabling the exact solution of large-scale stochastic location-inventory-fleet problems.

### Approved Open Questions
- Multistage Stochastic Network Design for EV Swapping: This outlines critical methodological and modeling extensions necessary to bridge the gap between static two-stage network design and real-world multi-period adaptive decision-making under uncertainty for heavy-duty freight electrification.

### Rejected Candidates
- [concept] Swap-Locally, Charge-Centrally Architecture (`swap-locally-charge-centrally-architecture`) - duplicate_existing: Already exists in the vault under the slug swap-locally-charge-centrally-architecture.

## Links

- [Abstract](https://arxiv.org/abs/2610.39652)
- [PDF](https://arxiv.org/pdf/2610.39652)

