---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions"
description: "The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for same-day delivery that combines a neural CVRP solver (Graph Edge Attention Network) with Thompson sampling for online customer preference learning. By rapidly evaluating routing cost deltas for home versus out-of-home delivery options in parallel batches, the system sets dynamic delivery fees that steer customers toward cost-effective out-of-home alternatives. Evaluations demonstrate an 11% profit increase over traditional routing solvers and superior performance compared to static pricing strategies."
resource: "https://arxiv.org/abs/2610.14792"
tags:
  - "fleet-scheduling"
  - "neural-routing-solver"
  - "dynamic-pricing"
  - "choice-modeling"
  - "time-series"
timestamp: "2026-10-19T10:28:09Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Attila Lischka"
  - literal: "Ze Zhou"
  - literal: "Xuegang, Ban"
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
    description: "A neural solver for the capacitated vehicle routing problem using graph edge attention to reoptimize routes under changing conditions."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-19T10:28:09Z"
created_at: "2026-10-19T10:28:09Z"
---

# GREAT-ESDD: Graph Edge Attention Network for Effectively Steered Delivery Decisions

**Authors**: Attila Lischka, Ze Zhou, Xuegang, Ban, Balaźs Kulcsár
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.14792](https://arxiv.org/abs/2610.14792)

## Summary

The paper introduces GREAT-ESDD, a dynamic pricing-and-routing framework for same-day delivery that combines a neural CVRP solver (Graph Edge Attention Network) with Thompson sampling for online customer preference learning. By rapidly evaluating routing cost deltas for home versus out-of-home delivery options in parallel batches, the system sets dynamic delivery fees that steer customers toward cost-effective out-of-home alternatives. Evaluations demonstrate an 11% profit increase over traditional routing solvers and superior performance compared to static pricing strategies.

## Key Contributions

- Developed GREAT, a neural solver for the capacitated vehicle routing problem (CVRP) capable of handling varying instance sizes and reoptimizing partially executed routes in parallel batches.
- Created a dynamic pricing-and-routing framework (GREAT-ESDD) that estimates delivery cost increases via CVRP candidate routing to set real-time delivery fees.
- Integrated Thompson sampling with a Laplace-approximated posterior to learn online customer preferences for home versus out-of-home delivery options.
- Demonstrated an 11% profit increase compared to traditional routing solvers under similar pricing time budgets, while outperforming static pricing after 5 days of simulated operations.

## Limitations

Future work may involve scaling the framework to larger networks and validating customer preference models with real-world empirical data under broader demand shocks.

## Key Concepts

- [[graph-edge-attention-network]]: A neural solver for the capacitated vehicle routing problem using graph edge attention to reoptimize routes under changing conditions.

## Archivist Review

Approved the graph-edge-attention-network concept as it already exists in the vault and represents a reusable neural routing module. Rejected GREAT-ESDD as a paper-specific system integration and rejected the open question as routine parameter tuning.

### Approved Concepts
- Graph Edge Attention Network (GREAT): Central neural routing solver component used to reoptimize partially executed CVRP routes and evaluate routing cost deltas for dynamic pricing.

### Rejected Candidates
- [concept] GREAT-ESDD (`great-esdd`) - paper_local: Paper-specific application framework that combines existing subcomponents (GREAT and Thompson sampling) for a specific delivery scenario.
- [open_question] Adaptive Rectifier Online Tuning (`adaptive-rectifier-online-tuning`) - not_novel: Routine hyperparameter tuning and optimization extension specific to the paper's cost correction parameter omega.

## Links

- [Abstract](https://arxiv.org/abs/2610.14792)
- [PDF](https://arxiv.org/pdf/2610.14792)

