---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Size Generalization for Diffusion Routing Solvers"
description: "Routing problems like the Traveling Salesman Problem and Capacitated Vehicle Routing Problem are notoriously difficult to solve at scale, and existing diffusion solvers struggle to generalize to instance sizes outside their training distribution. This paper introduces ResizeCO, a label-free size-generalization approach that leverages reinforcement learning (adapting GRPO with route length as the training signal) alongside GPU-accelerated beam search for k-opt tree search. Experiments on TSP and CVRP instances with up to 10,000 nodes demonstrate that ResizeCO establishes a new state of the art, dominating existing learned solvers across the Pareto front of route quality and computation time."
resource: "https://arxiv.org/abs/2610.17192"
tags:
  - "neural-routing-solver"
  - "combinatorial-optimization"
  - "discrete-diffusion"
  - "vehicle-routing-problem"
  - "machine-learning"
timestamp: "2026-10-18T09:17:41Z"

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
    description: "A label-free size-generalization approach that uses reinforcement learning to adapt small-scale trained diffusion models to large-scale routing instances."
datasets:
  []
open_questions:
  - name: "diffusion-solver-size-generalization"
    description: "Investigate and develop principled methods for improving out-of-distribution size generalization in diffusion-based routing solvers (such as TSP and CVRP) without requiring expensive ground-truth optimal solutions for large-scale problem instances. This involves exploring whether reinforcement learning fine-tuning, specialized graph neural network inductive biases, or parallelized local search heuristics can reliably scale model performance to instances with magnitudes larger node counts (e.g., 10,000+ nodes) while maintaining strict Pareto optimality over solution quality and inference time."
skill: "GeneralMLSkill"
processed_at: "2026-10-18T09:17:41Z"
created_at: "2026-10-18T09:17:41Z"
---

# Size Generalization for Diffusion Routing Solvers

**Authors**: Barak Itzchak Davidovitch, Eli A. Meirom, Ethan Fetaya, Gal Chechik
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.17192](https://arxiv.org/abs/2610.17192)

## Summary

Routing problems like the Traveling Salesman Problem and Capacitated Vehicle Routing Problem are notoriously difficult to solve at scale, and existing diffusion solvers struggle to generalize to instance sizes outside their training distribution. This paper introduces ResizeCO, a label-free size-generalization approach that leverages reinforcement learning (adapting GRPO with route length as the training signal) alongside GPU-accelerated beam search for k-opt tree search. Experiments on TSP and CVRP instances with up to 10,000 nodes demonstrate that ResizeCO establishes a new state of the art, dominating existing learned solvers across the Pareto front of route quality and computation time.

## Key Contributions

- Introduces ResizeCO, a label-free size-generalization approach adapting diffusion models trained on small routing instances to large-scale instances using reinforcement learning.
- Adapts Group Relative Policy Optimization (GRPO) using route length as the training signal to handle the statistical shifts in larger routing instances.
- Formulates k-opt as a tree search solved via GPU-accelerated beam search for efficient large-scale routing inference.
- Achieves state-of-the-art Pareto fronts over route quality and execution time on TSP and CVRP instances with up to 10000 nodes.

## Open Questions & Future Work

- [[diffusion-solver-size-generalization]]

## Key Concepts

- [[resizeco]]: A label-free size-generalization approach that uses reinforcement learning to adapt small-scale trained diffusion models to large-scale routing instances.

## Archivist Review

Approved the core concept ResizeCO as it represents a distinct method for size-generalization in combinatorial optimization, and approved the open question on diffusion solver size generalization as it addresses a fundamental roadblock in scaling generative models to large NP-hard instances. No datasets were approved because none were explicitly named as distinct benchmark datasets.

### Approved Concepts
- ResizeCO: Central novel framework introduced in the paper for size-generalization in diffusion-based combinatorial optimization routing solvers.

### Approved Open Questions
- Size Generalization in Diffusion Routing Solvers: Size generalization remains one of the fundamental roadblocks in applying deep learning and generative models to NP-hard combinatorial optimization, as models trained on small graphs typically collapse or perform poorly on larger instances.

## Links

- [Abstract](https://arxiv.org/abs/2610.17192)
- [PDF](https://arxiv.org/pdf/2610.17192)

