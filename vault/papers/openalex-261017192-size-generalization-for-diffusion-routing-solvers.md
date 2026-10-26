---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Size Generalization for Diffusion Routing Solvers"
description: "Routing problems like TSP and CVRP are computationally expensive to solve for large instances, and existing diffusion-based solvers fail to generalize to instance sizes outside their training distribution. This paper introduces ResizeCO, a label-free size-generalization approach that adapts a diffusion model trained on small instances to large-scale instances using reinforcement learning and GPU-accelerated beam search. Evaluated on TSP and CVRP instances with up to 10,000 nodes, ResizeCO sets a new state of the art by achieving a Pareto front over route quality and time that dominates existing learned solvers."
resource: "https://arxiv.org/abs/2610.17192"
tags:
  - "combinatorial-optimization"
  - "reinforcement-learning"
  - "vehicle-routing-problem"
  - "time-series"
timestamp: "2026-10-26T10:42:49Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Barak Itzchak Davidovitch"
  - literal: "Eli A. Meirom"
  - literal: "Ethan Fetaya"
  - literal: "Gal Chechik"
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
    description: "A label-free size-generalization approach for diffusion-based routing solvers that adapts models trained on small instances to large-scale instances via reinforcement learning and GPU beam search."
datasets:
  []
open_questions:
  - name: "label-free-size-generalization-routing-solvers"
    description: "Investigate how to eliminate the reliance on expensive ground-truth optimal labels or reinforcement learning fine-tuning for scaling neural routing solvers to extremely large out-of-distribution instance sizes, or whether alternative self-training and label-free paradigms can entirely bridge the zero-shot size generalization gap without performance degradation."
skill: "GeneralMLSkill"
processed_at: "2026-10-26T10:42:49Z"
created_at: "2026-10-26T10:42:49Z"
---

# Size Generalization for Diffusion Routing Solvers

**Authors**: Barak Itzchak Davidovitch, Eli A. Meirom, Ethan Fetaya, Gal Chechik, Barak Itzchak Davidovitch, Eli A. Meirom, Ethan Fetaya, Gal Chechik
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.17192](https://arxiv.org/abs/2610.17192)

## Summary

Routing problems like TSP and CVRP are computationally expensive to solve for large instances, and existing diffusion-based solvers fail to generalize to instance sizes outside their training distribution. This paper introduces ResizeCO, a label-free size-generalization approach that adapts a diffusion model trained on small instances to large-scale instances using reinforcement learning and GPU-accelerated beam search. Evaluated on TSP and CVRP instances with up to 10,000 nodes, ResizeCO sets a new state of the art by achieving a Pareto front over route quality and time that dominates existing learned solvers.

## Key Contributions

- Introduces ResizeCO, a label-free size-generalization approach for diffusion-based routing solvers using reinforcement learning to adapt models trained on small instances.
- Formulates k-opt as a tree search solved via GPU-accelerated beam search.
- Achieves a Pareto front over route quality and time dominating existing learned solvers on TSP and CVRP instances with up to 10000 nodes.

## Open Questions & Future Work

- [[label-free-size-generalization-routing-solvers]]

## Key Concepts

- [[resizeco]]: A label-free size-generalization approach for diffusion-based routing solvers that adapts models trained on small instances to large-scale instances via reinforcement learning and GPU beam search.

## Archivist Review

Approved the core concept ResizeCO as a novel label-free size-generalization framework for diffusion-based routing solvers, alongside an open question addressing label-free size generalization in combinatorial optimization. Both items meet the strict threshold for vault retention and distinct long-term value.

### Approved Concepts
- ResizeCO: Introduces a label-free size-generalization approach for diffusion-based routing solvers using reinforcement learning and GPU-accelerated beam search.

### Approved Open Questions
- Label-Free Size Generalization in Routing: Size generalization remains one of the fundamental bottlenecks in neural combinatorial optimization, limiting the applicability of deep learning models to large-scale real-world routing instances where optimal solutions are computationally infeasible to generate.

## Links

- [Abstract](https://arxiv.org/abs/2610.17192)
- [PDF](https://arxiv.org/pdf/2610.17192)

