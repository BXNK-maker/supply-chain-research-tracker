---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program"
description: "This paper studies the dynamic allocation of scarce medications in Liberia's community health program to balance patient travel costs, untreated risks, and geographic fairness. The authors formulate a finite-horizon stochastic control problem and develop a continuous-time approximation utilizing reflected Brownian motion and deep neural networks to compute allocation policies. Calibrated on data from Liberia, the proposed policy reduces operating costs by about 6% compared to the strongest fairness benchmark while preserving high fairness utility."
resource: "https://arxiv.org/abs/2610.32051"
tags:
  - "autonomous-delivery"
  - "stochastic-demands"
timestamp: "2026-11-04T12:43:04Z"

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
processed_at: "2026-11-04T12:43:04Z"
created_at: "2026-11-04T12:43:04Z"
---

# A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program

**Authors**: Baris Ata, Yufan Chen, Robert Montgomery
**Date**: 2026-10-23
**Paper ID**: [openalex:2610.32051](https://arxiv.org/abs/2610.32051)

## Summary

This paper studies the dynamic allocation of scarce medications in Liberia's community health program to balance patient travel costs, untreated risks, and geographic fairness. The authors formulate a finite-horizon stochastic control problem and develop a continuous-time approximation utilizing reflected Brownian motion and deep neural networks to compute allocation policies. Calibrated on data from Liberia, the proposed policy reduces operating costs by about 6% compared to the strongest fairness benchmark while preserving high fairness utility.

## Key Contributions

- Formulated the last-mile medication allocation problem as a finite-horizon stochastic control problem balancing referral costs, untreated patient costs, and fairness utility.
- Developed a continuous-time approximation controlling the drift rate of a reflected Brownian motion combined with deep neural networks for value function approximation.
- Demonstrated a 6% operating cost reduction relative to the fairness-only benchmark while retaining 98% of its fairness utility using empirical data from Liberia's community health program.

## Archivist Review

The proposed concept and open question are heavily application-specific to humanitarian healthcare logistics and inventory control, which does not fit the criteria for permanent, broadly reusable ML vault notes. No datasets qualified for standalone vault entry either.

### Rejected Candidates
- [concept] Dynamic Inventory Rationing Model (`dynamic-inventory-rationing-model`) - not_reusable: The proposed dynamic inventory rationing model is highly specific to last-mile medical supply chains and stochastic inventory control, representing an application domain rather than a broad, reusable ML methodological primitive or architecture.
- [open_question] Dynamic Medication Rationing with Endogenous Compliance (`dynamic-medication-rationing-endogenous-compliance`) - low_impact: This open question is extremely narrow and application-specific to healthcare rationing and referral compliance, rather than a general core research bottleneck in machine learning.

## Links

- [Abstract](https://arxiv.org/abs/2610.32051)
- [PDF](https://arxiv.org/pdf/2610.32051)

