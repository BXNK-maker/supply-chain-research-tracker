---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions"
description: "The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for same-day delivery that combines a fast neural CVRP solver (GREAT) with online customer preference learning via Thompson sampling. By rapidly evaluating routing cost changes for home versus out-of-home delivery options, the framework dynamically adjusts prices to steer customers toward cost-effective delivery methods. Simulations show an 11% profit increase over traditional routing solvers and superior performance compared to static pricing strategies."
resource: "https://arxiv.org/abs/2610.14792"
tags:
  - "vehicle-routing-problem"
  - "neural-routing-solver"
  - "dynamic-pricing"
  - "choice-modeling"
  - "reinforcement-learning"
timestamp: "2026-10-24T09:17:47Z"

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
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-24T09:17:47Z"
created_at: "2026-10-24T09:17:47Z"
---

# GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions

**Authors**: Attila Lischka, Ze Zhou, Xuegang, Ban, Balaźs Kulcsár
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.14792](https://arxiv.org/abs/2610.14792)

## Summary

The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for same-day delivery that combines a fast neural CVRP solver (GREAT) with online customer preference learning via Thompson sampling. By rapidly evaluating routing cost changes for home versus out-of-home delivery options, the framework dynamically adjusts prices to steer customers toward cost-effective delivery methods. Simulations show an 11% profit increase over traditional routing solvers and superior performance compared to static pricing strategies.

## Key Contributions

- Developed GREAT, a fast neural solver for the capacitated vehicle routing problem (CVRP) capable of handling varying instance sizes and reoptimizing partially executed routes in parallel batches.
- Created a dynamic pricing-and-routing framework (GREAT-ESDD) that estimates delivery cost increases from neural CVRP solutions to set delivery fees and steer customers toward out-of-home options.
- Integrated Thompson sampling with a Laplace-approximated posterior to learn online customer preferences for home versus out-of-home delivery options.
- Demonstrated around 11% profit increase compared to traditional routing solvers under similar pricing decision time budgets, while outperforming static pricing after 5 days of simulated operations.

## Limitations

Evaluated primarily in simulated operations; potential generalization challenges in highly volatile, large-scale real-world routing scenarios remain to be fully quantified.

## Archivist Review

Applied strict scarcity and reusability standards. The framework GREAT-ESDD and its associated parameter tuning question are highly specialized to last-mile delivery operations and do not represent broad, standalone machine learning concepts or fundamental research bottlenecks.

### Rejected Candidates
- [concept] GREAT-ESDD (`great-esdd`) - not_reusable: The framework is highly application-specific to last-mile logistics and out-of-home delivery pricing, lacking broad standalone reusability across general machine learning research.
- [open_question] Adaptive Routing Cost Rectification (`adaptive-rectification-parameter-learning`) - paper_local: This is a paper-local tuning detail regarding a specific heuristic parameter within the specific delivery pricing framework.

## Links

- [Abstract](https://arxiv.org/abs/2610.14792)
- [PDF](https://arxiv.org/pdf/2610.14792)

