---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Learning Advantage Function Surrogates via Convex Conjugate Matching"
description: "Pure policy-learning algorithms often output optimal per-unit decisions without providing an advantage function or critic to evaluate the cost of deviations. To address this, the paper proposes a method for training an advantage function surrogate via price perturbations motivated by a Fenchel-Young loss. The approach relies on a two-stage recipe that first fits the policy and subsequently fits the cost model, demonstrated on a multi-period inventory management problem."
resource: "https://arxiv.org/abs/2611.20199"
tags:
  - "reinforcement-learning"
timestamp: "2026-11-19T14:12:38Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Alvaro Maggiar"
issued:
  date-parts:
    - [2026, 11, 15]

# Domain-specific custom fields
paper_id: "2611.20199"
paper_source: "openalex"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "richer-surrogate-families-non-closed-form-conjugates"
    description: "Investigate richer surrogate families, such as input convex networks or M^{\\\\natural}-convex functions for placement problems, which enlarge the set of action-value functions the surrogate can match but lack closed-form conjugate gradients and scalable differentiation costs."
skill: "GeneralMLSkill"
processed_at: "2026-11-19T14:12:38Z"
created_at: "2026-11-19T14:12:38Z"
---

# Learning Advantage Function Surrogates via Convex Conjugate Matching

**Authors**: Alvaro Maggiar
**Date**: 2026-11-15
**Paper ID**: [openalex:2611.20199](https://arxiv.org/abs/2611.20199)

## Summary

Pure policy-learning algorithms often output optimal per-unit decisions without providing an advantage function or critic to evaluate the cost of deviations. To address this, the paper proposes a method for training an advantage function surrogate via price perturbations motivated by a Fenchel-Young loss. The approach relies on a two-stage recipe that first fits the policy and subsequently fits the cost model, demonstrated on a multi-period inventory management problem.

## Key Contributions

- Proposed a method to train advantage function surrogates through price perturbations motivated by a Fenchel-Young loss.
- Described a two-stage recipe (fit the policy, then the cost model) for estimating deviation costs from per-unit decisions.
- Illustrated the proposed surrogate training approach on a multi-period inventory management problem.

## Open Questions & Future Work

- [[richer-surrogate-families-non-closed-form-conjugates]]

## Archivist Review

Approved the open question regarding richer surrogate families and non-closed-form conjugates as it poses a specific, substantive technical bottleneck in scaling conjugate-matching advantage learning. No standalone vault concepts met the strict novelty and reusability standards.

### Approved Open Questions
- Richer Surrogate Families and Non-Closed-Form Conjugates: Understanding how to scale and differentiate non-closed-form convex surrogate families is critical for expanding the applicability of conjugate-matching advantage learning to complex, high-dimensional operations research and reinforcement learning problems.

## Links

- [Abstract](https://arxiv.org/abs/2611.20199)
- [PDF](https://arxiv.org/pdf/2611.20199)

