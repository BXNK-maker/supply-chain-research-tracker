---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Size Generalization for Diffusion Routing Solvers"
description: "This paper introduces ResizeCO, a label-free size-generalization approach for diffusion-based routing solvers that adapts models trained on small instances to solve large-scale Traveling Salesman and Capacitated Vehicle Routing problems. By combining reinforcement learning (adapting GRPO with route length signals) and a GPU-accelerated beam search formulation of k-opt, ResizeCO achieves state-of-the-art performance on instances with up to 10,000 nodes."
resource: "https://arxiv.org/abs/2610.17192"
tags:
  - "combinatorial-optimization"
  - "machine-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-16T09:32:12Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Barak Itzchak Davidovitch"
  - literal: "Eli A. Meirom"
  - literal: "Ethan Fetaya"
  - literal: "Gal Chechik"
  - literal: "Barak Itzchak Davidovitch"
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
    description: "A label-free size-generalization approach for diffusion-based routing solvers that adapts models trained on small instances to large-scale problems using reinforcement learning."
datasets:
  []
open_questions:
  - name: "size-generalization-diffusion-solvers"
    description: "Investigate and develop principled multi-stage reinforcement learning curricula or meta-learning adaptation strategies that allow diffusion-based combinatorial optimization solvers to scale effectively from small training distributions to extremely large instance sizes (e.g., beyond 10,000 nodes) without encountering performance degradation or excessive compute costs."
skill: "GeneralMLSkill"
processed_at: "2026-10-16T09:32:12Z"
created_at: "2026-10-16T09:32:12Z"
---

# Size Generalization for Diffusion Routing Solvers

**Authors**: Barak Itzchak Davidovitch, Eli A. Meirom, Ethan Fetaya, Gal Chechik, Barak Itzchak Davidovitch
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.17192](https://arxiv.org/abs/2610.17192)

## Summary

This paper introduces ResizeCO, a label-free size-generalization approach for diffusion-based routing solvers that adapts models trained on small instances to solve large-scale Traveling Salesman and Capacitated Vehicle Routing problems. By combining reinforcement learning (adapting GRPO with route length signals) and a GPU-accelerated beam search formulation of k-opt, ResizeCO achieves state-of-the-art performance on instances with up to 10,000 nodes.

## Key Contributions

- Proposed ResizeCO, a label-free size-generalization framework that adapts diffusion models trained on small routing problem instances to much larger scales using reinforcement learning.
- Adapted Group Relative Policy Optimization (GRPO) using route length as the training signal for large-scale combinatorial optimization instances.
- Formulated k-opt as a GPU-accelerated beam search tree search to address computational challenges in large-scale routing.
- Achieved a dominant Pareto front over route quality and solve time on TSP and CVRP instances with up to 10000 nodes, outperforming existing learned and traditional solvers at short run times.

## Limitations

Relies on pre-training diffusion models on smaller instances and requires careful tuning of reinforcement learning adaptation and GPU-accelerated tree search parameters for extreme scales.

## Open Questions & Future Work

- [[size-generalization-diffusion-solvers]]

## Key Concepts

- [[resizeco]]: A label-free size-generalization approach for diffusion-based routing solvers that adapts models trained on small instances to large-scale problems using reinforcement learning.

## Archivist Review

Approved ResizeCO as a highly specific, reusable framework for adapting diffusion solvers across problem scales, along with the fundamental open question of size generalization in diffusion routing solvers. GRPO was correctly rejected as an existing policy optimization technique.

### Approved Concepts
- ResizeCO: Introduces a novel label-free size-generalization framework for diffusion-based routing solvers using reinforcement learning and GPU-accelerated tree search.

### Approved Open Questions
- Size Generalization in Diffusion Routing Solvers: Size generalization remains a fundamental bottleneck in applying neural combinatorial optimization solvers to real-world large-scale routing tasks, as supervised models trained on small instances typically break down on larger instances.

### Rejected Candidates
- [concept] Group Relative Policy Optimization (`grpo`) - not_novel: GRPO is an existing RL algorithm rather than a novel concept introduced by this paper.

## Links

- [Abstract](https://arxiv.org/abs/2610.17192)
- [PDF](https://arxiv.org/pdf/2610.17192)

