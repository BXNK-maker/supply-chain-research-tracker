---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem"
description: "The paper introduces RELAGRAM (Recursive Latent Graph Model), which adapts latent recursion to graph combinatorial optimization by recurrently updating edge tokens through a compact transformer. Evaluated on the Capacitated Vehicle Routing Problem (CVRP), a 0.53M-parameter RELAGRAM trained only on CVRP-100 achieves competitive optimality gaps and demonstrates zero-shot generalization to larger problem instances like CVRP-500 and CVRP-1000. These results establish latent recursion as a viable and parameter-efficient approach for neural routing."
resource: "https://arxiv.org/abs/2610.15106"
tags:
  - "vehicle-routing-problem"
  - "neural-routing-solver"
  - "combinatorial-optimization"
timestamp: "2026-10-18T09:16:51Z"

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
  - name: "reinforcement-learning-signal-shaping-for-latent-recursion"
    description: "Investigate advanced reinforcement learning formulations, credit assignment strategies, and architectural adaptations to overcome the limitations of sparse reinforcement learning signals when training latent-recursive neural models on routing problems."
skill: "GeneralMLSkill"
processed_at: "2026-10-18T09:16:51Z"
created_at: "2026-10-18T09:16:51Z"
---

# RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem

**Authors**: Vladimir Kirill Bickov, Neil Yorke‐Smith
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15106](https://arxiv.org/abs/2610.15106)

## Summary

The paper introduces RELAGRAM (Recursive Latent Graph Model), which adapts latent recursion to graph combinatorial optimization by recurrently updating edge tokens through a compact transformer. Evaluated on the Capacitated Vehicle Routing Problem (CVRP), a 0.53M-parameter RELAGRAM trained only on CVRP-100 achieves competitive optimality gaps and demonstrates zero-shot generalization to larger problem instances like CVRP-500 and CVRP-1000. These results establish latent recursion as a viable and parameter-efficient approach for neural routing.

## Key Contributions

- Introduced RELAGRAM, a recursive latent graph model that brings latent recursion to graph combinatorial optimization and neural routing.
- Achieved strong performance on CVRP-100 instances with a compact 0.53M-parameter model, reaching gaps to a PyVRP reference of 13.4% (greedy), 9.8% (symmetry augmentation), and 8.3% (256-candidate search).
- Demonstrated zero-shot generalization when trained only on CVRP-100 and evaluated on CVRP-500 and CVRP-1000, achieving gaps of 15.6% and 21.7% under 256-candidate search.

## Limitations

Evaluated primarily on CVRP instances; zero-shot generalization degrades as problem scale increases from CVRP-100 to CVRP-1000.

## Open Questions & Future Work

- [[reinforcement-learning-signal-shaping-for-latent-recursion]]

## Key Concepts

- [[relagram]]: A recursive latent graph model that brings latent recursion to graph combinatorial optimization for the capacitated vehicle routing problem.

## Archivist Review

Approved the central concept RELAGRAM because it introduces latent recursion to graph combinatorial optimization. Reused the existing canonical slug 'reinforcement-learning-signal-shaping-for-latent-recursion' for the open question since it captures the identical research direction already present in the vault. No datasets met the criteria for standalone notes.

### Approved Concepts
- RELAGRAM: Introduces latent recursion to neural routing and graph combinatorial optimization, demonstrating strong zero-shot generalization across scale.

### Approved Open Questions
- Reinforcement Learning for Latent Recursion: Addressing sparse credit assignment in latent recursive networks is crucial for enabling effective end-to-end training and unlocking the full potential of recursive reasoning in deep reinforcement learning for combinatorial optimization.

### Rejected Candidates
- [open_question] Reinforcement Learning for Latent Recursion (`reinforcement-learning-sparse-signals-latent-recursion`) - duplicate_existing: Near-duplicate of existing vault question 'reinforcement-learning-signal-shaping-for-latent-recursion'.

## Links

- [Abstract](https://arxiv.org/abs/2610.15106)
- [PDF](https://arxiv.org/pdf/2610.15106)

