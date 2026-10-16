---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions"
description: "The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for online same-day delivery with home and out-of-home options. At its core, the framework uses a Graph Edge Attention Network (GREAT) as a fast neural solver for the capacitated vehicle routing problem, enabling parallel batch processing and real-time route reoptimization. By combining this neural solver with Thompson sampling using a Laplace-approximated posterior to learn customer preferences, GREAT-ESDD steers customers toward cost-effective delivery options and increases operator profit by around 11%."
resource: "https://arxiv.org/abs/2610.14792"
tags:
  - "choice-modeling"
  - "combinatorial-optimization"
  - "machine-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-16T09:36:32Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Attila Lischka"
  - literal: "Ze Zhou"
  - literal: "Xuegang Ban"
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
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-16T09:36:32Z"
created_at: "2026-10-16T09:36:32Z"
---

# GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions

**Authors**: Attila Lischka, Ze Zhou, Xuegang Ban, Balaźs Kulcsár
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.14792](https://arxiv.org/abs/2610.14792)

## Summary

The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for online same-day delivery with home and out-of-home options. At its core, the framework uses a Graph Edge Attention Network (GREAT) as a fast neural solver for the capacitated vehicle routing problem, enabling parallel batch processing and real-time route reoptimization. By combining this neural solver with Thompson sampling using a Laplace-approximated posterior to learn customer preferences, GREAT-ESDD steers customers toward cost-effective delivery options and increases operator profit by around 11%.

## Key Contributions

- Developed GREAT-ESDD, a dynamic pricing-and-routing framework integrating a neural CVRP solver with online customer preference learning.
- Utilized a Graph-Edge-Attention-Network (GREAT) to solve CVRP instances in parallel and reoptimize partially executed routes rapidly.
- Demonstrated an 11% profit increase compared to traditional routing solvers under similar timing constraints.
- Learned customer preferences online via Thompson sampling with a Laplace-approximated posterior, outperforming static pricing after 5 days.

## Limitations

The framework relies on simulated operations for customer preference learning and pricing validation.

## Archivist Review

I applied strict standards for vault admission, rejecting both the graph edge attention network concept as a domain-specific subcomponent of vehicle routing and the adaptive cost rectifiers question as a paper-local parameter tuning exploration. Consequently, no standalone notes were approved.

### Rejected Candidates
- [concept] Graph Edge Attention Network (`graph-edge-attention-network`) - subcomponent_of_broader_mechanism: The proposed Graph Edge Attention Network is a specialized architecture variant tailored for vehicle routing and acts as a subcomponent of the broader dynamic pricing-and-routing framework, lacking sufficient independent reusability outside specialized routing tasks.
- [open_question] Adaptive Cost Rectifiers in Dynamic Pricing (`adaptive-cost-rectifiers-dynamic-pricing`) - paper_local: The question is a paper-local exploration of tuning a specific parameter omega within a simulated delivery pricing heuristic rather than a broad, foundational bottleneck in machine learning.

## Links

- [Abstract](https://arxiv.org/abs/2610.14792)
- [PDF](https://arxiv.org/pdf/2610.14792)

