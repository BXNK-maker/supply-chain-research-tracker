---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximations for Vehicle Routing with Nonuniform Speeds"
description: "This paper studies vehicle routing problems involving vehicles with nonuniform speeds, aiming to minimize the maximum completion time among all vehicles. The author presents improved approximation algorithms for three core variants: the heterogeneous traveling salesman problem (HetTSP) and both split-delivery and unsplit-delivery versions of the heterogeneous capacitated vehicle routing problem (HetCVRP). These results significantly improve the approximation guarantees compared to existing literature."
resource: "https://arxiv.org/abs/2610.12195"
tags:
  - "vehicle-routing-problem"
  - "approximation-algorithms"
timestamp: "2026-10-22T09:46:25Z"

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
  - name: "improving-heterogeneous-vehicle-routing-approximation-bounds"
    description: "Determine whether the approximation guarantees for the heterogeneous traveling salesman problem (HetTSP) and the heterogeneous capacitated vehicle routing problem (HetCVRP) can be further improved, or if there exist matching lower bounds establishing the optimal approximation factors for these problems."
skill: "GeneralMLSkill"
processed_at: "2026-10-22T09:46:25Z"
created_at: "2026-10-22T09:46:25Z"
---

# Improved Approximations for Vehicle Routing with Nonuniform Speeds

**Authors**: Hong Li
**Date**: 2026-10-08
**Paper ID**: [openalex:2610.12195](https://arxiv.org/abs/2610.12195)

## Summary

This paper studies vehicle routing problems involving vehicles with nonuniform speeds, aiming to minimize the maximum completion time among all vehicles. The author presents improved approximation algorithms for three core variants: the heterogeneous traveling salesman problem (HetTSP) and both split-delivery and unsplit-delivery versions of the heterogeneous capacitated vehicle routing problem (HetCVRP). These results significantly improve the approximation guarantees compared to existing literature.

## Key Contributions

- Achieves a 6-approximation algorithm for the heterogeneous traveling salesman problem (HetTSP), improving upon the previous $90(1+\delta)$-approximation.
- Proposes a $(\frac{9}{2}+2\sqrt{3}) < 7.965$-approximation algorithm for the split-delivery version of the heterogeneous capacitated vehicle routing problem (HetCVRP).
- Achieves an $(\frac{11}{2}+3\sqrt{2}) < 9.743$-approximation algorithm for the unsplit-delivery version of HetCVRP, improving upon the previous $450(1+\delta)$-approximation.

## Open Questions & Future Work

- [[improving-heterogeneous-vehicle-routing-approximation-bounds]]

## Archivist Review

Applied rigorous selectivity for the ML/algorithms vault. No distinct reusable conceptual modules were introduced, but the open question regarding approximation bounds for heterogeneous vehicle routing is preserved as a valuable theoretical direction.

### Approved Open Questions
- Improved Approximation Bounds for Heterogeneous Routing: Closing the gap between upper and lower bounds for vehicle routing with nonuniform speeds is a fundamental open direction in approximation algorithms for heterogeneous routing.

### Rejected Candidates
- [open_question] Improved Approximation Bounds for Heterogeneous Routing (`improving-heterogeneous-vehicle-routing-approximation-bounds`) - other: Approved as a valuable open research direction in approximation algorithms.

## Links

- [Abstract](https://arxiv.org/abs/2610.12195)
- [PDF](https://arxiv.org/pdf/2610.12195)

