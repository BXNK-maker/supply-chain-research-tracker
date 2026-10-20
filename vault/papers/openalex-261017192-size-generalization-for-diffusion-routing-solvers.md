---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Size Generalization for Diffusion Routing Solvers"
description: "Routing problems like TSP and CVRP are computationally expensive for large instances, and existing diffusion-based solvers struggle to generalize beyond their training distribution sizes. This paper introduces ResizeCO, a label-free size-generalization approach that uses reinforcement learning (adapting GRPO with route length as a signal) and GPU-accelerated beam search to adapt small-instance diffusion models to larger instances. Evaluated on TSP and CVRP instances with up to 10,000 nodes, ResizeCO establishes a new state-of-the-art Pareto front balancing route quality and computation time compared to prior learned and traditional solvers."
resource: "https://arxiv.org/abs/2610.17192"
tags:
  - "neural-routing-solver"
  - "combinatorial-optimization"
  - "machine-learning"
timestamp: "2026-10-20T09:47:24Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Barak Itzchak Davidovitch"
  - literal: "Eli A. Meirom"
  - literal: "Ethan Fetaya"
  - literal: "Gal Chechik"
issued:
  date-parts:
    - [2026, 10, 12]

# Domain-specific custom fields
paper_id: "2610.17192"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "resizeco"
    description: "A label-free size-generalization approach for diffusion-based routing solvers using reinforcement learning and GPU-accelerated beam search."
datasets:
  []
open_questions:
  - name: "size-generalization-diffusion-routing"
    description: "Investigate and develop principled techniques to overcome the performance degradation of neural combinatorial optimization and diffusion routing solvers when generalizing to instance sizes and distributions substantially larger than the training set."
skill: "GeneralMLSkill"
processed_at: "2026-10-20T09:47:24Z"
created_at: "2026-10-20T09:47:24Z"
---

# Size Generalization for Diffusion Routing Solvers

**Authors**: Barak Itzchak Davidovitch, Eli A. Meirom, Ethan Fetaya, Gal Chechik
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.17192](https://arxiv.org/abs/2610.17192)

## Summary

Routing problems like TSP and CVRP are computationally expensive for large instances, and existing diffusion-based solvers struggle to generalize beyond their training distribution sizes. This paper introduces ResizeCO, a label-free size-generalization approach that uses reinforcement learning (adapting GRPO with route length as a signal) and GPU-accelerated beam search to adapt small-instance diffusion models to larger instances. Evaluated on TSP and CVRP instances with up to 10,000 nodes, ResizeCO establishes a new state-of-the-art Pareto front balancing route quality and computation time compared to prior learned and traditional solvers.

## Key Contributions

- Proposed ResizeCO, a label-free size-generalization framework that adapts small-instance trained diffusion models to large-scale routing instances via reinforcement learning.
- Formulated k-opt as a tree search and implemented GPU-accelerated beam search to handle large instances efficiently.
- Achieved a Pareto front over route quality and execution time that dominates prior learned solvers on TSP and CVRP instances with up to 10000 nodes.

## Open Questions & Future Work

- [[size-generalization-diffusion-routing]]

## Key Concepts

- [[resizeco]]: A label-free size-generalization approach for diffusion-based routing solvers using reinforcement learning and GPU-accelerated beam search.

## Archivist Review

Approved the core concept 'ResizeCO' as it provides a distinct, reusable paradigm for label-free size-generalization in combinatorial optimization and diffusion solvers. Also approved the open question on size generalization in diffusion routing solvers, which captures a fundamental bottleneck in scaling neural solvers to larger problem instances. No datasets were approved because TSP and CVRP are standard problem domains rather than specific named benchmark datasets.

### Approved Concepts
- ResizeCO: ResizeCO is the central methodological contribution of the paper, introducing a label-free size-generalization approach combining reinforcement learning with diffusion models for routing solvers.

### Approved Open Questions
- Size Generalization in Diffusion Routing Solvers: Size generalization is a primary bottleneck for deploying neural routing solvers in real-world scenarios where instance scales vary dynamically.

## Links

- [Abstract](https://arxiv.org/abs/2610.17192)
- [PDF](https://arxiv.org/pdf/2610.17192)

