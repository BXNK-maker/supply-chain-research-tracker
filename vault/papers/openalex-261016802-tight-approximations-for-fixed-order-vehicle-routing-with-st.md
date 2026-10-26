---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Tight Approximations for Fixed-Order Vehicle Routing with Stochastic Demands"
description: "This paper studies the vehicle routing problem with stochastic demands under fixed-order a priori and restocking policies. By constructing TSP tours via matroid parity rather than general metric TSP solvers, the authors improve the randomized a priori approximation ratios to 2 and 3 for splittable and unsplittable deliveries, respectively. They also introduce deterministic approximation schemes using cumulative demand distribution compression and prove matching lower bounds for randomized restocking policies."
resource: "https://arxiv.org/abs/2610.16802"
tags:
  - "vehicle-routing-problem"
  - "approximation-algorithms"
  - "stochastic-demands"
timestamp: "2026-10-26T10:41:27Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jingyang Zhao"
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
processed_at: "2026-10-26T10:41:27Z"
created_at: "2026-10-26T10:41:27Z"
---

# Tight Approximations for Fixed-Order Vehicle Routing with Stochastic Demands

**Authors**: Jingyang Zhao, Mingyu Xiao
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.16802](https://arxiv.org/abs/2610.16802)

## Summary

This paper studies the vehicle routing problem with stochastic demands under fixed-order a priori and restocking policies. By constructing TSP tours via matroid parity rather than general metric TSP solvers, the authors improve the randomized a priori approximation ratios to 2 and 3 for splittable and unsplittable deliveries, respectively. They also introduce deterministic approximation schemes using cumulative demand distribution compression and prove matching lower bounds for randomized restocking policies.

## Key Contributions

- Improved randomized a priori approximation ratios from (alpha + 1) and (alpha + 2) to 2 and 3 for splittable and unsplittable vehicle routing with stochastic demands using matroid parity.
- Developed deterministic a priori (2 + epsilon)- and (3 + epsilon)-approximation algorithms by compressing cumulative demand distributions in polynomial time.
- Established matching lower bounds of 2 and 3 for randomized restocking policies.
- Applied matroid-parity constructions to improve approximation ratios for several vehicle routing problem variants with deterministic demands.

## Archivist Review

Applied strict selectivity criteria. The paper focuses on theoretical approximation algorithms for vehicle routing with stochastic demands, but no standalone reusable concepts or open questions met the bar for vault insertion.

### Rejected Candidates
- [open_question] Tight Approximations for Unsplittable VRP (`tight-approximations-unsplittable-vrp`) - duplicate_existing: The paper establishes matching lower bounds of 2 and 3, meaning the bounds for these fixed-order policies are already tight, making the proposed open question redundant.

## Links

- [Abstract](https://arxiv.org/abs/2610.16802)
- [PDF](https://arxiv.org/pdf/2610.16802)

