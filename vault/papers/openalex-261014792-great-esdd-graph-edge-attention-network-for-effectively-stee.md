---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions"
description: "The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for same-day delivery that combines a graph-edge-attention-network neural solver for the capacitated vehicle routing problem with Thompson sampling for online customer preference learning. By rapidly evaluating routing cost increases for home versus out-of-home delivery options, the framework dynamically adjusts delivery fees to steer customer choices and increase overall operating profit. Simulations demonstrate an 11% profit increase over traditional routing solvers and effective online learning of customer preferences within 5 days."
resource: "https://arxiv.org/abs/2610.14792"
tags:
  - "dynamic-pricing"
  - "demand-forecasting"
  - "neural-routing-solver"
  - "choice-modeling"
  - "time-series"
timestamp: "2026-10-20T09:47:53Z"

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
  - name: "great-esdd"
    description: "A dynamic pricing-and-routing framework using a graph edge attention network and Thompson sampling for out-of-home delivery steering."
datasets:
  []
open_questions:
  - name: "adaptive-cost-rectification-online-routing"
    description: "Investigate how the cost-correction rectifier parameter can be learned or adapted dynamically as a function of time or the fraction of completed orders, replacing the current static offline grid-search approach."
skill: "GeneralMLSkill"
processed_at: "2026-10-20T09:47:53Z"
created_at: "2026-10-20T09:47:53Z"
---

# GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions

**Authors**: Attila Lischka, Ze Zhou, Xuegang, Ban, Balaźs Kulcsár
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.14792](https://arxiv.org/abs/2610.14792)

## Summary

The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for same-day delivery that combines a graph-edge-attention-network neural solver for the capacitated vehicle routing problem with Thompson sampling for online customer preference learning. By rapidly evaluating routing cost increases for home versus out-of-home delivery options, the framework dynamically adjusts delivery fees to steer customer choices and increase overall operating profit. Simulations demonstrate an 11% profit increase over traditional routing solvers and effective online learning of customer preferences within 5 days.

## Key Contributions

- Developed GREAT-ESDD, a dynamic pricing-and-routing framework combining a graph-edge-attention-network neural solver with online preference learning for out-of-home delivery steering.
- Trained a fast neural CVRP solver capable of reoptimizing partially executed routes under changing conditions across varying instance sizes.
- Integrated Thompson sampling with a Laplace-approximated posterior to learn customer delivery preferences online.
- Increased profit by around 11% compared to a traditional routing solver while operating within similar pricing decision time budgets.

## Limitations

Evaluated using simulated operations; requires online adaptation of customer preferences and fast batch parallel CVRP solving.

## Open Questions & Future Work

- [[adaptive-cost-rectification-online-routing]]

## Key Concepts

- [[great-esdd]]: A dynamic pricing-and-routing framework using a graph edge attention network and Thompson sampling for out-of-home delivery steering.

## Archivist Review

Approved the core framework GREAT-ESDD as a reusable concept for dynamic pricing and neural routing. Rejected the underlying graph edge attention network as a subcomponent of the broader mechanism. Approved the open question regarding adaptive cost rectification in online routing, as it addresses a substantive methodological bottleneck. No datasets met the criteria for standalone note approval.

### Approved Concepts
- GREAT-ESDD: Core framework combining dynamic pricing, graph edge attention neural routing, and online preference learning for same-day delivery.

### Approved Open Questions
- Adaptive Cost Rectification in Online Routing: Static rectification limits the adaptability of dynamic pricing and routing frameworks across varying operational horizons and demand distributions, making adaptive or learned rectification an important methodological direction for online combinatorial optimization.

### Rejected Candidates
- [concept] Graph Edge Attention Network (`graph-edge-attention-network`) - subcomponent_of_broader_mechanism: Subcomponent of broader mechanism or architecture variant without standalone theoretical novelty beyond GREAT-ESDD.

## Links

- [Abstract](https://arxiv.org/abs/2610.14792)
- [PDF](https://arxiv.org/pdf/2610.14792)

