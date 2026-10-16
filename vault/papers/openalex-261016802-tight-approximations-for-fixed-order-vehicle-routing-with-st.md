---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Tight Approximations for Fixed-Order Vehicle Routing with Stochastic Demands"
description: "This paper studies the vehicle routing problem with stochastic demands under a priori and restocking policies. By employing a traveling salesman tour constructed via matroid parity, the authors improve randomized approximation ratios to 2 (splittable) and 3 (unsplittable), and introduce deterministic (2+epsilon) and (3+epsilon) approximations. They also establish matching lower bounds of 2 and 3 that hold for randomized restocking policies."
resource: "https://arxiv.org/abs/2610.16802"
tags:
  - "approximation-algorithms"
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-16T09:27:22Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jngyang Zhao"
  - literal: "Mingyu Xiao"
issued:
  date-parts:
    - [2026, 10, 12]

# Domain-specific custom fields
paper_id: "2610.16802"
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
processed_at: "2026-10-16T09:27:22Z"
created_at: "2026-10-16T09:27:22Z"
---

# Tight Approximations for Fixed-Order Vehicle Routing with Stochastic Demands

**Authors**: Jngyang Zhao, Mingyu Xiao
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.16802](https://arxiv.org/abs/2610.16802)

## Summary

This paper studies the vehicle routing problem with stochastic demands under a priori and restocking policies. By employing a traveling salesman tour constructed via matroid parity, the authors improve randomized approximation ratios to 2 (splittable) and 3 (unsplittable), and introduce deterministic (2+epsilon) and (3+epsilon) approximations. They also establish matching lower bounds of 2 and 3 that hold for randomized restocking policies.

## Key Contributions

- Improved randomized a priori approximation ratios from (alpha+1) and (alpha+2) down to 2 and 3 for splittable and unsplittable vehicle routing with stochastic demands.
- Developed deterministic a priori (2+epsilon) and (3+epsilon)-approximation algorithms via cumulative demand distribution compression.
- Established matching theoretical lower bounds of 2 and 3 even for the general class of randomized restocking policies.
- Applied matroid-parity construction to improve approximation ratios for several vehicle routing variants with deterministic demands.

## Limitations

Restricted to fixed-order vehicle routing policies where client visitation order is determined prior to observing demands.

## Archivist Review

No concepts or datasets met the rigorous bar for standalone vault entries; all terms are either standard operational research problem formulations or specific algorithmic reductions not warranting independent permanent notes.

## Links

- [Abstract](https://arxiv.org/abs/2610.16802)
- [PDF](https://arxiv.org/pdf/2610.16802)

