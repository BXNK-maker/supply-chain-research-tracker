---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "EDISCO: Equivariant DIScrete Diffusion for Euclidean Combinatorial Optimization"
description: "This paper introduces EDISCO, a novel discrete diffusion model for Euclidean combinatorial optimization problems (ECOPs) that guarantees exact E(2)-invariance over node-index solutions. By coupling an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain, EDISCO incorporates a local geometric inductive bias that makes learning and inference more efficient. Experimental results show that EDISCO outperforms prior learning-based solvers on large-scale TSP and CVRP instances while requiring fewer training instances and exhibiting strong robustness to distribution shifts."
resource: "https://arxiv.org/abs/2610.04953"
tags:
  - "machine-learning"
timestamp: "2026-10-15T04:45:05Z"

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
    description: "A discrete diffusion model for Euclidean combinatorial optimization featuring exact E(2)-invariant generative distributions over node-index solutions."
datasets:
  []
open_questions:
  - name: "non-euclidean-asymmetric-routing-equivariance"
    description: "Investigate how to close the sim-to-real gap and study exact equivariance in non-Euclidean or asymmetric routing representations, such as Finsler multi-dimensional scaling or directional encoders, where standard Euclidean group symmetries do not directly apply."
skill: "GeneralMLSkill"
processed_at: "2026-10-15T04:45:05Z"
created_at: "2026-10-15T04:45:05Z"
---

# EDISCO: Equivariant DIScrete Diffusion for Euclidean Combinatorial Optimization

**Authors**: Ruogu Chen, Jie Han
**Date**: 2026-10-04
**Paper ID**: [openalex:2610.04953](https://arxiv.org/abs/2610.04953)

## Summary

This paper introduces EDISCO, a novel discrete diffusion model for Euclidean combinatorial optimization problems (ECOPs) that guarantees exact E(2)-invariance over node-index solutions. By coupling an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain, EDISCO incorporates a local geometric inductive bias that makes learning and inference more efficient. Experimental results show that EDISCO outperforms prior learning-based solvers on large-scale TSP and CVRP instances while requiring fewer training instances and exhibiting strong robustness to distribution shifts.

## Key Contributions

- Introduces EDISCO, the first discrete diffusion model for Euclidean combinatorial optimization problems (ECOPs) providing exact E(2)-invariant generative distributions over node-index solutions.
- Combines an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain over discrete edge variables for efficient multi-step posterior sampling.
- Outperforms previous learning-based state-of-the-art solvers on synthetic TSP (100 to 10000 nodes) and CVRP (50 to 2000 customers) while utilizing only 33-50% of the training instances.
- Demonstrates robust generalization under spatial distribution shift and CVRP constraint-tightness shift when trained solely on uniform synthetic data.

## Limitations

The paper evaluates EDISCO primarily on synthetic TSP and CVRP instances; performance on complex real-world routing datasets with heterogeneous side constraints is not fully explored.

## Open Questions & Future Work

- [[non-euclidean-asymmetric-routing-equivariance]]

## Key Concepts

- [[edisco]]: A discrete diffusion model for Euclidean combinatorial optimization featuring exact E(2)-invariant generative distributions over node-index solutions.

## Archivist Review

Approved the core methodological concept EDISCO for its novel exact E(2)-invariant discrete diffusion framework, and retained the open question on non-Euclidean routing equivariance as a valuable research direction. No datasets were approved since none met the rigorous proper-noun benchmark criterion.

### Approved Concepts
- EDISCO: Introduces the first discrete diffusion model for Euclidean combinatorial optimization with exact E(2)-invariant generative distributions, serving as the core methodological contribution of the paper.

### Approved Open Questions
- Equivariance in Non-Euclidean Routing: Extends exact geometric deep learning frameworks beyond the standard Euclidean domain to complex asymmetric and real-world network structures.

## Links

- [Abstract](https://arxiv.org/abs/2610.04953)
- [PDF](https://arxiv.org/pdf/2610.04953)

