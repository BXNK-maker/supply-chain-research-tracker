---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Tight Approximations for Fixed-Order Vehicle Routing with Stochastic Demands"
description: "This paper studies the vehicle routing problem with stochastic demands under fixed-order a priori and restocking policies. The authors improve existing randomized approximation ratios to 2 for splittable deliveries and 3 for unsplittable deliveries by employing a matroid-parity-based TSP tour construction. Furthermore, they develop deterministic (2+ε)- and (3+ε)-approximation algorithms and establish matching theoretical lower bounds of 2 and 3 that extend to randomized restocking policies."
resource: "https://arxiv.org/abs/2610.16802"
tags:
  - "vehicle-routing-problem"
  - "stochastic-demands"
  - "approximation-algorithms"
timestamp: "2026-10-23T09:42:10Z"

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
    description: "A technique that constructs TSP tours via matroid parity to improve approximation ratios for vehicle routing problems with stochastic demands."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-23T09:42:10Z"
created_at: "2026-10-23T09:42:10Z"
---

# Tight Approximations for Fixed-Order Vehicle Routing with Stochastic Demands

**Authors**: Jingyang Zhao, Mingyu Xiao
**Date**: 2026-10-12
**Paper ID**: [openalex:2610.16802](https://arxiv.org/abs/2610.16802)

## Summary

This paper studies the vehicle routing problem with stochastic demands under fixed-order a priori and restocking policies. The authors improve existing randomized approximation ratios to 2 for splittable deliveries and 3 for unsplittable deliveries by employing a matroid-parity-based TSP tour construction. Furthermore, they develop deterministic (2+ε)- and (3+ε)-approximation algorithms and establish matching theoretical lower bounds of 2 and 3 that extend to randomized restocking policies.

## Key Contributions

- Improved randomized a priori approximation ratios to 2 and 3 for splittable and unsplittable deliveries, respectively, using a TSP tour constructed via matroid parity.
- Developed deterministic a priori (2+ε)-approximation and (3+ε)-approximation algorithms by compressing cumulative demand distributions in polynomial time.
- Established matching lower bounds of 2 and 3 holding even for the more general class of randomized restocking policies.

## Key Concepts

- [[matroid-parity-tsp-construction]]: A technique that constructs TSP tours via matroid parity to improve approximation ratios for vehicle routing problems with stochastic demands.

## Archivist Review

Approved the concept 'Matroid Parity TSP Construction' as a novel and reusable technique for vehicle routing approximations. No datasets or open questions met the strict vault standards.

### Approved Concepts
- Matroid Parity TSP Construction: Provides a novel technique using matroid parity to construct TSP tours for stochastic vehicle routing, strictly improving prior approximation ratios.

## Links

- [Abstract](https://arxiv.org/abs/2610.16802)
- [PDF](https://arxiv.org/pdf/2610.16802)

