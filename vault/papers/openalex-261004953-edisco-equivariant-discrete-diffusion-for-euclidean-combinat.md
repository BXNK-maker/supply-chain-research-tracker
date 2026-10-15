---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "EDISCO: Equivariant DIScrete Diffusion for Euclidean Combinatorial Optimization"
description: "EDISCO is the first discrete diffusion model for Euclidean combinatorial optimization problems (ECOPs) that achieves exact E(2)-invariant generative distributions over node-index solutions. By coupling an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain over discrete edge variables, the model provides robust local geometric inductive biases without relying on data augmentation or approximate regularization. Experiments on Traveling Salesman Problem and Capacitated Vehicle Routing Problem demonstrate state-of-the-art performance and strong generalization under distribution shifts while using fewer training instances."
resource: "https://arxiv.org/abs/2610.04953"
tags:
  - "combinatorial-optimization"
  - "machine-learning"
  - "vehicle-routing-problem"
  - "euclidean-combinatorial-optimization"
  - "discrete-diffusion"
timestamp: "2026-10-15T09:35:22Z"

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
    description: "An equivariant discrete diffusion model for Euclidean combinatorial optimization problems with exact E(2)-invariant generative distributions over node-index solutions."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-15T09:35:22Z"
created_at: "2026-10-15T09:35:22Z"
---

# EDISCO: Equivariant DIScrete Diffusion for Euclidean Combinatorial Optimization

**Authors**: Ruogu Chen, Jie Han
**Date**: 2026-10-04
**Paper ID**: [openalex:2610.04953](https://arxiv.org/abs/2610.04953)

## Summary

EDISCO is the first discrete diffusion model for Euclidean combinatorial optimization problems (ECOPs) that achieves exact E(2)-invariant generative distributions over node-index solutions. By coupling an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain over discrete edge variables, the model provides robust local geometric inductive biases without relying on data augmentation or approximate regularization. Experiments on Traveling Salesman Problem and Capacitated Vehicle Routing Problem demonstrate state-of-the-art performance and strong generalization under distribution shifts while using fewer training instances.

## Key Contributions

- Introduces EDISCO, the first discrete diffusion model for Euclidean combinatorial optimization problems with exact E(2)-invariant generative distributions over node-index solutions.
- Combines an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain over discrete edge variables and exact posterior sampling.
- Outperforms previous learning-based state-of-the-art solvers on synthetic TSP (100 to 10000 nodes) and CVRP (50 to 2000 customers) while using only 33-50% of the training instances.
- Demonstrates robust generalization under spatial distribution shift and CVRP constraint-tightness shift when trained only on uniform synthetic data.

## Limitations

Future work could explore extending exact equivariant discrete diffusion to even broader classes of geometric constraint satisfaction and vehicle routing variants.

## Key Concepts

- [[edisco]]: An equivariant discrete diffusion model for Euclidean combinatorial optimization problems with exact E(2)-invariant generative distributions over node-index solutions.

## Archivist Review

Approved the core concept EDISCO for its novel exact E(2)-invariant discrete diffusion framework. Rejected the open question as it framed generic future work rather than a distinct, rigorous bottleneck.

### Approved Concepts
- EDISCO: EDISCO introduces the first discrete diffusion model for Euclidean combinatorial optimization problems with exact E(2)-invariant generative distributions over node-index solutions.

### Rejected Candidates
- [open_question] Sim-to-Real and Asymmetric Routing Generalization (`sim-to-real-and-asymmetric-routing-generalization`) - low_impact: Broad and general future work direction rather than a precise technical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.04953)
- [PDF](https://arxiv.org/pdf/2610.04953)

