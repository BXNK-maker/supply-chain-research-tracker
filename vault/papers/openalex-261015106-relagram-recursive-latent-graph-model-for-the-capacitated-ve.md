---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem"
description: "This paper introduces RELAGRAM, a novel recursive latent graph model that brings latent recursion to graph combinatorial optimization for the capacitated vehicle routing problem (CVRP). RELAGRAM encodes CVRP instances as edge tokens and recurrently updates their latent representations using a compact transformer before decoding feasible solutions. Operating with only 0.53M parameters, RELAGRAM achieves competitive optimality gaps on CVRP-100 and demonstrates zero-shot generalization to larger instances such as CVRP-500 and CVRP-1000."
resource: "https://arxiv.org/abs/2610.15106"
tags:
  - "neural-routing-solver"
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-20T09:46:57Z"

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
  - name: "reinforcement-learning-signal-shaping-for-latent-recursion"
    description: "Investigate and design improved reinforcement learning signal mechanisms tailored for latent-recursive neural architectures, addressing the limitation that internal state vectors receive only indirect feedback from route-level rewards."
skill: "GeneralMLSkill"
processed_at: "2026-10-20T09:46:57Z"
created_at: "2026-10-20T09:46:57Z"
---

# RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem

**Authors**: Vladimir Kirill Bickov, Neil Yorke‐Smith
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15106](https://arxiv.org/abs/2610.15106)

## Summary

This paper introduces RELAGRAM, a novel recursive latent graph model that brings latent recursion to graph combinatorial optimization for the capacitated vehicle routing problem (CVRP). RELAGRAM encodes CVRP instances as edge tokens and recurrently updates their latent representations using a compact transformer before decoding feasible solutions. Operating with only 0.53M parameters, RELAGRAM achieves competitive optimality gaps on CVRP-100 and demonstrates zero-shot generalization to larger instances such as CVRP-500 and CVRP-1000.

## Key Contributions

- Introduces RELAGRAM, bringing latent recursion to graph combinatorial optimization and neural routing.
- Achieves competitive gaps to PyVRP reference on CVRP-100 instances (13.4% greedy, 9.8% with symmetry augmentation, 8.3% with candidate search) using a compact 0.53M-parameter model.
- Demonstrates zero-shot generalization from CVRP-100 training to larger instances (CVRP-500 and CVRP-1000), achieving gaps of 15.6% and 21.7% under 256-candidate search.

## Limitations

Evaluated primarily on CVRP instances; zero-shot generalization degrades as instance size scales up to CVRP-1000.

## Open Questions & Future Work

- [[reinforcement-learning-signal-shaping-for-latent-recursion]]

## Key Concepts

- [[relagram]]: A recursive latent graph model that repeatedly processes internal representations through a compact transformer for the capacitated vehicle routing problem.

## Archivist Review

Approved RELAGRAM as a central novel architecture applying latent recursion to graph combinatorial optimization and routing. Approved the open question on reinforcement-learning signal shaping for latent recursion due to its fundamental challenge in recursive neural models. Rejected CVRP as it is a standard problem family rather than a novel dataset.

### Approved Concepts
- RELAGRAM (Recursive Latent Graph Model): Introduces latent recursion to graph combinatorial optimization and neural routing, demonstrating strong zero-shot generalization on CVRP instances.

### Approved Open Questions
- Reinforcement Learning Signals for Latent Recursion: Latent recursion relies heavily on intermediate latent states receiving adequate supervision or reward gradients; solving the sparse feedback bottleneck is crucial for scaling recursive reasoning in reinforcement learning.

### Rejected Candidates
- [dataset] CVRP (`cvrp`) - not_novel: Standard combinatorial optimization problem benchmark family rather than a novel standalone dataset created or curated specifically as a unique vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2610.15106)
- [PDF](https://arxiv.org/pdf/2610.15106)

