---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program"
description: "We study the dynamic allocation of scarce medications in Liberia's community health program by formulating a finite-horizon stochastic control problem that balances patient referral costs, untreated patient costs, and a demand-weighted fairness utility. To overcome the computational intractability of standard dynamic programming, we develop a continuous-time approximation controlling the drift rate of a reflected Brownian motion and use the deep splitting method with deep neural networks to compute dynamic allocation policies. Calibrated using malaria case data from Lofa County, Liberia, our policy reduces operating costs by about 6% relative to the fairness-only benchmark while retaining approximately 98% of its fairness utility. Additional experiments reveal that higher referral costs shift inventory toward Community Health Assistants and reduce local unmet demand, whereas greater demand variability further increases our policy's performance advantage."
resource: "https://arxiv.org/abs/2610.32051"
tags:
  - "demand-forecasting"
  - "stochastic-demands"
  - "time-series"
timestamp: "2026-10-28T10:58:16Z"

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
processed_at: "2026-10-28T10:58:16Z"
created_at: "2026-10-28T10:58:16Z"
---

# A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program

**Authors**: Baris Ata, Yufan Chen, Robert Montgomery
**Date**: 2026-10-23
**Paper ID**: [openalex:2610.32051](https://arxiv.org/abs/2610.32051)

## Summary

We study the dynamic allocation of scarce medications in Liberia's community health program by formulating a finite-horizon stochastic control problem that balances patient referral costs, untreated patient costs, and a demand-weighted fairness utility. To overcome the computational intractability of standard dynamic programming, we develop a continuous-time approximation controlling the drift rate of a reflected Brownian motion and use the deep splitting method with deep neural networks to compute dynamic allocation policies. Calibrated using malaria case data from Lofa County, Liberia, our policy reduces operating costs by about 6% relative to the fairness-only benchmark while retaining approximately 98% of its fairness utility. Additional experiments reveal that higher referral costs shift inventory toward Community Health Assistants and reduce local unmet demand, whereas greater demand variability further increases our policy's performance advantage.

## Key Contributions

- Formulated a finite-horizon stochastic control problem for dynamic medication allocation combining referral/untreated patient costs with demand-weighted fairness utility
- Developed a continuous-time approximation controlling the drift rate of a reflected Brownian motion to overcome the computational intractability of standard dynamic programming
- Adapted the deep splitting method using deep neural networks to approximate the value function and its gradient for computing dynamic allocation policies
- Demonstrated a 6% reduction in operating costs relative to the fairness-only benchmark while retaining 98% of its fairness utility using malaria case data from the Fangonda region in Liberia

## Links

- [Abstract](https://arxiv.org/abs/2610.32051)
- [PDF](https://arxiv.org/pdf/2610.32051)

