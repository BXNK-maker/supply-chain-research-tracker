---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program"
description: "This paper studies the dynamic allocation of scarce medications in community health programs, balancing patient travel costs, untreated demand, and spatial fairness through a finite-horizon stochastic control model. Because standard dynamic programming is intractable, the authors introduce a continuous-time approximation using a reflected Brownian motion and solve it via the deep splitting method with deep neural networks. Evaluated on malaria case data from Liberia, the proposed policy reduces operating costs by 6% relative to the fairness-only baseline while preserving 98% of its fairness utility."
resource: "https://arxiv.org/abs/2610.32051"
tags:
  - "demand-forecasting"
  - "stochastic-demands"
  - "time-series"
timestamp: "2026-10-29T11:13:37Z"

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
processed_at: "2026-10-29T11:13:37Z"
created_at: "2026-10-29T11:13:37Z"
---

# A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program

**Authors**: Baris Ata, Yufan Chen, Robert Montgomery
**Date**: 2026-10-23
**Paper ID**: [openalex:2610.32051](https://arxiv.org/abs/2610.32051)

## Summary

This paper studies the dynamic allocation of scarce medications in community health programs, balancing patient travel costs, untreated demand, and spatial fairness through a finite-horizon stochastic control model. Because standard dynamic programming is intractable, the authors introduce a continuous-time approximation using a reflected Brownian motion and solve it via the deep splitting method with deep neural networks. Evaluated on malaria case data from Liberia, the proposed policy reduces operating costs by 6% relative to the fairness-only baseline while preserving 98% of its fairness utility.

## Key Contributions

- Formulates a finite-horizon stochastic control problem for last-mile medical inventory rationing that integrates patient travel costs, untreated demand, and demand-weighted fairness utility.
- Develops a continuous-time approximation controlling the drift rate of a reflected Brownian motion, solved via the deep splitting method with neural networks approximating the value function and its gradient.
- Demonstrates through calibration on malaria case data from Liberia that the proposed policy reduces operating costs by about 6% while retaining approximately 98% of the fairness utility of a fairness-only baseline.

## Archivist Review

Applied rigorous selectivity standards. The paper addresses an operations research and supply chain problem (last-mile inventory rationing in healthcare) using stochastic control and numerical PDEs. While rigorous, the core concepts and open questions are domain-specific to humanitarian logistics and applied probability rather than core general machine learning or AI methodology, so they were rejected to keep the vault focused.

### Rejected Candidates
- [concept] Dynamic Inventory Rationing (`dynamic-inventory-rationing`) - low_impact: Too domain-specific to operations research and humanitarian logistics rather than core machine learning or general AI methodology.
- [open_question] Nonstationary High-Dimensional RBM Control (`nonstationary-rbm-deep-splitting`) - low_impact: An operations research and stochastic control extension rather than a central machine learning research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.32051)
- [PDF](https://arxiv.org/pdf/2610.32051)

