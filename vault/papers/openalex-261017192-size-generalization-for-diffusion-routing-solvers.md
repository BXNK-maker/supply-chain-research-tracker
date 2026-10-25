---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Size Generalization for Diffusion Routing Solvers"
description: "Routing problems like the Traveling Salesman Problem (TSP) and Capacitated Vehicle Routing Problem (CVRP) are NP-hard and challenging to scale. This paper introduces ResizeCO, a label-free size-generalization framework that adapts diffusion models trained on small instances to handle much larger instances without requiring optimal labels. ResizeCO combines Group Relative Policy Optimization (GRPO) using route length as a reward signal with a GPU-accelerated beam search formulation of k-opt. Experiments on TSP and CVRP instances with up to 10,000 nodes demonstrate that ResizeCO establishes a new state-of-the-art Pareto front for route quality versus computation time."
resource: "https://arxiv.org/abs/2610.17192"
tags:
  - "combinatorial-optimization"
  - "neural-routing-solver"
  - "reinforcement-learning"
timestamp: "2026-10-25T09:32:45Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Barak Itzchak Davidovitch"
  - literal: "Eli A. Meirom"
  - literal: "Ethan Fetaya"
  - literal: "Gal Chechik"
  - literal: "ResizeCO"
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
    description: "A label-free size-generalization approach that adapts diffusion models trained on small routing instances to much larger instances using reinforcement learning."
datasets:
  []
open_questions:
  - name: "size-generalization-neural-co-solvers"
    description: "The paper notes that current supervised and reinforcement learning approaches for routing problems like TSP and CVRP often fail at out-of-distribution size generalization due to shifts in statistical properties and exploding search spaces. Future work and open challenges involve developing scalable architectures and label-free fine-tuning paradigms that can robustly scale neural combinatorial optimization solvers to massive instance sizes without requiring costly optimal ground-truth labels."
skill: "GeneralMLSkill"
processed_at: "2026-10-25T09:32:45Z"
created_at: "2026-10-25T09:32:45Z"
---

# Size Generalization for Diffusion Routing Solvers

**Authors**: Barak Itzchak Davidovitch, Eli A. Meirom, Ethan Fetaya, Gal Chechik, ResizeCO
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.17192](https://arxiv.org/abs/2610.17192)

## Summary

Routing problems like the Traveling Salesman Problem (TSP) and Capacitated Vehicle Routing Problem (CVRP) are NP-hard and challenging to scale. This paper introduces ResizeCO, a label-free size-generalization framework that adapts diffusion models trained on small instances to handle much larger instances without requiring optimal labels. ResizeCO combines Group Relative Policy Optimization (GRPO) using route length as a reward signal with a GPU-accelerated beam search formulation of k-opt. Experiments on TSP and CVRP instances with up to 10,000 nodes demonstrate that ResizeCO establishes a new state-of-the-art Pareto front for route quality versus computation time.

## Key Contributions

- Proposes ResizeCO, a label-free size-generalization framework for diffusion-based routing solvers that adapts models trained on small instances to large instances.
- Applies Group Relative Policy Optimization (GRPO) using route length as the training signal for large-scale instances.
- Formulates k-opt as a GPU-accelerated beam search to address computational challenges in large-scale routing.
- Achieves a Pareto front over route quality and time dominating existing learned solvers and sets a new state of the art on TSP and CVRP instances with up to 10000 nodes.

## Open Questions & Future Work

- [[size-generalization-neural-co-solvers]]

## Key Concepts

- [[resizeco]]: A label-free size-generalization approach that adapts diffusion models trained on small routing instances to much larger instances using reinforcement learning.

## Archivist Review

Approved ResizeCO as the core methodological contribution since it already exists or matches vault conventions, and approved the open question on size generalization in neural routing solvers because it directly targets a fundamental bottleneck. All constraints on scarcity and anti-duplication were respected.

### Approved Concepts
- ResizeCO: ResizeCO is the central methodological contribution of the paper, introducing a label-free size-generalization framework for diffusion-based routing solvers using reinforcement learning.

### Approved Open Questions
- Size Generalization in Neural Routing Solvers: Size generalization is a central bottleneck in neural combinatorial optimization, limiting the practical deployment of learned solvers on real-world large-scale routing tasks.

## Links

- [Abstract](https://arxiv.org/abs/2610.17192)
- [PDF](https://arxiv.org/pdf/2610.17192)

