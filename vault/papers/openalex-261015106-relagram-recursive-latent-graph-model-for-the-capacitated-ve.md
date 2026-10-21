---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem"
description: "The paper introduces RELAGRAM, a novel recursive latent graph model that applies latent recursion via a compact transformer to solve the capacitated vehicle routing problem (CVRP). By recurrently updating edge token representations, RELAGRAM generates edge heatmaps for feasible solution decoding. Evaluated on CVRP instances, the 0.53M-parameter model achieves competitive gaps to PyVRP references and exhibits strong zero-shot generalization to larger scales (CVRP-500 and CVRP-1000)."
resource: "https://arxiv.org/abs/2610.15106"
tags:
  - "vehicle-routing-problem"
  - "neural-routing-solver"
  - "combinatorial-optimization"
timestamp: "2026-10-21T09:47:05Z"

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
    description: "A recursive latent graph model that repeatedly processes internal representations through a compact transformer for the capacitated vehicle routing problem."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-21T09:47:05Z"
created_at: "2026-10-21T09:47:05Z"
---

# RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem

**Authors**: Vladimir Kirill Bickov, Neil Yorke‐Smith
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15106](https://arxiv.org/abs/2610.15106)

## Summary

The paper introduces RELAGRAM, a novel recursive latent graph model that applies latent recursion via a compact transformer to solve the capacitated vehicle routing problem (CVRP). By recurrently updating edge token representations, RELAGRAM generates edge heatmaps for feasible solution decoding. Evaluated on CVRP instances, the 0.53M-parameter model achieves competitive gaps to PyVRP references and exhibits strong zero-shot generalization to larger scales (CVRP-500 and CVRP-1000).

## Key Contributions

- Introduces RELAGRAM, bringing latent recursion to graph combinatorial optimization for neural routing.
- Achieves small optimality gaps (8.3% on CVRP-100 under 256-candidate search) with a compact 0.53M-parameter model.
- Demonstrates zero-shot generalization to larger problem instances (CVRP-500 and CVRP-1000).

## Limitations

Optimality gaps increase when scaling zero-shot to larger instances like CVRP-1000 (21.7%).

## Key Concepts

- [[relagram]]: A recursive latent graph model that repeatedly processes internal representations through a compact transformer for the capacitated vehicle routing problem.

## Archivist Review

Approved RELAGRAM as a central standalone concept representing recursive latent graph modeling for combinatorial optimization. Rejected the open question candidate because it closely duplicates an existing vault question on reinforcement learning signal shaping for latent recursion.

### Approved Concepts
- RELAGRAM: Introduces latent recursion to graph combinatorial optimization and neural routing, demonstrating strong zero-shot generalization on CVRP instances.

### Rejected Candidates
- [open_question] Improving Reinforcement Learning for Latent Recursion (`reinforcement-learning-signal-for-latent-recursion`) - duplicate_existing: Too similar to existing vault open question reinforcement-learning-signal-shaping-for-latent-recursion.

## Links

- [Abstract](https://arxiv.org/abs/2610.15106)
- [PDF](https://arxiv.org/pdf/2610.15106)

