---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem"
description: "The authors introduce RELAGRAM, a recursive latent graph model that adapts latent recursion for graph combinatorial optimization, specifically targeting the capacitated vehicle routing problem (CVRP). RELAGRAM encodes CVRP instances as edge tokens and recurrently updates their latent representations via a compact transformer before decoding feasible solutions. Trained solely on CVRP-100 instances, the model demonstrates strong performance and robust zero-shot generalization to CVRP-500 and CVRP-1000."
resource: "https://arxiv.org/abs/2610.15106"
tags:
  - "vehicle-routing-problem"
  - "neural-routing-solver"
timestamp: "2026-10-23T09:44:49Z"

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
  - name: "sparse-rl-signal-latent-recursion"
    description: "Investigate and engineer advanced reinforcement learning reward signals, auxiliary losses, or curriculum learning strategies tailored specifically to provide denser guidance for intermediate latent states in recursive graph neural models."
skill: "GeneralMLSkill"
processed_at: "2026-10-23T09:44:49Z"
created_at: "2026-10-23T09:44:49Z"
---

# RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem

**Authors**: Vladimir Kirill Bickov, Neil Yorke‐Smith
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15106](https://arxiv.org/abs/2610.15106)

## Summary

The authors introduce RELAGRAM, a recursive latent graph model that adapts latent recursion for graph combinatorial optimization, specifically targeting the capacitated vehicle routing problem (CVRP). RELAGRAM encodes CVRP instances as edge tokens and recurrently updates their latent representations via a compact transformer before decoding feasible solutions. Trained solely on CVRP-100 instances, the model demonstrates strong performance and robust zero-shot generalization to CVRP-500 and CVRP-1000.

## Key Contributions

- Introduced RELAGRAM, a recursive latent graph model that brings latent recursion to graph combinatorial optimization and neural routing.
- Achieved gaps to a PyVRP reference of 13.4%, 9.8%, and 8.3% on CVRP-100 under greedy decoding, eightfold symmetry augmentation, and 256-candidate search, respectively.
- Demonstrated zero-shot generalization from CVRP-100 training to CVRP-500 and CVRP-1000 instances, achieving gaps of 15.6% and 21.7% under 256-candidate search.

## Limitations

Evaluated primarily on CVRP instances with zero-shot scaling up to 1000 nodes; broader applicability to other vehicle routing variants remains to be explored.

## Open Questions & Future Work

- [[sparse-rl-signal-latent-recursion]]

## Key Concepts

- [[relagram]]: A recursive latent graph model that brings latent recursion to graph combinatorial optimization for the capacitated vehicle routing problem.

## Archivist Review

Approved the core model RELAGRAM as a central standalone concept because it establishes a novel recursive latent graph framework for combinatorial optimization. Also approved the open question regarding sparse RL signals for latent recursion as it targets a clear foundational bottleneck. CVRP datasets were rejected because they are standard problem scale variations rather than unique named benchmark datasets.

### Approved Concepts
- RELAGRAM: Introduces latent recursion to graph combinatorial optimization and neural routing, demonstrating strong zero-shot generalization to larger problem instances.

### Approved Open Questions
- Denser Reward Signals for Latent Recursion: Overcoming the sparse reward bottleneck in latent-recursive models is critical for enabling effective gradient propagation and representation learning across recursive reasoning steps in combinatorial optimization.

## Links

- [Abstract](https://arxiv.org/abs/2610.15106)
- [PDF](https://arxiv.org/pdf/2610.15106)

