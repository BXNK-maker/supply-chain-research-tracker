---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Size Generalization for Diffusion Routing Solvers"
description: "This paper introduces ResizeCO, a label-free size-generalization framework designed to adapt diffusion-based routing solvers trained on small combinatorial optimization instances to much larger scales. By combining reinforcement learning (adapting GRPO with route length as the reward signal) and a GPU-accelerated beam search formulation of k-opt, ResizeCO overcomes the distribution shift and computational bottlenecks of large instances. Experiments on TSP and CVRP with up to 10,000 nodes show that ResizeCO sets a new state of the art, achieving a superior Pareto front over route quality and solving time compared to existing learned solvers."
resource: "https://arxiv.org/abs/2610.17192"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-17T08:59:01Z"

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
    description: "A label-free size-generalization framework for diffusion-based routing solvers that adapts models trained on small instances to large-scale instances using reinforcement learning."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-17T08:59:01Z"
created_at: "2026-10-17T08:59:01Z"
---

# Size Generalization for Diffusion Routing Solvers

**Authors**: Barak Itzchak Davidovitch, Eli A. Meirom, Ethan Fetaya, Gal Chechik
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.17192](https://arxiv.org/abs/2610.17192)

## Summary

This paper introduces ResizeCO, a label-free size-generalization framework designed to adapt diffusion-based routing solvers trained on small combinatorial optimization instances to much larger scales. By combining reinforcement learning (adapting GRPO with route length as the reward signal) and a GPU-accelerated beam search formulation of k-opt, ResizeCO overcomes the distribution shift and computational bottlenecks of large instances. Experiments on TSP and CVRP with up to 10,000 nodes show that ResizeCO sets a new state of the art, achieving a superior Pareto front over route quality and solving time compared to existing learned solvers.

## Key Contributions

- Proposes ResizeCO, a label-free size-generalization approach for diffusion-based routing solvers that adapts models trained on small instances to large-scale instances using reinforcement learning.
- Adapts GRPO for combinatorial optimization problems using route length as the training signal.
- Formulates k-opt as a tree search solved via GPU-accelerated beam search.
- Achieves a dominant Pareto front over route quality and inference time on TSP and CVRP instances with up to 10,000 nodes, outperforming existing learned solvers.

## Limitations

Relies on reinforcement learning adaptation from smaller instances and requires GPU-accelerated beam search for k-opt tree search, which may still incur computational overhead for extremely large instances.

## Key Concepts

- [[resizeco]]: A label-free size-generalization framework for diffusion-based routing solvers that adapts models trained on small instances to large-scale instances using reinforcement learning.

## Archivist Review

We approved the core concept 'ResizeCO' as a novel framework note. The open question candidate was rejected due to duplication with existing vault entries on diffusion solver size generalization, and datasets were omitted as TSP/CVRP are standard problem domains rather than specific dataset assets.

### Approved Concepts
- ResizeCO: ResizeCO is the central methodological contribution of the paper, providing a novel label-free size-generalization approach for diffusion-based routing solvers using reinforcement learning.

### Rejected Candidates
- [open_question] Size Generalization in Diffusion Solvers (`size-generalization-in-diffusion-solverss`) - duplicate_existing: This open question is near-duplicate or structurally overlapping with existing vault entry size-generalization-diffusion-solvers.

## Links

- [Abstract](https://arxiv.org/abs/2610.17192)
- [PDF](https://arxiv.org/pdf/2610.17192)

