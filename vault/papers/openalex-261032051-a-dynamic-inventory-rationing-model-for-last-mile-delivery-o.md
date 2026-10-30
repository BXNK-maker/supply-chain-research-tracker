---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program"
description: "This paper investigates the dynamic allocation of scarce medications in community health programs, focusing on last-mile delivery in Liberia. To overcome the computational intractability of standard dynamic programming, the authors formulate a continuous-time approximation controlled by a reflected Brownian motion and solve it using deep neural networks via the deep splitting method. Calibrated on malaria case data from Liberia, the proposed policy reduces operating costs by about 6% compared to the strongest baseline while maintaining high fairness utility."
resource: "https://arxiv.org/abs/2610.32051"
tags:
  - "autonomous-delivery"
  - "demand-forecasting"
  - "stochastic-demands"
timestamp: "2026-10-30T11:07:48Z"

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
processed_at: "2026-10-30T11:07:48Z"
created_at: "2026-10-30T11:07:48Z"
---

# A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program

**Authors**: Baris Ata, Yufan Chen, Robert Montgomery
**Date**: 2026-10-23
**Paper ID**: [openalex:2610.32051](https://arxiv.org/abs/2610.32051)

## Summary

This paper investigates the dynamic allocation of scarce medications in community health programs, focusing on last-mile delivery in Liberia. To overcome the computational intractability of standard dynamic programming, the authors formulate a continuous-time approximation controlled by a reflected Brownian motion and solve it using deep neural networks via the deep splitting method. Calibrated on malaria case data from Liberia, the proposed policy reduces operating costs by about 6% compared to the strongest baseline while maintaining high fairness utility.

## Key Contributions

- Formulates a finite-horizon stochastic control problem balancing referral costs, untreated patient costs, and demand-weighted fairness utility for last-mile medication allocation in community health programs.
- Develops a continuous-time approximation controlling the drift rate of a reflected Brownian motion to overcome the computational intractability of standard dynamic programming.
- Adapts the deep splitting method using deep neural networks to approximate the value function and its gradient for computing dynamic allocation policies.
- Demonstrates a 6% operating cost reduction relative to the fairness-only benchmark while retaining approximately 98% of its fairness utility when calibrated on malaria cases in Liberia's Fangonda region.

## Archivist Review

Applied standard selectivity filtering. No concepts or open questions met the rigorous bar for long-term vault retention in this review cycle.

### Rejected Candidates
- [open_question] Scaling High-Dimensional Brownian Control (`high-dimensional-brownian-control-scaling`) - low_impact: While scaling high-dimensional stochastic control is relevant, this is a standard broad research direction in applied mathematics and operations research rather than a specific open technical bottleneck unique to machine learning vault integration.

## Links

- [Abstract](https://arxiv.org/abs/2610.32051)
- [PDF](https://arxiv.org/pdf/2610.32051)

