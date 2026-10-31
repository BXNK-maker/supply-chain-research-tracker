---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program"
description: "This paper studies the dynamic allocation of scarce medications in Liberia's community health program to balance patient travel costs, untreated risks, and geographic fairness. The authors formulate a finite-horizon stochastic control problem, approximate it in continuous time via a controlled reflected Brownian motion, and solve it using a deep splitting neural network method. Evaluated on empirical malaria data from Liberia, the proposed policy reduces operating costs by roughly 6% compared to baseline fairness-only policies while preserving nearly all fairness utility."
resource: "https://arxiv.org/abs/2610.32051"
tags:
  - "autonomous-delivery"
  - "demand-forecasting"
  - "stochastic-demands"
timestamp: "2026-10-31T10:41:28Z"

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
processed_at: "2026-10-31T10:41:28Z"
created_at: "2026-10-31T10:41:28Z"
---

# A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program

**Authors**: Baris Ata, Yufan Chen, Robert Montgomery
**Date**: 2026-10-23
**Paper ID**: [openalex:2610.32051](https://arxiv.org/abs/2610.32051)

## Summary

This paper studies the dynamic allocation of scarce medications in Liberia's community health program to balance patient travel costs, untreated risks, and geographic fairness. The authors formulate a finite-horizon stochastic control problem, approximate it in continuous time via a controlled reflected Brownian motion, and solve it using a deep splitting neural network method. Evaluated on empirical malaria data from Liberia, the proposed policy reduces operating costs by roughly 6% compared to baseline fairness-only policies while preserving nearly all fairness utility.

## Key Contributions

- Formulated a finite-horizon stochastic control problem for dynamic medication allocation in last-mile community health programs, balancing referral costs, untreated patient costs, and demand-weighted fairness utility.
- Developed a continuous-time approximation approach controlling the drift rate of a reflected Brownian motion and adapted the deep splitting method using neural networks to compute the allocation policy.
- Demonstrated that the proposed policy reduces operating costs by about 6% relative to a fairness-only benchmark while retaining roughly 98% of its fairness utility using empirical data from Liberia's Lofa County.

## Limitations

Limited to the evaluated community health program context and relies on continuous-time diffusion approximations of discrete inventory dynamics.

## Archivist Review

Applied high selectivity standards: the sole proposed open question is highly domain-specific to healthcare inventory rationing rather than representing a general ML research bottleneck. No reusable concepts or datasets qualified for standalone vault notes.

### Rejected Candidates
- [open_question] Scalable High-Dimensional Stochastic Control (`scalable-high-dimensional-stochastic-control-healthcare`) - low_impact: Too domain-specific to healthcare inventory distribution and does not represent a general, reusable machine learning research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.32051)
- [PDF](https://arxiv.org/pdf/2610.32051)

