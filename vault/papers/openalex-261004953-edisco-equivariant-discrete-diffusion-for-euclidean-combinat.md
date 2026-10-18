---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "EDISCO: Equivariant DIScrete Diffusion for Euclidean Combinatorial Optimization"
description: "EDISCO is a discrete diffusion model designed for Euclidean combinatorial optimization problems (ECOPs) that provides exact E(2)-invariant generative distributions over node-index solutions. By coupling an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain over discrete edge variables, the framework incorporates local geometric inductive biases that improve both data efficiency and inference robustness. Experimental evaluations show that EDISCO outperforms prior learning-based state-of-the-art solvers on large-scale Traveling Salesman and Capacitated Vehicle Routing Problems while using substantially fewer training instances and exhibiting strong generalization under distribution shifts."
resource: "https://arxiv.org/abs/2610.04953"
tags:
  - "discrete-diffusion"
  - "vehicle-routing-problem"
  - "neural-routing-solver"
  - "machine-learning"
timestamp: "2026-10-18T09:17:53Z"

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
    description: "An equivariant discrete diffusion model for Euclidean combinatorial optimization problems featuring exact E(2)-invariant generative distributions over node-index solutions."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-18T09:17:53Z"
created_at: "2026-10-18T09:17:53Z"
---

# EDISCO: Equivariant DIScrete Diffusion for Euclidean Combinatorial Optimization

**Authors**: Ruogu Chen, Jie Han
**Date**: 2026-10-04
**Paper ID**: [openalex:2610.04953](https://arxiv.org/abs/2610.04953)

## Summary

EDISCO is a discrete diffusion model designed for Euclidean combinatorial optimization problems (ECOPs) that provides exact E(2)-invariant generative distributions over node-index solutions. By coupling an E(2)-equivariant edge-score network with a categorical continuous-time Markov chain over discrete edge variables, the framework incorporates local geometric inductive biases that improve both data efficiency and inference robustness. Experimental evaluations show that EDISCO outperforms prior learning-based state-of-the-art solvers on large-scale Traveling Salesman and Capacitated Vehicle Routing Problems while using substantially fewer training instances and exhibiting strong generalization under distribution shifts.

## Key Contributions

- Proposes EDISCO, the first discrete diffusion model for Euclidean combinatorial optimization problems featuring exact E(2)-invariant generative distributions over node-index solutions.
- Introduces an E(2)-equivariant edge-score network coupled with a categorical continuous-time Markov chain over discrete edge variables for efficient multi-step inference.
- Outperforms previous learning-based state-of-the-art solvers on synthetic TSP (100 to 10,000 nodes) and CVRP (50 to 2,000 customers) while utilizing only 33-50% of the training instances.
- Demonstrates superior generalization under spatial distribution shift and CVRP constraint-tightness shift when trained exclusively on uniform synthetic data.

## Key Concepts

- [[edisco]]: An equivariant discrete diffusion model for Euclidean combinatorial optimization problems featuring exact E(2)-invariant generative distributions over node-index solutions.

## Archivist Review

The concept EDISCO is approved as a central methodological contribution combining discrete diffusion with exact E(2)-equivariance for combinatorial optimization. The proposed open question is rejected because its core theme (extending equivariance to non-euclidean and asymmetric costs) is already covered in the existing vault under extending-equivariance-non-euclidean-asymmetric-costs. No named datasets are present for vault inclusion.

### Approved Concepts
- EDISCO: EDISCO introduces the first exact E(2)-invariant discrete diffusion framework for Euclidean combinatorial optimization problems.

### Rejected Candidates
- [open_question] Equivariance in Non-Euclidean Routing (`non-euclidean-asymmetric-equivariance`) - duplicate_existing: Substantially overlaps with existing vault question extending-equivariance-non-euclidean-asymmetric-costs.

## Links

- [Abstract](https://arxiv.org/abs/2610.04953)
- [PDF](https://arxiv.org/pdf/2610.04953)

