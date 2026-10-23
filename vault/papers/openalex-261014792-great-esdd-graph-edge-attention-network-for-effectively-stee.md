---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions"
description: "The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for online same-day delivery that combines home and out-of-home options. It leverages a fast neural solver based on the Graph-Edge-Attention-Network (GREAT) to reoptimize capacitated vehicle routing problems in parallel, estimating cost increases to set dynamic delivery prices. Customer preferences are learned online using Thompson sampling with a Laplace-approximated posterior, successfully steering customers toward cost-effective delivery options and increasing operator profit by around 11%."
resource: "https://arxiv.org/abs/2610.14792"
tags:
  - "neural-routing-solver"
  - "dynamic-pricing"
  - "choice-modeling"
  - "vehicle-routing-problem"
  - "time-series"
timestamp: "2026-10-23T09:46:25Z"

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
    description: "A graph attention network variant designed for solving and reoptimizing capacitated vehicle routing problems."
datasets:
  []
open_questions:
  - name: "anticipatory-non-myopic-cost-estimates"
    description: "Investigate and develop non-myopic or anticipatory cost estimation techniques that account for future customer arrivals and dynamic demand patterns, moving beyond myopic marginal routing cost approximations in vehicle routing and pricing frameworks."
skill: "GeneralMLSkill"
processed_at: "2026-10-23T09:46:25Z"
created_at: "2026-10-23T09:46:25Z"
---

# GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions

**Authors**: Attila Lischka, Ze Zhou, Xuegang, Ban, Balaźs Kulcsár
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.14792](https://arxiv.org/abs/2610.14792)

## Summary

The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for online same-day delivery that combines home and out-of-home options. It leverages a fast neural solver based on the Graph-Edge-Attention-Network (GREAT) to reoptimize capacitated vehicle routing problems in parallel, estimating cost increases to set dynamic delivery prices. Customer preferences are learned online using Thompson sampling with a Laplace-approximated posterior, successfully steering customers toward cost-effective delivery options and increasing operator profit by around 11%.

## Key Contributions

- Developed a neural solver based on the Graph Edge Attention Network (GREAT) capable of solving and reoptimizing CVRP instances across varying sizes and starting conditions.
- Designed a dynamic pricing-and-routing framework (GREAT-ESDD) that integrates parallel CVRP solving to estimate delivery cost increases and steer customers toward out-of-home options.
- Employed Thompson sampling with a Laplace-approximated posterior to learn online customer preferences for delivery options.
- Demonstrated an 11% profit increase over traditional routing solvers and superior performance compared to static pricing after 5 days of simulated operations.

## Limitations

Evaluated on simulated operations; relies on accurate modeling of customer choice preferences.

## Open Questions & Future Work

- [[anticipatory-non-myopic-cost-estimates]]

## Key Concepts

- [[graph-edge-attention-network]]: A graph attention network variant designed for solving and reoptimizing capacitated vehicle routing problems.

## Archivist Review

Applied strict selection criteria to maintain a high-signal knowledge vault. Graph Edge Attention Network is already in the vault and correctly reused. GREAT-ESDD is rejected as paper-local application branding. The open question on anticipatory non-myopic cost estimates is approved as it addresses a fundamental algorithmic bottleneck in neural combinatorial optimization and dynamic pricing.

### Approved Concepts
- Graph Edge Attention Network: Serves as the core neural routing solver handling varying instance sizes and partial route reoptimization.

### Approved Open Questions
- Anticipatory Non-Myopic Cost Estimates: Overcoming myopic routing cost approximations is a fundamental bottleneck for bridging static neural solvers with truly optimal dynamic pricing and routing in online logistics.

### Rejected Candidates
- [concept] GREAT-ESDD (`great-esdd`) - paper_local: GREAT-ESDD is a paper-local system name combining specific routing and pricing components rather than a broadly reusable architectural pattern.

## Links

- [Abstract](https://arxiv.org/abs/2610.14792)
- [PDF](https://arxiv.org/pdf/2610.14792)

