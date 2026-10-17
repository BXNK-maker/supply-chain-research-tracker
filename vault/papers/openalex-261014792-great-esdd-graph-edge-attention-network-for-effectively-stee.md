---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions"
description: "The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for online same-day delivery that combines a neural CVRP solver based on the Graph-Edge-Attention-Network (GREAT) with Thompson sampling for customer preference learning. By rapidly evaluating candidate routing problems in parallel batches, the framework estimates delivery cost increases to set dynamic prices that steer customers toward out-of-home delivery options. Simulations show that the approach increases profit by approximately 11% over traditional routing solvers while successfully learning customer preferences."
resource: "https://arxiv.org/abs/2610.14792"
tags:
  - "choice-modeling"
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "dynamic-pricing"
  - "neural-routing-solver"
timestamp: "2026-10-17T09:00:04Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Attila Lischka"
  - literal: "Ze Zhou"
  - literal: "Xuegang Ban"
  - literal: "Balaźs Kulcsár"
  - literal: "Xuegang"
issued:
  date-parts:
    - [2026, 10, 10]

# Domain-specific custom fields
paper_id: "2610.14792"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "graph-edge-attention-network"
    description: "A neural solver based on Graph-Edge-Attention-Network (GREAT) designed to solve the capacitated vehicle routing problem with varying instance sizes and starting conditions."
datasets:
  []
open_questions:
  - name: "adaptive-rectifiers-for-dynamic-routing"
    description: "Investigate whether adaptive or online-learned rectification parameters (such as time-varying or dynamically adjusted scaling factors) can replace static rectifiers to improve the accuracy of marginal routing cost estimates over the operating horizon."
skill: "GeneralMLSkill"
processed_at: "2026-10-17T09:00:04Z"
created_at: "2026-10-17T09:00:04Z"
---

# GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions

**Authors**: Attila Lischka, Ze Zhou, Xuegang Ban, Balaźs Kulcsár, Xuegang
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.14792](https://arxiv.org/abs/2610.14792)

## Summary

The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for online same-day delivery that combines a neural CVRP solver based on the Graph-Edge-Attention-Network (GREAT) with Thompson sampling for customer preference learning. By rapidly evaluating candidate routing problems in parallel batches, the framework estimates delivery cost increases to set dynamic prices that steer customers toward out-of-home delivery options. Simulations show that the approach increases profit by approximately 11% over traditional routing solvers while successfully learning customer preferences.

## Key Contributions

- Developed GREAT-ESDD, a dynamic pricing-and-routing framework that integrates a neural CVRP solver with Thompson sampling to steer customers toward out-of-home delivery options.
- Built a neural solver using the Graph-Edge-Attention-Network (GREAT) capable of processing multiple CVRP instances in parallel batches and rapidly reoptimizing partially executed routes.
- Demonstrated an 11% profit increase compared to traditional routing solvers under similar pricing decision time budgets, alongside successful online learning of customer preferences.

## Limitations

Evaluated in simulated operations; potential generalization limits to complex real-world traffic and unmodeled customer behavior variations remain to be tested.

## Open Questions & Future Work

- [[adaptive-rectifiers-for-dynamic-routing]]

## Key Concepts

- [[graph-edge-attention-network]]: A neural solver based on Graph-Edge-Attention-Network (GREAT) designed to solve the capacitated vehicle routing problem with varying instance sizes and starting conditions.

## Archivist Review

Approved the Graph-Edge-Attention-Network concept as a reusable neural routing architecture for vehicle routing problems, and the adaptive rectifiers open question addressing learning scaling factors in dynamic routing pipelines. Both pass the high-bar novelty and reusability standards of the knowledge vault.

### Approved Concepts
- Graph-Edge-Attention-Network: Serves as the core neural solver for the capacitated vehicle routing problem, enabling real-time reoptimization of partially executed routes and parallel batch processing of candidate routing problems.

### Approved Open Questions
- Adaptive Rectifiers for Dynamic Routing: A dynamic or learned rectifier bridges the gap between myopic routing cost approximations and global anticipatory optimization, potentially improving decision quality in dynamic pricing-and-routing pipelines.

## Links

- [Abstract](https://arxiv.org/abs/2610.14792)
- [PDF](https://arxiv.org/pdf/2610.14792)

