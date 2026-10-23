---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Size Generalization for Diffusion Routing Solvers"
description: "Diffusion models for routing problems often fail to generalize to larger problem instances outside their training distribution where optimal solutions are intractable. This paper introduces ResizeCO, a label-free size-generalization framework that uses reinforcement learning to adapt diffusion models trained on small instances to large-scale routing problems. By adapting GRPO with route length rewards and formulating k-opt as a GPU-accelerated beam search, ResizeCO sets a new state of the art on TSP and CVRP instances with up to 10,000 nodes."
resource: "https://arxiv.org/abs/2610.17192"
tags:
  - "machine-learning"
  - "neural-routing-solver"
  - "combinatorial-optimization"
timestamp: "2026-10-23T09:45:15Z"

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
    description: "A label-free size-generalization approach that uses reinforcement learning to adapt small-instance-trained diffusion models to large-scale routing problem instances."
datasets:
  []
open_questions:
  - name: "size-generalization-diffusion-routing-solvers"
    description: "Investigating how diffusion models and reinforcement learning routing solvers can better maintain robust zero-shot or fine-tuned size generalization on massive routing graphs (such as TSP and CVRP instances with over 10,000 nodes) without requiring prohibitively expensive optimal labels."
skill: "GeneralMLSkill"
processed_at: "2026-10-23T09:45:15Z"
created_at: "2026-10-23T09:45:15Z"
---

# Size Generalization for Diffusion Routing Solvers

**Authors**: Barak Itzchak Davidovitch, Eli A. Meirom, Ethan Fetaya, Gal Chechik
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.17192](https://arxiv.org/abs/2610.17192)

## Summary

Diffusion models for routing problems often fail to generalize to larger problem instances outside their training distribution where optimal solutions are intractable. This paper introduces ResizeCO, a label-free size-generalization framework that uses reinforcement learning to adapt diffusion models trained on small instances to large-scale routing problems. By adapting GRPO with route length rewards and formulating k-opt as a GPU-accelerated beam search, ResizeCO sets a new state of the art on TSP and CVRP instances with up to 10,000 nodes.

## Key Contributions

- Proposed ResizeCO, a label-free size-generalization approach that adapts diffusion models trained on small routing instances to large-scale instances using reinforcement learning.
- Adapted Group Relative Policy Optimization (GRPO) using route length as the training signal for large-scale routing instances.
- Formulated k-opt as a tree search and solved it via GPU-accelerated beam search.
- Achieved state-of-the-art performance on TSP and CVRP instances with up to 10000 nodes, dominating existing learned solvers on a Pareto front of route quality and inference time.

## Limitations

Not explicitly stated in the abstract, though reliance on reinforcement learning adaptation for scaling up diffusion models requires careful tuning.

## Open Questions & Future Work

- [[size-generalization-diffusion-routing-solvers]]

## Key Concepts

- [[resizeco]]: A label-free size-generalization approach that uses reinforcement learning to adapt small-instance-trained diffusion models to large-scale routing problem instances.

## Archivist Review

Approved the core concept 'resizeco' (reusing the existing vault slug 'resizeco') as it represents a distinct and reusable framework for label-free size generalization in diffusion routing solvers. Approved the open question 'size-generalization-diffusion-routing-solvers' (matching the existing vault slug) because scaling diffusion solvers across varying graph sizes is a key bottleneck. Rejected GRPO adaptation as a subcomponent of the broader framework.

### Approved Concepts
- ResizeCO: Central framework proposed by the paper for label-free size generalization in diffusion routing solvers using reinforcement learning.

### Approved Open Questions
- Size Generalization in Diffusion Solvers: Crucial for scaling neural combinatorial optimization to real-world, large-scale routing tasks where ground-truth optimal solutions are intractable to compute.

### Rejected Candidates
- [concept] GRPO for Routing Solvers (`grpo-for-routing`) - subcomponent_of_broader_mechanism: Application of GRPO to routing is a subcomponent of the broader ResizeCO framework rather than an independent concept.

## Links

- [Abstract](https://arxiv.org/abs/2610.17192)
- [PDF](https://arxiv.org/pdf/2610.17192)

