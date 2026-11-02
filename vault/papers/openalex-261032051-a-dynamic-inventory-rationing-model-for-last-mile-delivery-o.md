---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program"
description: "This paper studies the dynamic allocation of scarce medications in Liberia's community health program, balancing patient referral costs and untreated patient outcomes with demand-weighted fairness utility. To overcome the computational intractability of standard dynamic programming, the authors formulate a continuous-time approximation controlling the drift rate of a reflected Brownian motion and solve it using the deep splitting method with deep neural networks. Evaluated on malaria case data from Liberia, the proposed policy reduces operating costs by approximately 6% compared to a fairness-only benchmark while preserving 98% of its fairness utility."
resource: "https://arxiv.org/abs/2610.32051"
tags:
  - "demand-forecasting"
  - "stochastic-demands"
  - "autonomous-delivery"
  - "time-series"
timestamp: "2026-11-02T12:59:39Z"

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
processed_at: "2026-11-02T12:59:39Z"
created_at: "2026-11-02T12:59:39Z"
---

# A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program

**Authors**: Baris Ata, Yufan Chen, Robert Montgomery
**Date**: 2026-10-23
**Paper ID**: [openalex:2610.32051](https://arxiv.org/abs/2610.32051)

## Summary

This paper studies the dynamic allocation of scarce medications in Liberia's community health program, balancing patient referral costs and untreated patient outcomes with demand-weighted fairness utility. To overcome the computational intractability of standard dynamic programming, the authors formulate a continuous-time approximation controlling the drift rate of a reflected Brownian motion and solve it using the deep splitting method with deep neural networks. Evaluated on malaria case data from Liberia, the proposed policy reduces operating costs by approximately 6% compared to a fairness-only benchmark while preserving 98% of its fairness utility.

## Key Contributions

- Formulated a finite-horizon stochastic control problem for dynamic inventory rationing and allocation in last-mile medication delivery, balancing referral costs, untreated patient costs, and demand-weighted fairness utility.
- Developed a continuous-time approximation controlling the drift rate of a reflected Brownian motion to overcome the computational intractability of standard dynamic programming.
- Adapted the deep splitting method using deep neural networks to approximate the value function and its gradient for computing dynamic allocation policies.
- Demonstrated via empirical calibration on malaria cases in Liberia that the proposed policy reduces operating costs by about 6% relative to a fairness-only benchmark while retaining 98% of its fairness utility.

## Archivist Review

Applied strict selectivity filters. The proposed open question focuses specifically on scaling multi-echelon healthcare supply chain operations, which is too application-specific for a general machine learning vault. No concepts or datasets were provided or warranted approval.

### Rejected Candidates
- [open_question] High-Dimensional Multi-Echelon Healthcare Scaling (`high-dimensional-multi-echelon-healthcare-scaling`) - low_impact: Too domain-specific to healthcare supply chain operations and scaling rather than a general core algorithmic or machine learning bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.32051)
- [PDF](https://arxiv.org/pdf/2610.32051)

