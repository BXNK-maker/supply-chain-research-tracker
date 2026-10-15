---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximations for Vehicle Routing with Nonuniform Speeds"
description: "This paper studies vehicle routing problems involving vehicles with nonuniform speeds and the objective of minimizing the maximum completion time. The author presents improved approximation algorithms for the heterogeneous traveling salesman problem (HetTSP) and both the split-delivery and unsplit-delivery versions of the heterogeneous capacitated vehicle routing problem (HetCVRP). Specifically, the paper improves the approximation ratio for HetTSP to 6 and for unsplit-delivery HetCVRP to below 9.743, while establishing a sub-8 approximation for split-delivery HetCVRP."
resource: "https://arxiv.org/abs/2610.12195"
tags:
  - "machine-learning"
  - "approximation-algorithms"
  - "vehicle-routing-problem"
timestamp: "2026-10-15T04:43:35Z"

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
  - name: "improved-approximations-heterogeneous-vehicle-routing"
    description: "Determine whether the approximation guarantees for the heterogeneous traveling salesman problem (HetTSP) and heterogeneous capacitated vehicle routing problem (HetCVRP) with nonuniform speeds can be further improved, or if there is a fundamental lower bound limit for these approximation ratios using tour-splitting and layer partitioning frameworks."
skill: "GeneralMLSkill"
processed_at: "2026-10-15T04:43:35Z"
created_at: "2026-10-15T04:43:35Z"
---

# Improved Approximations for Vehicle Routing with Nonuniform Speeds

**Authors**: Hong Li
**Date**: 2026-10-08
**Paper ID**: [openalex:2610.12195](https://arxiv.org/abs/2610.12195)

## Summary

This paper studies vehicle routing problems involving vehicles with nonuniform speeds and the objective of minimizing the maximum completion time. The author presents improved approximation algorithms for the heterogeneous traveling salesman problem (HetTSP) and both the split-delivery and unsplit-delivery versions of the heterogeneous capacitated vehicle routing problem (HetCVRP). Specifically, the paper improves the approximation ratio for HetTSP to 6 and for unsplit-delivery HetCVRP to below 9.743, while establishing a sub-8 approximation for split-delivery HetCVRP.

## Key Contributions

- Gives a 6-approximation algorithm for the heterogeneous traveling salesman problem (HetTSP), improving the previous 90(1+δ)-approximation.
- Gives a 4.965-approximation (9/2 + 2\sqrt{3}) algorithm for the split-delivery version of the heterogeneous capacitated vehicle routing problem (HetCVRP).
- Gives a 9.743-approximation (11/2 + 3\sqrt{2}) algorithm for the unsplit-delivery version of HetCVRP, improving the previous 450(1+δ)-approximation.

## Limitations

The paper provides theoretical approximation algorithms for vehicle routing with nonuniform speeds; empirical evaluations on real-world instances are not mentioned in the abstract.

## Open Questions & Future Work

- [[improved-approximations-heterogeneous-vehicle-routing]]

## Archivist Review

Applied strict screening standards. No concepts from this theoretical operations research / algorithms paper are general enough or central to machine learning vault interests to warrant permanent notes. One open question addressing approximation ratios in heterogeneous vehicle routing is retained as it represents a core theoretical bottleneck.

### Approved Open Questions
- Improved Approximations for Heterogeneous Vehicle Routing: Closing the gap between upper and lower bounds for vehicle routing with nonuniform speeds is a core open problem in approximation algorithms for heterogeneous logistics.

## Links

- [Abstract](https://arxiv.org/abs/2610.12195)
- [PDF](https://arxiv.org/pdf/2610.12195)

