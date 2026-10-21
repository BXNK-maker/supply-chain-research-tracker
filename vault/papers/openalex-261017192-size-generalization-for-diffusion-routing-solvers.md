---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Size Generalization for Diffusion Routing Solvers"
description: "Routing problems like TSP and CVRP are computationally expensive for large instances, and existing diffusion-based solvers fail to generalize to sizes beyond their training distribution. This paper introduces ResizeCO, a label-free size-generalization approach that uses reinforcement learning (adapting GRPO with route length signals) and a GPU-accelerated beam search for k-opt tree search to adapt small-instance diffusion models. Evaluated on TSP and CVRP instances with up to 10,000 nodes, ResizeCO sets a new state of the art by achieving a dominant Pareto front over route quality and solving time."
resource: "https://arxiv.org/abs/2610.17192"
tags:
  - "neural-routing-solver"
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-21T09:47:54Z"

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
    description: "A label-free size-generalization approach that adapts small-instance diffusion routing solvers to large-scale instances using reinforcement learning and GPU-accelerated beam search."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-21T09:47:54Z"
created_at: "2026-10-21T09:47:54Z"
---

# Size Generalization for Diffusion Routing Solvers

**Authors**: Barak Itzchak Davidovitch, Eli A. Meirom, Ethan Fetaya, Gal Chechik
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.17192](https://arxiv.org/abs/2610.17192)

## Summary

Routing problems like TSP and CVRP are computationally expensive for large instances, and existing diffusion-based solvers fail to generalize to sizes beyond their training distribution. This paper introduces ResizeCO, a label-free size-generalization approach that uses reinforcement learning (adapting GRPO with route length signals) and a GPU-accelerated beam search for k-opt tree search to adapt small-instance diffusion models. Evaluated on TSP and CVRP instances with up to 10,000 nodes, ResizeCO sets a new state of the art by achieving a dominant Pareto front over route quality and solving time.

## Key Contributions

- Introduces ResizeCO, a label-free size-generalization framework that adapts diffusion models trained on small routing problem instances to large-scale instances using reinforcement learning.
- Adapts GRPO for combinatorial optimization using route length as the training signal to handle distribution shifts in large instances.
- Formulates k-opt as a tree search solved via GPU-accelerated beam search for efficient decoding.
- Achieves a Pareto front over route quality and solving time dominating existing learned solvers on TSP and CVRP instances with up to 10000 nodes.

## Key Concepts

- [[resizeco]]: A label-free size-generalization approach that adapts small-instance diffusion routing solvers to large-scale instances using reinforcement learning and GPU-accelerated beam search.

## Archivist Review

Approved ResizeCO as a distinct concept, but rejected the open question because an identical question (size-generalization-diffusion-routing) already exists in the vault. No datasets qualified.

### Approved Concepts
- ResizeCO: It introduces a novel label-free size-generalization framework combining reinforcement learning with diffusion-based routing solvers to handle instances up to 10000 nodes.

### Rejected Candidates
- [open_question] Size Generalization for Diffusion Routing Solvers (`size-generalization-diffusion-routing`) - duplicate_existing: Duplicate of existing open question in the vault (size-generalization-diffusion-routing).

## Links

- [Abstract](https://arxiv.org/abs/2610.17192)
- [PDF](https://arxiv.org/pdf/2610.17192)

