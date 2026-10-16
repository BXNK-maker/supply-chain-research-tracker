---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem"
description: "The paper introduces RELAGRAM (Recursive Latent Graph Model), which adapts latent recursion for graph combinatorial optimization by recurrently updating edge token representations using a compact transformer. Evaluated on the capacitated vehicle routing problem (CVRP), RELAGRAM achieves competitive performance on CVRP-100 and exhibits strong zero-shot generalization to larger instances such as CVRP-500 and CVRP-1000."
resource: "https://arxiv.org/abs/2610.15106"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-16T09:27:54Z"

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
    description: "Recursive Latent Graph Model is a neural routing architecture that recurrently updates latent representations of edge tokens to solve the capacitated vehicle routing problem."
datasets:
  []
open_questions:
  - name: "reinforcement-learning-signal-shaping-for-latent-recursion"
    description: "Investigate advanced reinforcement learning signal shaping and credit assignment strategies tailored for latent-recursive models in graph combinatorial optimization, addressing the limitations of sparse rewards on internal latent states like the answer and workspace representations."
skill: "GeneralMLSkill"
processed_at: "2026-10-16T09:27:54Z"
created_at: "2026-10-16T09:27:54Z"
---

# RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem

**Authors**: Vladimir Kirill Bickov, Neil Yorke‐Smith
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15106](https://arxiv.org/abs/2610.15106)

## Summary

The paper introduces RELAGRAM (Recursive Latent Graph Model), which adapts latent recursion for graph combinatorial optimization by recurrently updating edge token representations using a compact transformer. Evaluated on the capacitated vehicle routing problem (CVRP), RELAGRAM achieves competitive performance on CVRP-100 and exhibits strong zero-shot generalization to larger instances such as CVRP-500 and CVRP-1000.

## Key Contributions

- Introduces RELAGRAM, a recursive latent graph model applying latent recursion to graph combinatorial optimization tasks like the capacitated vehicle routing problem (CVRP).
- Achieves gaps to PyVRP reference of 13.4% (greedy), 9.8% (eightfold symmetry augmentation), and 8.3% (256-candidate search) on CVRP-100 instances with only 0.53M parameters.
- Demonstrates zero-shot generalization from CVRP-100 training instances to larger instances (CVRP-500 and CVRP-1000), achieving gaps of 15.6% and 21.7% under 256-candidate search.

## Limitations

The paper evaluates zero-shot generalization up to CVRP-1000 and reports performance gaps relative to PyVRP, but does not explore alternative combinatorial optimization problems beyond CVRP.

## Open Questions & Future Work

- [[reinforcement-learning-signal-shaping-for-latent-recursion]]

## Key Concepts

- [[relagram]]: Recursive Latent Graph Model is a neural routing architecture that recurrently updates latent representations of edge tokens to solve the capacitated vehicle routing problem.

## Archivist Review

Approved RELAGRAM as a novel and reusable architecture for graph combinatorial optimization, along with the open question regarding reinforcement learning signal shaping for latent recursion. Rejected 'latent recursion' as a standalone concept because it is a broader mechanism adapted from prior literature. No standalone named datasets qualify for vault inclusion.

### Approved Concepts
- RELAGRAM: It introduces latent recursion to graph combinatorial optimization, serving as the core model architecture for the paper.

### Approved Open Questions
- RL Signal Shaping for Latent Recursion: Because latent-recursive models pass internal latent states rather than complete candidate solutions across steps, standard RL algorithms suffer from weak or indirect supervision signals on these intermediate states, posing a fundamental hurdle for scaling reinforcement learning in combinatorial optimization.

### Rejected Candidates
- [concept] Latent Recursion (`latent-recursion`) - subcomponent_of_broader_mechanism: Latent recursion is a general machine learning mechanism discussed in prior work; the paper's specific contribution is its integration into graph combinatorial optimization via RELAGRAM.

## Links

- [Abstract](https://arxiv.org/abs/2610.15106)
- [PDF](https://arxiv.org/pdf/2610.15106)

