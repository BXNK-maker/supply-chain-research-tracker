---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "EDISCO: Equivariant DIScrete Diffusion for Euclidean Combinatorial Optimization"
description: "This paper introduces EDISCO, the first discrete diffusion model for Euclidean combinatorial optimization problems that guarantees exact E(2)-invariant generative distributions over node-index solutions. By coupling an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain over discrete edge variables, the model naturally incorporates local geometric inductive biases. Experiments demonstrate that EDISCO outperforms prior learning-based solvers on large-scale Traveling Salesman and Capacitated Vehicle Routing problems while requiring fewer training instances and exhibiting strong robustness to distribution and constraint shifts."
resource: "https://arxiv.org/abs/2610.04953"
tags:
  - "combinatorial-optimization"
  - "discrete-diffusion"
  - "vehicle-routing-problem"
timestamp: "2026-10-17T08:59:57Z"

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
    description: "A discrete diffusion model for Euclidean combinatorial optimization with exact E(2)-invariant generative distributions over node-index solutions."
datasets:
  []
open_questions:
  - name: "extending-equivariance-non-euclidean-asymmetric-costs"
    description: "Investigate how to generalize exact E(2)-equivariance and distribution-level symmetry guarantees to non-Euclidean representations, asymmetric routing costs, and real-world network structures where standard coordinate-based geometric assumptions do not apply."
skill: "GeneralMLSkill"
processed_at: "2026-10-17T08:59:57Z"
created_at: "2026-10-17T08:59:57Z"
---

# EDISCO: Equivariant DIScrete Diffusion for Euclidean Combinatorial Optimization

**Authors**: Ruogu Chen, Jie Han
**Date**: 2026-10-04
**Paper ID**: [openalex:2610.04953](https://arxiv.org/abs/2610.04953)

## Summary

This paper introduces EDISCO, the first discrete diffusion model for Euclidean combinatorial optimization problems that guarantees exact E(2)-invariant generative distributions over node-index solutions. By coupling an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain over discrete edge variables, the model naturally incorporates local geometric inductive biases. Experiments demonstrate that EDISCO outperforms prior learning-based solvers on large-scale Traveling Salesman and Capacitated Vehicle Routing problems while requiring fewer training instances and exhibiting strong robustness to distribution and constraint shifts.

## Key Contributions

- Introduces EDISCO, the first discrete diffusion model for Euclidean combinatorial optimization problems with exact E(2)-invariant generative distributions over node-index solutions.
- Combines an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain over discrete edge variables to provide efficient multi-step inference.
- Outperforms previous learning-based state-of-the-art solvers on synthetic TSP (100 to 10000 nodes) and CVRP (50 to 2000 customers) while using only 33-50% of the training instances.
- Demonstrates robust generalisation under spatial distribution shifts and CVRP constraint-tightness shifts when trained solely on uniform synthetic data.

## Limitations

Future work could explore extending exact E(2)-invariant discrete diffusion to higher-dimensional spaces or more complex routing constraints.

## Open Questions & Future Work

- [[extending-equivariance-non-euclidean-asymmetric-costs]]

## Key Concepts

- [[edisco]]: A discrete diffusion model for Euclidean combinatorial optimization with exact E(2)-invariant generative distributions over node-index solutions.

## Archivist Review

Approved the core concept EDISCO and the open question regarding non-Euclidean equivariance. No new datasets were approved since the paper uses standard synthetic problem instances (TSP/CVRP) rather than a novel named dataset.

### Approved Concepts
- EDISCO: EDISCO introduces the first discrete diffusion model for Euclidean combinatorial optimization problems with exact E(2)-invariant generative distributions over node-index solutions.

### Approved Open Questions
- Equivariance in Non-Euclidean Routing: Extending exact geometric equivariance beyond symmetric Euclidean problems is crucial for handling broader classes of real-world routing and optimization tasks with asymmetric or non-metric costs.

## Links

- [Abstract](https://arxiv.org/abs/2610.04953)
- [PDF](https://arxiv.org/pdf/2610.04953)

