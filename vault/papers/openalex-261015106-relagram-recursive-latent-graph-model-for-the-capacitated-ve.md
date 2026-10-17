---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem"
description: "The paper introduces RELAGRAM, a recursive latent graph model that applies latent recursion to the capacitated vehicle routing problem (CVRP). By recurrently updating edge token representations through a compact transformer, RELAGRAM constructs feasible routing solutions via an autoregressive decoder. Experiments on CVRP-100 demonstrate competitive gaps to PyVRP references while achieving zero-shot generalization to larger scales such as CVRP-500 and CVRP-1000."
resource: "https://arxiv.org/abs/2610.15106"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-17T08:57:55Z"

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
    description: "A recursive latent graph model that repeatedly processes internal edge token representations via a compact transformer for combinatorial optimization."
datasets:
  []
open_questions:
  - name: "reinforcement-learning-signal-shaping-for-latent-recursion"
    description: "Investigate the design of reinforcement learning signals and training dynamics for latent-recursive models applied to routing problems, addressing the limitation that internal states receive only indirect and sparse reinforcement learning guidance."
skill: "GeneralMLSkill"
processed_at: "2026-10-17T08:57:55Z"
created_at: "2026-10-17T08:57:55Z"
---

# RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem

**Authors**: Vladimir Kirill Bickov, Neil Yorke‐Smith
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15106](https://arxiv.org/abs/2610.15106)

## Summary

The paper introduces RELAGRAM, a recursive latent graph model that applies latent recursion to the capacitated vehicle routing problem (CVRP). By recurrently updating edge token representations through a compact transformer, RELAGRAM constructs feasible routing solutions via an autoregressive decoder. Experiments on CVRP-100 demonstrate competitive gaps to PyVRP references while achieving zero-shot generalization to larger scales such as CVRP-500 and CVRP-1000.

## Key Contributions

- Introduced RELAGRAM, a compact 0.53M-parameter recursive latent graph model that brings latent recursion to graph combinatorial optimization.
- Demonstrated zero-shot generalization of RELAGRAM trained on CVRP-100 to larger instances such as CVRP-500 and CVRP-1000.
- Achieved gaps to a PyVRP reference of 13.4% (greedy), 9.8% (symmetry augmentation), and 8.3% (256-candidate search) on CVRP-100 instances.

## Limitations

Evaluation is limited to CVRP instances up to CVRP-1000, and optimality gaps increase with instance scale under zero-shot generalization.

## Open Questions & Future Work

- [[reinforcement-learning-signal-shaping-for-latent-recursion]]

## Key Concepts

- [[relagram]]: A recursive latent graph model that repeatedly processes internal edge token representations via a compact transformer for combinatorial optimization.

## Archivist Review

Approved the core model RELAGRAM (using its canonical slug 'relagram') and reused the existing vault open question for reinforcement learning signal shaping in latent recursion. Rejected the standard CVRP problem as not novel.

### Approved Concepts
- Recursive Latent Graph Model: RELAGRAM introduces latent recursion to graph combinatorial optimization and routing problems, providing a compact parameter-efficient architecture for CVRP.

### Approved Open Questions
- Reinforcement Learning for Latent Recursion: Crucial for improving the training stability and sample efficiency of latent-recursive architectures in combinatorial optimization, as current indirect supervision limits performance compared to established search methods like ant colony optimization.

### Rejected Candidates
- [concept] Capacitated Vehicle Routing Problem (`capacitated-vehicle-routing-problem`) - not_novel: Standard combinatorial optimization problem rather than a novel concept introduced by the paper.

## Links

- [Abstract](https://arxiv.org/abs/2610.15106)
- [PDF](https://arxiv.org/pdf/2610.15106)

