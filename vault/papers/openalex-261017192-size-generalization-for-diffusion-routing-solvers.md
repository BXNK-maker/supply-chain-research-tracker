---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Size Generalization for Diffusion Routing Solvers"
description: "Routing problems like TSP and CVRP are computationally expensive to solve at scale, and existing diffusion-based neural solvers struggle to generalize to instance sizes outside their training distribution. To address this, the authors propose ResizeCO, a label-free size-generalization framework that uses reinforcement learning to adapt small-instance-trained diffusion models to larger graphs without requiring optimal supervision labels. Furthermore, the approach formulates k-opt as a GPU-accelerated beam search tree search, establishing a new state of the art on TSP and CVRP instances with up to 10,000 nodes."
resource: "https://arxiv.org/abs/2610.17192"
tags:
  - "neural-routing-solver"
  - "discrete-diffusion"
  - "machine-learning"
  - "combinatorial-optimization"
timestamp: "2026-10-19T10:27:51Z"

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
    description: "A label-free size-generalization approach using reinforcement learning to adapt diffusion-based routing solvers trained on small instances to large-scale problem instances up to 10000 nodes."
datasets:
  []
open_questions:
  - name: "size-generalization-diffusion-routing"
    description: "Investigate mechanisms for enabling diffusion-based routing solvers to robustly generalize to instance sizes significantly larger than their training distribution (such as scaling from 100 to 10,000 nodes) without requiring costly ground-truth optimal labels for the large instances."
skill: "GeneralMLSkill"
processed_at: "2026-10-19T10:27:51Z"
created_at: "2026-10-19T10:27:51Z"
---

# Size Generalization for Diffusion Routing Solvers

**Authors**: Barak Itzchak Davidovitch, Eli A. Meirom, Ethan Fetaya, Gal Chechik
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.17192](https://arxiv.org/abs/2610.17192)

## Summary

Routing problems like TSP and CVRP are computationally expensive to solve at scale, and existing diffusion-based neural solvers struggle to generalize to instance sizes outside their training distribution. To address this, the authors propose ResizeCO, a label-free size-generalization framework that uses reinforcement learning to adapt small-instance-trained diffusion models to larger graphs without requiring optimal supervision labels. Furthermore, the approach formulates k-opt as a GPU-accelerated beam search tree search, establishing a new state of the art on TSP and CVRP instances with up to 10,000 nodes.

## Key Contributions

- Proposed ResizeCO, a label-free size-generalization approach that adapts diffusion models trained on small routing instances to larger problem scales using reinforcement learning.
- Formulated k-opt as a tree search solved via GPU-accelerated beam search for efficient decoding.
- Achieved a Pareto front over route quality and time dominating existing learned solvers and outperforming other solvers on large TSP and CVRP instances with up to 10000 nodes.

## Open Questions & Future Work

- [[size-generalization-diffusion-routing]]

## Key Concepts

- [[resizeco]]: A label-free size-generalization approach using reinforcement learning to adapt diffusion-based routing solvers trained on small instances to large-scale problem instances up to 10000 nodes.

## Archivist Review

Approved ResizeCO and the corresponding open question on size generalization for diffusion routing solvers as they represent core methodological contributions and significant open challenges in neural combinatorial optimization.

### Approved Concepts
- ResizeCO: Introduces a novel label-free size-generalization framework combining reinforcement learning and diffusion models for routing problems.

### Approved Open Questions
- Size Generalization for Diffusion Routing Solvers: Size generalization is a central bottleneck in neural combinatorial optimization, limiting the practical deployment of learned heuristics on massive real-world graphs.

## Links

- [Abstract](https://arxiv.org/abs/2610.17192)
- [PDF](https://arxiv.org/pdf/2610.17192)

