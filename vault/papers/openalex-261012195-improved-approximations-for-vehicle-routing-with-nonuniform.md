---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximations for Vehicle Routing with Nonuniform Speeds"
description: "This paper studies vehicle routing problems with vehicles having nonuniform speeds, focusing on minimizing the maximum completion time (makespan). For the heterogeneous traveling salesman problem (HetTSP), the author presents an improved 6-approximation algorithm. Additionally, for the heterogeneous capacitated vehicle routing problem (HetCVRP), the author provides approximation algorithms with guarantees below 7.965 and 9.743 for the split-delivery and unsplit-delivery variants, respectively, significantly improving upon prior asymptotic approximations."
resource: "https://arxiv.org/abs/2610.12195"
tags:
  - "approximation-algorithms"
  - "vehicle-routing-problem"
timestamp: "2026-10-17T08:57:41Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Hong Li"
issued:
  date-parts:
    - [2026, 10, 8]

# Domain-specific custom fields
paper_id: "2610.12195"
paper_source: "openalex"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "tight-approximation-bounds-heterogeneous-vehicle-routing"
    description: "The authors note specific approximation ratios achieved for HetTSP, split-delivery HetCVRP, and unsplit-delivery HetCVRP, but whether these bounds can be further tightened or matched by lower bounds (or optimal approximation limits) for vehicle routing with nonuniform speeds remains an open direction for future exploration."
skill: "GeneralMLSkill"
processed_at: "2026-10-17T08:57:41Z"
created_at: "2026-10-17T08:57:41Z"
---

# Improved Approximations for Vehicle Routing with Nonuniform Speeds

**Authors**: Hong Li
**Date**: 2026-10-08
**Paper ID**: [openalex:2610.12195](https://arxiv.org/abs/2610.12195)

## Summary

This paper studies vehicle routing problems with vehicles having nonuniform speeds, focusing on minimizing the maximum completion time (makespan). For the heterogeneous traveling salesman problem (HetTSP), the author presents an improved 6-approximation algorithm. Additionally, for the heterogeneous capacitated vehicle routing problem (HetCVRP), the author provides approximation algorithms with guarantees below 7.965 and 9.743 for the split-delivery and unsplit-delivery variants, respectively, significantly improving upon prior asymptotic approximations.

## Key Contributions

- Achieves a 6-approximation algorithm for the heterogeneous traveling salesman problem (HetTSP), improving upon the previous $90(1+\delta)$-approximation.
- Provides a $(\frac{9}{2}+2\sqrt{3}) < 7.965$-approximation algorithm for the split-delivery version of the heterogeneous capacitated vehicle routing problem (HetCVRP).
- Provides an $(\frac{11}{2}+3\sqrt{2}) < 9.743$-approximation algorithm for the unsplit-delivery version of HetCVRP, improving upon the previous $450(1+\delta)$-approximation.

## Limitations

The paper focuses on theoretical approximation guarantees for vehicle routing with nonuniform speeds; empirical evaluations on large-scale real-world instances are not discussed.

## Open Questions & Future Work

- [[tight-approximation-bounds-heterogeneous-vehicle-routing]]

## Archivist Review

Applied strict scarcity and reusability standards. No reusable methodology or architectural primitive was identified as a standalone concept, so concepts were rejected. The open question regarding tight approximation bounds for heterogeneous vehicle routing is retained as it represents a fundamental open theoretical problem in combinatorial optimization.

### Approved Open Questions
- Tight Approximation Bounds for Heterogeneous Vehicle Routing: Determining the tight approximation limits for heterogeneous routing problems with nonuniform vehicle speeds is a central open question in approximation algorithms for logistics and transportation.

### Rejected Candidates
- [concept] Heterogeneous Traveling Salesman Problem (HetTSP) (`heterogeneous-traveling-salesman-problem`) - paper_local: This is a specific problem definition in theoretical computer science rather than a reusable methodological concept or architectural pattern.
- [concept] Heterogeneous Capacitated Vehicle Routing Problem (HetCVRP) (`heterogeneous-capacitated-vehicle-routing-problem`) - paper_local: This is a specific problem variant studied in the paper rather than a general methodological concept.

## Links

- [Abstract](https://arxiv.org/abs/2610.12195)
- [PDF](https://arxiv.org/pdf/2610.12195)

