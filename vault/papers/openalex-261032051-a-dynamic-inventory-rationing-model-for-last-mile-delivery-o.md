---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program"
description: "This paper studies the dynamic allocation of scarce medications in Liberia's community health program, balancing patient travel costs, untreated patient penalties, and fairness across locations. Because standard dynamic programming is intractable, the authors formulate a continuous-time approximation using a reflected Brownian motion and apply the deep splitting method with neural networks to compute allocation policies. Evaluated on malaria case data from Liberia, the proposed policy reduces operating costs by approximately 6% relative to a fairness-only benchmark while preserving nearly all of its fairness utility."
resource: "https://arxiv.org/abs/2610.32051"
tags:
  - "demand-forecasting"
  - "stochastic-demands"
timestamp: "2026-11-01T11:36:31Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Baris Ata"
  - literal: "Yufan Chen"
  - literal: "Robert Montgomery"
issued:
  date-parts:
    - [2026, 10, 23]

# Domain-specific custom fields
paper_id: "2610.32051"
paper_source: "openalex"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:36:31Z"
created_at: "2026-11-01T11:36:31Z"
---

# A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program

**Authors**: Baris Ata, Yufan Chen, Robert Montgomery
**Date**: 2026-10-23
**Paper ID**: [openalex:2610.32051](https://arxiv.org/abs/2610.32051)

## Summary

This paper studies the dynamic allocation of scarce medications in Liberia's community health program, balancing patient travel costs, untreated patient penalties, and fairness across locations. Because standard dynamic programming is intractable, the authors formulate a continuous-time approximation using a reflected Brownian motion and apply the deep splitting method with neural networks to compute allocation policies. Evaluated on malaria case data from Liberia, the proposed policy reduces operating costs by approximately 6% relative to a fairness-only benchmark while preserving nearly all of its fairness utility.

## Key Contributions

- Formulates a finite-horizon stochastic control problem for dynamic inventory rationing in community health last-mile delivery, balancing referral costs, untreated patient penalties, and demand-weighted fairness utility.
- Develops a continuous-time approximation controlling the drift rate of a reflected Brownian motion to overcome the computational intractability of standard dynamic programming.
- Adapts the deep splitting method using deep neural networks to approximate the value function and its gradient for computing dynamic allocation policies.
- Demonstrates on malaria case data from Liberia that the proposed policy reduces operating costs by about 6% relative to a fairness-only benchmark while retaining 98% of its fairness utility.

## Archivist Review

No concepts or open questions met the rigorous inclusion bar. The paper addresses a domain-specific application in last-mile healthcare inventory management using standard deep splitting and reflected Brownian motion approximations, which do not introduce broadly reusable core ML vault concepts or novel unresolved theoretical bottlenecks beyond standard scaling goals.

### Rejected Candidates
- [open_question] Scaling High-Dimensional Stochastic Control (`high-dimensional-stochastic-control-scaling`) - low_impact: This open question asks about scaling deep-learning-based stochastic control methods to hundreds or thousands of dimensions, which is a routine scaling and performance aspiration rather than a specifically formulated, independently tracked conceptual bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.32051)
- [PDF](https://arxiv.org/pdf/2610.32051)

