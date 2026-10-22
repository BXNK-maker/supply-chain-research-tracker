---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions"
description: "The authors introduce GREAT-ESDD, a dynamic pricing-and-routing framework for same-day delivery that integrates home and out-of-home (OOH) delivery options. At its core, the framework uses a novel neural solver for the capacitated vehicle routing problem based on a Graph-Edge-Attention-Network (GREAT) to quickly evaluate candidate routing costs in parallel batches. These cost estimates are combined with customer preferences learned online via Thompson sampling to dynamically set delivery fees and steer customers toward cost-effective OOH options. Simulations demonstrate that the approach increases operator profit by around 11% compared to traditional routing baselines while successfully learning preferences within days."
resource: "https://arxiv.org/abs/2610.14792"
tags:
  - "dynamic-pricing"
  - "neural-routing-solver"
  - "vehicle-routing-problem"
  - "choice-modeling"
  - "time-series"
timestamp: "2026-10-22T09:49:50Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Attila Lischka"
  - literal: "Ze Zhou"
  - literal: "Xuegang"
  - literal: "Ban"
  - literal: "Balaźs Kulcsár"
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
    description: "A neural solver for the capacitated vehicle routing problem based on graph edge attention that enables fast parallel reoptimization of partially executed routes."
datasets:
  []
open_questions:
  - name: "adaptive-rectifier-dynamic-pricing"
    description: "Investigate how the cost-correction rectifier parameter (omega) can be learned dynamically or adapted as a function of time, reflecting the intuition that marginal routing cost estimates become more accurate and require less correction later in the operating day as fewer future customer arrivals remain."
skill: "GeneralMLSkill"
processed_at: "2026-10-22T09:49:50Z"
created_at: "2026-10-22T09:49:50Z"
---

# GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions

**Authors**: Attila Lischka, Ze Zhou, Xuegang, Ban, Balaźs Kulcsár
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.14792](https://arxiv.org/abs/2610.14792)

## Summary

The authors introduce GREAT-ESDD, a dynamic pricing-and-routing framework for same-day delivery that integrates home and out-of-home (OOH) delivery options. At its core, the framework uses a novel neural solver for the capacitated vehicle routing problem based on a Graph-Edge-Attention-Network (GREAT) to quickly evaluate candidate routing costs in parallel batches. These cost estimates are combined with customer preferences learned online via Thompson sampling to dynamically set delivery fees and steer customers toward cost-effective OOH options. Simulations demonstrate that the approach increases operator profit by around 11% compared to traditional routing baselines while successfully learning preferences within days.

## Key Contributions

- Developed GREAT-ESDD, a dynamic pricing-and-routing framework combining neural CVRP routing with online customer preference learning via Thompson sampling.
- Proposed a neural CVRP solver based on Graph-Edge-Attention-Network (GREAT) capable of parallel batch processing and reoptimizing partially executed routes.
- Achieved around 11% higher profit compared to traditional routing solvers under similar pricing decision time budgets in simulated operations.

## Limitations

Evaluated in simulated operations; performance relies on accurate online estimation of customer preferences via Thompson sampling.

## Open Questions & Future Work

- [[adaptive-rectifier-dynamic-pricing]]

## Key Concepts

- [[graph-edge-attention-network]]: A neural solver for the capacitated vehicle routing problem based on graph edge attention that enables fast parallel reoptimization of partially executed routes.

## Archivist Review

Applied strict selectivity: approved the core neural routing solver concept and the substantive open question regarding time-dependent adaptive pricing parameters, rejecting any routine or paper-local extensions.

### Approved Concepts
- Graph Edge Attention Network: Serves as the core neural routing solver enabling fast parallel batch processing of CVRP instances for real-time dynamic pricing and routing.

### Approved Open Questions
- Adaptive Rectifier for Dynamic Pricing: Developing adaptive, time-dependent rectifiers bridges the gap between myopic cost approximations and full anticipatory dynamic programming, enhancing real-time pricing profitability without requiring full stochastic multi-stage models.

## Links

- [Abstract](https://arxiv.org/abs/2610.14792)
- [PDF](https://arxiv.org/pdf/2610.14792)

