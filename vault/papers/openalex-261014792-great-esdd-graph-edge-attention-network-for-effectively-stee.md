---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions"
description: "The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for online same-day delivery that combines home and out-of-home (OOH) options. At its core, it employs a Graph-Edge-Attention-Network (GREAT) neural solver to efficiently reoptimize capacitated vehicle routing problems in parallel. By estimating routing cost changes per delivery option, the system dynamically prices choices and uses Thompson sampling with a Laplace approximation to learn customer preferences online. Experiments show that GREAT-ESDD increases profit by around 11% over traditional routing solvers and outperforms static pricing after 5 days of simulated operations."
resource: "https://arxiv.org/abs/2610.14792"
tags:
  - "dynamic-pricing"
  - "neural-routing-solver"
  - "fleet-scheduling"
  - "choice-modeling"
  - "time-series"
timestamp: "2026-10-21T09:48:14Z"

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
    description: "A graph edge attention network designed as a fast neural solver for capacitated vehicle routing problems."
  - name: "great-esdd"
    description: "A dynamic pricing-and-routing framework combining graph neural network routing solvers with Thompson sampling for out-of-home delivery steering."
datasets:
  []
open_questions:
  - name: "adaptive-cost-rectification-scaling"
    description: "Investigate whether adaptive or time-varying cost-rectification scaling parameters can replace static offline-tuned values to improve the accuracy of myopic routing cost estimates in dynamic pricing-and-routing frameworks."
skill: "GeneralMLSkill"
processed_at: "2026-10-21T09:48:14Z"
created_at: "2026-10-21T09:48:14Z"
---

# GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions

**Authors**: Attila Lischka, Ze Zhou, Xuegang, Ban, Balaźs Kulcsár
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.14792](https://arxiv.org/abs/2610.14792)

## Summary

The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for online same-day delivery that combines home and out-of-home (OOH) options. At its core, it employs a Graph-Edge-Attention-Network (GREAT) neural solver to efficiently reoptimize capacitated vehicle routing problems in parallel. By estimating routing cost changes per delivery option, the system dynamically prices choices and uses Thompson sampling with a Laplace approximation to learn customer preferences online. Experiments show that GREAT-ESDD increases profit by around 11% over traditional routing solvers and outperforms static pricing after 5 days of simulated operations.

## Key Contributions

- Developed a neural solver based on Graph-Edge-Attention-Network (GREAT) for solving capacitated vehicle routing problems (CVRP) with varying instance sizes and starting conditions.
- Created a dynamic pricing-and-routing framework (GREAT-ESDD) that integrates parallel batch CVRP solving to estimate delivery cost increases and trade off fees against routing costs.
- Utilized Thompson sampling with a Laplace-approximated posterior to learn online customer preferences for home versus out-of-home delivery options.
- Demonstrated an 11% profit increase compared to traditional routing solvers under similar decision time budgets, outperforming static pricing strategies after 5 days of simulated operations.

## Limitations

Evaluated using simulated operations; relies on accurate online preference learning assumptions.

## Open Questions & Future Work

- [[adaptive-cost-rectification-scaling]]

## Key Concepts

- [[graph-edge-attention-network]]: A graph edge attention network designed as a fast neural solver for capacitated vehicle routing problems.
- [[great-esdd]]: A dynamic pricing-and-routing framework combining graph neural network routing solvers with Thompson sampling for out-of-home delivery steering.

## Archivist Review

Approved the two central concepts (GREAT and GREAT-ESDD) as they represent distinctive architectural patterns and dynamic frameworks for vehicle routing and pricing. The open question on adaptive cost rectification was approved because it addresses a specific unresolved parameterization bottleneck in myopic routing cost estimation. No datasets were approved as none were explicitly named.

### Approved Concepts
- Graph Edge Attention Network: Central neural solver architecture used to solve CVRP instances under changing conditions.
- GREAT-ESDD: Core dynamic pricing-and-routing framework combining neural routing with online preference learning.

### Approved Open Questions
- Adaptive Cost Rectification Scaling: Static cost rectification limits the adaptability of myopic pricing-and-routing frameworks across varying operational horizons and demand intensities, making dynamic or learned rectification a critical direction for online delivery optimization.

## Links

- [Abstract](https://arxiv.org/abs/2610.14792)
- [PDF](https://arxiv.org/pdf/2610.14792)

