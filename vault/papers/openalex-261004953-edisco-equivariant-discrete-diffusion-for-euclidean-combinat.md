---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "EDISCO: Equivariant DIScrete Diffusion for Euclidean Combinatorial Optimization"
description: "EDISCO is the first discrete diffusion model for Euclidean combinatorial optimization problems (ECOPs) that achieves exact E(2)-invariance over node-index solutions. By coupling an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain over discrete edge variables, the model embeds a local geometric inductive bias into combinatorial solving. Empirical evaluations show that EDISCO outperforms prior learning-based state-of-the-art solvers on large-scale Traveling Salesman and Capacitated Vehicle Routing Problems while requiring significantly fewer training instances and exhibiting strong generalization under distribution shifts."
resource: "https://arxiv.org/abs/2610.04953"
tags:
  - "combinatorial-optimization"
  - "discrete-diffusion"
  - "vehicle-routing-problem"
timestamp: "2026-10-16T09:36:19Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Ruogu Chen"
  - literal: "Jie Han"
issued:
  date-parts:
    - [2026, 10, 4]

# Domain-specific custom fields
paper_id: "2610.04953"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "edisco"
    description: "An equivariant discrete diffusion model with exact E(2)-invariance over node-index solutions for Euclidean combinatorial optimization."
datasets:
  []
open_questions:
  - name: "equivariant-methods-non-euclidean-asymmetric-routing"
    description: "Investigating whether equivariance, symmetry alignment, and metric learning representations can be successfully extended from Euclidean routing problems to arbitrary-graph problems, non-Euclidean network costs, and asymmetric routing domains."
skill: "GeneralMLSkill"
processed_at: "2026-10-16T09:36:19Z"
created_at: "2026-10-16T09:36:19Z"
---

# EDISCO: Equivariant DIScrete Diffusion for Euclidean Combinatorial Optimization

**Authors**: Ruogu Chen, Jie Han
**Date**: 2026-10-04
**Paper ID**: [openalex:2610.04953](https://arxiv.org/abs/2610.04953)

## Summary

EDISCO is the first discrete diffusion model for Euclidean combinatorial optimization problems (ECOPs) that achieves exact E(2)-invariance over node-index solutions. By coupling an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain over discrete edge variables, the model embeds a local geometric inductive bias into combinatorial solving. Empirical evaluations show that EDISCO outperforms prior learning-based state-of-the-art solvers on large-scale Traveling Salesman and Capacitated Vehicle Routing Problems while requiring significantly fewer training instances and exhibiting strong generalization under distribution shifts.

## Key Contributions

- EDISCO introduces the first discrete diffusion model for Euclidean combinatorial optimization problems with exact E(2)-invariant generative distributions over node-index solutions.
- Combines an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain over discrete edge variables for efficient multi-step inference.
- Outperforms previous learning-based state-of-the-art solvers on synthetic TSP (100 to 10000 nodes) and CVRP (50 to 2000 customers) while using only 33-50% of the training instances.
- Demonstrates robust generalization under spatial distribution shift and CVRP constraint-tightness shift when trained exclusively on uniform synthetic data.

## Limitations

Limitations are not explicitly discussed in the abstract, but the evaluation is limited to synthetic TSP and CVRP benchmarks.

## Open Questions & Future Work

- [[equivariant-methods-non-euclidean-asymmetric-routing]]

## Key Concepts

- [[edisco]]: An equivariant discrete diffusion model with exact E(2)-invariance over node-index solutions for Euclidean combinatorial optimization.

## Archivist Review

Approved the central model concept EDISCO and the open question regarding non-Euclidean equivariant routing extensions, adhering to strict vault standards and avoiding redundant or subcomponent entries.

### Approved Concepts
- EDISCO: Introduces the first discrete diffusion framework with exact E(2)-invariance for Euclidean combinatorial optimization problems.

### Approved Open Questions
- Equivariance in Non-Euclidean Routing: Understanding how to extend geometric and equivariant inductive biases to non-Euclidean or asymmetric combinatorial problems is a key open frontier in neural combinatorial optimization.

### Rejected Candidates
- [concept] E(2)-equivariant discrete diffusion (`e-2-equivariant-discrete-diffusion`) - duplicate_existing: Redundant with the main EDISCO concept.

## Links

- [Abstract](https://arxiv.org/abs/2610.04953)
- [PDF](https://arxiv.org/pdf/2610.04953)

