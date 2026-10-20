---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximations for Vehicle Routing with Nonuniform Speeds"
description: "This paper studies vehicle routing problems involving vehicles with different speeds and capacities to minimize the maximum completion time across vehicles. The author presents improved theoretical approximation algorithms for the heterogeneous traveling salesman problem (HetTSP) as well as both split-delivery and unsplit-delivery variants of the heterogeneous capacitated vehicle routing problem (HetCVRP). Specifically, the work achieves a 6-approximation for HetTSP and upper bounds under 8 and 10 for the respective HetCVRP variants, substantially improving prior asymptotic and large-constant approximation bounds."
resource: "https://arxiv.org/abs/2610.12195"
tags:
  - "approximation-algorithms"
  - "vehicle-routing-problem"
timestamp: "2026-10-20T09:45:37Z"

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
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-20T09:45:37Z"
created_at: "2026-10-20T09:45:37Z"
---

# Improved Approximations for Vehicle Routing with Nonuniform Speeds

**Authors**: Hong Li
**Date**: 2026-10-08
**Paper ID**: [openalex:2610.12195](https://arxiv.org/abs/2610.12195)

## Summary

This paper studies vehicle routing problems involving vehicles with different speeds and capacities to minimize the maximum completion time across vehicles. The author presents improved theoretical approximation algorithms for the heterogeneous traveling salesman problem (HetTSP) as well as both split-delivery and unsplit-delivery variants of the heterogeneous capacitated vehicle routing problem (HetCVRP). Specifically, the work achieves a 6-approximation for HetTSP and upper bounds under 8 and 10 for the respective HetCVRP variants, substantially improving prior asymptotic and large-constant approximation bounds.

## Key Contributions

- Proposes a 6-approximation algorithm for the heterogeneous traveling salesman problem (HetTSP), improving upon the previous 90(1+δ)-approximation.
- Proposes a (9/2 + 2\sqrt{3}) < 7.965-approximation algorithm for the split-delivery heterogeneous capacitated vehicle routing problem (HetCVRP).
- Proposes a (11/2 + 3\sqrt{2}) < 9.743-approximation algorithm for the unsplit-delivery heterogeneous capacitated vehicle routing problem (HetCVRP), improving upon the previous 450(1+δ)-approximation.

## Limitations

The paper focuses on theoretical approximation algorithms for vehicle routing with nonuniform speeds; empirical evaluations on real-world instances are not discussed in the abstract.

## Archivist Review

No concepts or datasets were proposed in the analysis, and the sole open question represents a standard request for tighter theoretical bounds on a specific graph theory problem rather than a broadly applicable architectural or methodological research bottleneck.

### Rejected Candidates
- [open_question] Improved Approximations for Nonuniform Speeds (`improved-approximations-nonuniform-speeds-bounds`) - low_impact: Standard theoretical complexity open question asking for tighter bounds on a specific problem variant without identifying a broader structural bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.12195)
- [PDF](https://arxiv.org/pdf/2610.12195)

