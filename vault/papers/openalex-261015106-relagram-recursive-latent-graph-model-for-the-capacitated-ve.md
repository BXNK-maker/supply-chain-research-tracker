---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem"
description: "The paper introduces RELAGRAM, a recursive latent graph model that applies latent recursion to the Capacitated Vehicle Routing Problem (CVRP) by recurrently updating edge token representations via a compact transformer. Evaluated on CVRP-100, RELAGRAM achieves competitive performance compared to a PyVRP reference while maintaining a small parameter count (0.53M). Furthermore, when trained exclusively on CVRP-100 instances, the model demonstrates zero-shot generalization capabilities to larger problem scales such as CVRP-500 and CVRP-1000."
resource: "https://arxiv.org/abs/2610.15106"
tags:
  - "neural-routing-solver"
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-10-24T09:15:35Z"

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
    description: "Recursive Latent Graph Model that applies latent recursion to neural routing and graph combinatorial optimization."
datasets:
  []
open_questions:
  - name: "sparse-rl-signal-latent-recursion"
    description: "Investigate and design denser supervision mechanisms or credit assignment strategies tailored for latent-recursive models to improve learning efficiency and optimization stability when trained via reinforcement learning."
skill: "GeneralMLSkill"
processed_at: "2026-10-24T09:15:35Z"
created_at: "2026-10-24T09:15:35Z"
---

# RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem

**Authors**: Vladimir Kirill Bickov, Neil Yorke‐Smith
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15106](https://arxiv.org/abs/2610.15106)

## Summary

The paper introduces RELAGRAM, a recursive latent graph model that applies latent recursion to the Capacitated Vehicle Routing Problem (CVRP) by recurrently updating edge token representations via a compact transformer. Evaluated on CVRP-100, RELAGRAM achieves competitive performance compared to a PyVRP reference while maintaining a small parameter count (0.53M). Furthermore, when trained exclusively on CVRP-100 instances, the model demonstrates zero-shot generalization capabilities to larger problem scales such as CVRP-500 and CVRP-1000.

## Key Contributions

- Introduces RELAGRAM, a recursive latent graph model applying latent recursion to the Capacitated Vehicle Routing Problem (CVRP).
- Achieves competitive gaps to PyVRP on CVRP-100 instances (8.3% gap under 256-candidate search with only 0.53M parameters).
- Demonstrates zero-shot generalization to larger CVRP-500 and CVRP-1000 instances when trained solely on CVRP-100.

## Limitations

Performance gaps increase on larger instances (CVRP-500 and CVRP-1000), indicating room for improvement in zero-shot scaling.

## Open Questions & Future Work

- [[sparse-rl-signal-latent-recursion]]

## Key Concepts

- [[relagram]]: Recursive Latent Graph Model that applies latent recursion to neural routing and graph combinatorial optimization.

## Archivist Review

Approved the core model concept RELAGRAM as a reusable approach for latent recursion in graph combinatorial optimization, along with the open question on sparse reinforcement learning signals for latent recursion. Rejected the dynamic routing open question as a routine future application.

### Approved Concepts
- RELAGRAM: Brings latent recursion to graph combinatorial optimization and neural routing.

### Approved Open Questions
- Denser Reinforcement Learning Supervision: Addressing sparse reinforcement learning signals is critical for enabling effective end-to-end training of latent-recursive neural architectures in combinatorial optimization.

### Rejected Candidates
- [open_question] Latent Recursion for Dynamic Routing (`latent-recursion-dynamic-routing`) - not_novel: This represents a standard future work suggestion (applying a method to a new problem variant) rather than a deep unresolved technical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.15106)
- [PDF](https://arxiv.org/pdf/2610.15106)

