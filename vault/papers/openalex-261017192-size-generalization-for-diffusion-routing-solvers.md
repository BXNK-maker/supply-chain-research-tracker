---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Size Generalization for Diffusion Routing Solvers"
description: "This paper introduces ResizeCO, a label-free size-generalization framework that adapts small-instance diffusion routing solvers to large instances (up to 10,000 nodes) via reinforcement learning (GRPO) and GPU-accelerated beam search for k-opt. ResizeCO eliminates the need for expensive optimal labels on large instances, outperforming existing learned and traditional solvers to establish a new state-of-the-art Pareto front on TSP and CVRP."
resource: "https://arxiv.org/abs/2610.17192"
tags:
  - "reinforcement-learning"
  - "vehicle-routing-problem"
  - "neural-routing-solver"
  - "combinatorial-optimization"
timestamp: "2026-10-24T09:16:38Z"

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
    description: "A label-free size-generalization approach using reinforcement learning to adapt small-instance diffusion models to large routing problem instances."
datasets:
  []
open_questions:
  - name: "size-generalization-diffusion-routing-solvers"
    description: "Future research needs to determine how label-free reinforcement learning approaches like GRPO and structure-aware architectures can be further scaled to systematically generalize across drastically wider instance size disparities (such as from small graphs to extremely large-scale routing instances with tens of thousands of nodes) without requiring costly ground-truth optimal labels."
skill: "GeneralMLSkill"
processed_at: "2026-10-24T09:16:38Z"
created_at: "2026-10-24T09:16:38Z"
---

# Size Generalization for Diffusion Routing Solvers

**Authors**: Barak Itzchak Davidovitch, Eli A. Meirom, Ethan Fetaya, Gal Chechik
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.17192](https://arxiv.org/abs/2610.17192)

## Summary

This paper introduces ResizeCO, a label-free size-generalization framework that adapts small-instance diffusion routing solvers to large instances (up to 10,000 nodes) via reinforcement learning (GRPO) and GPU-accelerated beam search for k-opt. ResizeCO eliminates the need for expensive optimal labels on large instances, outperforming existing learned and traditional solvers to establish a new state-of-the-art Pareto front on TSP and CVRP.

## Key Contributions

- Proposes ResizeCO, a label-free size-generalization approach for diffusion-based routing solvers using reinforcement learning (adapted GRPO) with route length as the training signal.
- Formulates k-opt as a tree search solved via GPU-based beam search to address computational challenges on large instances.
- Demonstrates state-of-the-art Pareto fronts over route quality and execution time on TSP and CVRP instances with up to 10,000 nodes.

## Open Questions & Future Work

- [[size-generalization-diffusion-routing-solvers]]

## Key Concepts

- [[resizeco]]: A label-free size-generalization approach using reinforcement learning to adapt small-instance diffusion models to large routing problem instances.

## Archivist Review

Approved the core framework concept 'resizeco' which is already present in the vault or matches the exact newly introduced method, and reused/aligned the open question with 'size-generalization-diffusion-routing-solvers' already tracked in the vault. No other candidates met the strict novelty or scarcity standards.

### Approved Concepts
- ResizeCO: Central contribution of the paper, enabling size-generalization for diffusion routing solvers to large-scale instances without requiring optimal labels.

### Approved Open Questions
- Size Generalization for Diffusion Routing Solvers: Size generalization remains a fundamental bottleneck in applying generative and diffusion models to large-scale NP-hard combinatorial optimization problems.

## Links

- [Abstract](https://arxiv.org/abs/2610.17192)
- [PDF](https://arxiv.org/pdf/2610.17192)

