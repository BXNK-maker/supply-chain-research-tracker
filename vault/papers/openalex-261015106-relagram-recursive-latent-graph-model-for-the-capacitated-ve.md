---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem"
description: "The paper introduces RELAGRAM, a recursive latent graph model that applies latent recursion to graph combinatorial optimization for the capacitated vehicle routing problem. By repeatedly updating edge token representations through a compact transformer, RELAGRAM constructs edge heatmaps and feasible solutions via an autoregressive decoder. Evaluated on CVRP-100, the 0.53M-parameter model achieves strong performance compared to PyVRP references and demonstrates zero-shot generalization to larger CVRP-500 and CVRP-1000 instances."
resource: "https://arxiv.org/abs/2610.15106"
tags:
  - "vehicle-routing-problem"
  - "neural-routing-solver"
  - "combinatorial-optimization"
timestamp: "2026-10-22T09:46:45Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Vladimir Kirill Bickov"
  - literal: "Neil Yorke‐Smith"
issued:
  date-parts:
    - [2026, 10, 10]

# Domain-specific custom fields
paper_id: "2610.15106"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "relagram"
    description: "A recursive latent graph model that brings latent recursion to graph combinatorial optimization for the capacitated vehicle routing problem."
datasets:
  []
open_questions:
  - name: "reinforcement-learning-signals-latent-recursion"
    description: "Investigate advanced reinforcement learning training objectives and credit assignment mechanisms tailored specifically for latent-recursive graph models to address sparse reward signals and indirect supervision of answer and workspace states."
skill: "GeneralMLSkill"
processed_at: "2026-10-22T09:46:45Z"
created_at: "2026-10-22T09:46:45Z"
---

# RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem

**Authors**: Vladimir Kirill Bickov, Neil Yorke‐Smith
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15106](https://arxiv.org/abs/2610.15106)

## Summary

The paper introduces RELAGRAM, a recursive latent graph model that applies latent recursion to graph combinatorial optimization for the capacitated vehicle routing problem. By repeatedly updating edge token representations through a compact transformer, RELAGRAM constructs edge heatmaps and feasible solutions via an autoregressive decoder. Evaluated on CVRP-100, the 0.53M-parameter model achieves strong performance compared to PyVRP references and demonstrates zero-shot generalization to larger CVRP-500 and CVRP-1000 instances.

## Key Contributions

- Introduced RELAGRAM, a recursive latent graph model that brings latent recursion to graph combinatorial optimization via edge token updates.
- Achieved competitive optimality gaps on CVRP-100 instances (8.3% gap to PyVRP under 256-candidate search with only 0.53M parameters).
- Demonstrated zero-shot generalization from CVRP-100 training to larger problem instances CVRP-500 and CVRP-1000.

## Limitations

Evaluation focuses primarily on CVRP instances up to size 1000; generalization to broader vehicle routing variants remains to be explored.

## Open Questions & Future Work

- [[reinforcement-learning-signals-latent-recursion]]

## Key Concepts

- [[relagram]]: A recursive latent graph model that brings latent recursion to graph combinatorial optimization for the capacitated vehicle routing problem.

## Archivist Review

Approved RELAGRAM as a distinctive concept representing latent recursion applied to combinatorial optimization on graphs, and approved the open question regarding reinforcement learning signals for latent recursion. Datasets like CVRP are standard task families and were rejected as routine benchmarks.

### Approved Concepts
- RELAGRAM: Introduces latent recursion to graph combinatorial optimization for vehicle routing problems, combining a compact transformer with recursive latent updates.

### Approved Open Questions
- RL Signal Engineering for Latent Recursion: Sparse reinforcement learning signals and indirect supervision of latent states remain fundamental bottlenecks for training deep recursive neural models on combinatorial optimization tasks.

## Links

- [Abstract](https://arxiv.org/abs/2610.15106)
- [PDF](https://arxiv.org/pdf/2610.15106)

