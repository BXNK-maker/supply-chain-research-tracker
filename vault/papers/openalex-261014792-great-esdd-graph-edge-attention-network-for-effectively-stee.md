---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions"
description: "The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for online same-day delivery that combines home and out-of-home (OOH) options. It utilizes a novel neural solver based on the Graph Edge Attention Network (GREAT) to solve capacitated vehicle routing problems in parallel, estimating cost increases to inform dynamic prices. Customer preferences are learned online using Thompson sampling with a Laplace-approximated posterior, effectively steering customers toward OOH delivery when home delivery is costly. Simulations show a profit increase of around 11% over traditional routing solvers while successfully estimating customer preferences within 5 days."
resource: "https://arxiv.org/abs/2610.14792"
tags:
  - "dynamic-pricing"
  - "neural-routing-solver"
  - "vehicle-routing-problem"
  - "choice-modeling"
  - "time-series"
timestamp: "2026-10-18T09:18:41Z"

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
    description: "A neural solver for the capacitated vehicle routing problem that uses graph edge attention to rapidly reoptimize routes under changing conditions."
datasets:
  []
open_questions:
  - name: "adaptive-cost-rectifier-learning"
    description: "Investigate mechanisms to dynamically learn or adapt the cost rectifier parameter over the operating horizon, as routing cost estimations become more accurate later in the day compared to earlier periods."
skill: "GeneralMLSkill"
processed_at: "2026-10-18T09:18:41Z"
created_at: "2026-10-18T09:18:41Z"
---

# GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions

**Authors**: Attila Lischka, Ze Zhou, Xuegang, Ban, Balaźs Kulcsár
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.14792](https://arxiv.org/abs/2610.14792)

## Summary

The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for online same-day delivery that combines home and out-of-home (OOH) options. It utilizes a novel neural solver based on the Graph Edge Attention Network (GREAT) to solve capacitated vehicle routing problems in parallel, estimating cost increases to inform dynamic prices. Customer preferences are learned online using Thompson sampling with a Laplace-approximated posterior, effectively steering customers toward OOH delivery when home delivery is costly. Simulations show a profit increase of around 11% over traditional routing solvers while successfully estimating customer preferences within 5 days.

## Key Contributions

- Developed a fast neural solver based on the Graph Edge Attention Network (GREAT) capable of reoptimizing partially executed CVRP routes under changing conditions.
- Proposed a dynamic pricing-and-routing framework (GREAT-ESDD) that estimates delivery cost increases in parallel batches to price home versus out-of-home delivery options.
- Integrated Thompson sampling with a Laplace-approximated posterior to learn online customer preferences for delivery options.
- Demonstrated an 11% profit increase compared to traditional routing solvers and outperformed static pricing after 5 days of simulated operations.

## Open Questions & Future Work

- [[adaptive-cost-rectifier-learning]]

## Key Concepts

- [[graph-edge-attention-network]]: A neural solver for the capacitated vehicle routing problem that uses graph edge attention to rapidly reoptimize routes under changing conditions.

## Archivist Review

Approved the graph-edge-attention-network concept as it represents a distinct neural combinatorial solver architecture. Approved the adaptive-cost-rectifier-learning open question because it addresses a specific non-stationary operational bottleneck. Rejected GREAT-ESDD as it is a paper-local system name combining existing components.

### Approved Concepts
- Graph Edge Attention Network (GREAT): Acts as the core neural routing solver enabling fast parallel CVRP evaluations for dynamic pricing and reoptimization in delivery decisions.

### Approved Open Questions
- Adaptive Cost Rectifier Learning: Crucial for bridging myopic heuristic estimates with non-stationary online environments to optimize operational profits without manual offline grid searches.

### Rejected Candidates
- [concept] GREAT-ESDD (`great-esdd`) - paper_local: Subsumed by graph-edge-attention-network and the broader combination of dynamic pricing, making it a paper-local application framework rather than a general core vault note.

## Links

- [Abstract](https://arxiv.org/abs/2610.14792)
- [PDF](https://arxiv.org/pdf/2610.14792)

