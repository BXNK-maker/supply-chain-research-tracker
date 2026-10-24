---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Tight Approximations for Fixed-Order Vehicle Routing with Stochastic Demands"
description: "This paper studies the vehicle routing problem with stochastic demands under a priori and restocking policies. The authors improve randomized a priori approximation ratios to 2 and 3 for splittable and unsplittable deliveries, respectively, using a TSP construction via matroid parity. They also provide deterministic $(2+\\varepsilon)$- and $(3+\\varepsilon)$-approximation algorithms, establish matching lower bounds, and extend their matroid-parity construction to deterministic VRP variants."
resource: "https://arxiv.org/abs/2610.16802"
tags:
  - "vehicle-routing-problem"
  - "approximation-algorithms"
  - "stochastic-demands"
timestamp: "2026-10-24T09:14:33Z"

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
  - name: "matroid-parity-tsp-construction"
    description: "A technique using matroid parity to construct TSP tours for improving approximation guarantees in vehicle routing problems."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-24T09:14:33Z"
created_at: "2026-10-24T09:14:33Z"
---

# Tight Approximations for Fixed-Order Vehicle Routing with Stochastic Demands

**Authors**: Jingyang Zhao, Mingyu Xiao
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.16802](https://arxiv.org/abs/2610.16802)

## Summary

This paper studies the vehicle routing problem with stochastic demands under a priori and restocking policies. The authors improve randomized a priori approximation ratios to 2 and 3 for splittable and unsplittable deliveries, respectively, using a TSP construction via matroid parity. They also provide deterministic $(2+\varepsilon)$- and $(3+\varepsilon)$-approximation algorithms, establish matching lower bounds, and extend their matroid-parity construction to deterministic VRP variants.

## Key Contributions

- Improved randomized a priori approximation ratios to 2 and 3 for splittable and unsplittable deliveries in fixed-order VRP with stochastic demands using a matroid-parity TSP tour.
- Developed deterministic a priori (2+\epsilon)-approximation and (3+\epsilon)-approximation algorithms via cumulative demand distribution compression.
- Established matching lower bounds of 2 and 3 that hold even for randomized restocking policies.
- Applied the matroid-parity construction to improve approximation ratios for several VRP variants with deterministic demands.

## Key Concepts

- [[matroid-parity-tsp-construction]]: A technique using matroid parity to construct TSP tours for improving approximation guarantees in vehicle routing problems.

## Archivist Review

Approved the matroid-parity-tsp-construction concept as it already exists in the vault and represents a reusable combinatorial optimization technique for routing algorithms. No datasets or open questions were proposed.

### Approved Concepts
- Matroid Parity TSP Construction: Improves approximation ratios for fixed-order vehicle routing with stochastic demands by combining replenishment rules with matroid parity.

## Links

- [Abstract](https://arxiv.org/abs/2610.16802)
- [PDF](https://arxiv.org/pdf/2610.16802)

