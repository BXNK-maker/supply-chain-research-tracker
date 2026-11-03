---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program"
description: "This paper studies the dynamic allocation of scarce medications in Liberia's community health program to balance patient travel and untreated costs against a demand-weighted fairness utility. The authors formulate a finite-horizon stochastic control problem, approximate it via a reflected Brownian motion control problem, and solve it using a deep splitting method with neural networks. Calibrated on malaria data from Liberia, the proposed policy reduces operating costs by approximately 6% over a fairness-only baseline while maintaining high fairness utility."
resource: "https://arxiv.org/abs/2610.32051"
tags:
  - "autonomous-delivery"
  - "stochastic-demands"
  - "time-series"
timestamp: "2026-11-03T12:36:02Z"

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
  - name: "high-dimensional-stochastic-inventory-control"
    description: "The authors note that while their current model uses a nine-dimensional control problem as a proof-of-concept, extending deep neural network and deep splitting methods to handle hundreds or thousands of dimensions in multi-echelon healthcare and humanitarian supply chains represents an important open computational direction."
skill: "GeneralMLSkill"
processed_at: "2026-11-03T12:36:02Z"
created_at: "2026-11-03T12:36:02Z"
---

# A Dynamic Inventory Rationing Model for Last-Mile Delivery of Medication in Liberia's Community Health Program

**Authors**: Baris Ata, Yufan Chen, Robert Montgomery
**Date**: 2026-10-23
**Paper ID**: [openalex:2610.32051](https://arxiv.org/abs/2610.32051)

## Summary

This paper studies the dynamic allocation of scarce medications in Liberia's community health program to balance patient travel and untreated costs against a demand-weighted fairness utility. The authors formulate a finite-horizon stochastic control problem, approximate it via a reflected Brownian motion control problem, and solve it using a deep splitting method with neural networks. Calibrated on malaria data from Liberia, the proposed policy reduces operating costs by approximately 6% over a fairness-only baseline while maintaining high fairness utility.

## Key Contributions

- Formulated a finite-horizon stochastic control problem for dynamic inventory rationing in last-mile medication delivery, balancing referral/untreated costs against demand-weighted fairness utility.
- Developed a continuous-time approximation controlling the drift rate of a reflected Brownian motion to overcome the computational intractability of standard dynamic programming.
- Adapted the deep splitting method using deep neural networks to approximate the value function and its gradient for computing dynamic allocation policies.
- Calibrated the model using malaria case data from Liberia's Fangonda region, demonstrating a 6% operating cost reduction relative to the fairness-only benchmark while retaining 98% of its fairness utility.

## Open Questions & Future Work

- [[high-dimensional-stochastic-inventory-control]]

## Archivist Review

Approved the open question on high-dimensional stochastic inventory control as it captures an important scalability bottleneck in multi-echelon stochastic control. No concepts or datasets met the strict novelty and reusability standards for vault inclusion.

### Approved Open Questions
- High-Dimensional Stochastic Inventory Control: High-dimensional stochastic control and inventory routing models face severe computational barriers, and validating deep learning techniques for larger multi-echelon networks is crucial for broader operational deployment.

## Links

- [Abstract](https://arxiv.org/abs/2610.32051)
- [PDF](https://arxiv.org/pdf/2610.32051)

