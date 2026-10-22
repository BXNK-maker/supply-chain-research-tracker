---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Size Generalization for Diffusion Routing Solvers"
description: "Routing problems like TSP and CVRP are computationally expensive for large instances, and existing diffusion solvers struggle to generalize to sizes beyond their training distribution without expensive optimal labels. To address this, the authors introduce ResizeCO, a label-free size-generalization approach that adapts diffusion models trained on small instances to large-scale instances using reinforcement learning (GRPO) and a GPU-accelerated beam search formulation of k-opt. Experiments on TSP and CVRP up to 10,000 nodes demonstrate that ResizeCO achieves a new state-of-the-art Pareto front balancing route quality and execution time."
resource: "https://arxiv.org/abs/2610.17192"
tags:
  - "vehicle-routing-problem"
  - "neural-routing-solver"
  - "combinatorial-optimization"
timestamp: "2026-10-22T09:49:12Z"

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
  - name: "size-generalization-diffusion-routing-solvers"
    description: "Investigate and develop methodologies that enable diffusion-based combinatorial optimization solvers to maintain solution quality and computational efficiency when scaling to substantially larger problem instances without requiring expensive supervised labels for those large instances."
skill: "GeneralMLSkill"
processed_at: "2026-10-22T09:49:12Z"
created_at: "2026-10-22T09:49:12Z"
---

# Size Generalization for Diffusion Routing Solvers

**Authors**: Barak Itzchak Davidovitch, Eli A. Meirom, Ethan Fetaya, Gal Chechik
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.17192](https://arxiv.org/abs/2610.17192)

## Summary

Routing problems like TSP and CVRP are computationally expensive for large instances, and existing diffusion solvers struggle to generalize to sizes beyond their training distribution without expensive optimal labels. To address this, the authors introduce ResizeCO, a label-free size-generalization approach that adapts diffusion models trained on small instances to large-scale instances using reinforcement learning (GRPO) and a GPU-accelerated beam search formulation of k-opt. Experiments on TSP and CVRP up to 10,000 nodes demonstrate that ResizeCO achieves a new state-of-the-art Pareto front balancing route quality and execution time.

## Key Contributions

- Proposes ResizeCO, a label-free size-generalization framework that adapts small-instance trained diffusion models to large-scale routing instances using reinforcement learning.
- Adapts GRPO for combinatorial optimization using route length as the training signal to handle distribution shifts in large instances.
- Formulates k-opt as a tree search accelerated via GPU-based beam search to address the computational challenge of large instances.
- Achieves a dominant Pareto front over route quality and inference time on TSP and CVRP instances up to 10,000 nodes, outperforming existing learned solvers.

## Open Questions & Future Work

- [[size-generalization-diffusion-routing-solvers]]

## Key Concepts

- [[resizeco]]: A label-free size-generalization approach for diffusion-based routing solvers using reinforcement learning and GPU-accelerated beam search.

## Archivist Review

Approved the core framework 'ResizeCO' and the open question regarding size generalization in diffusion-based combinatorial optimization solvers. Rejected 'GRPO' because it is an established external reinforcement learning algorithm.

### Approved Concepts
- ResizeCO: It is the core proposed framework combining reinforcement learning with diffusion models for size-generalization in routing problems.

### Approved Open Questions
- Size Generalization in Diffusion Routing Solvers: Size generalization is a primary bottleneck for deploying neural combinatorial optimization models in real-world large-scale routing applications.

### Rejected Candidates
- [concept] GRPO (`grpo`) - not_novel: GRPO is an existing reinforcement learning technique rather than a novel concept introduced by this paper.

## Links

- [Abstract](https://arxiv.org/abs/2610.17192)
- [PDF](https://arxiv.org/pdf/2610.17192)

