---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximations for Vehicle Routing with Nonuniform Speeds"
description: "This paper studies vehicle routing problems involving vehicles with nonuniform speeds on metric graphs, aiming to minimize the maximum completion time across vehicles. For the heterogeneous traveling salesman problem (HetTSP), the author provides an improved 6-approximation algorithm. Furthermore, for the heterogeneous capacitated vehicle routing problem (HetCVRP), the author presents a ~7.965-approximation algorithm for the split-delivery version and a ~9.743-approximation algorithm for the unsplit-delivery version, substantially improving prior approximation bounds."
resource: "https://arxiv.org/abs/2610.12195"
tags:
  - "approximation-algorithms"
  - "vehicle-routing-problem"
timestamp: "2026-10-15T09:33:25Z"

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
    description: "Closing the gap between current constant-factor approximations and inapproximability lower bounds for heterogeneous vehicle routing problems (HetTSP and HetCVRP) remains an important open direction."
skill: "GeneralMLSkill"
processed_at: "2026-10-15T09:33:25Z"
created_at: "2026-10-15T09:33:25Z"
---

# Improved Approximations for Vehicle Routing with Nonuniform Speeds

**Authors**: Hong Li
**Date**: 2026-10-08
**Paper ID**: [openalex:2610.12195](https://arxiv.org/abs/2610.12195)

## Summary

This paper studies vehicle routing problems involving vehicles with nonuniform speeds on metric graphs, aiming to minimize the maximum completion time across vehicles. For the heterogeneous traveling salesman problem (HetTSP), the author provides an improved 6-approximation algorithm. Furthermore, for the heterogeneous capacitated vehicle routing problem (HetCVRP), the author presents a ~7.965-approximation algorithm for the split-delivery version and a ~9.743-approximation algorithm for the unsplit-delivery version, substantially improving prior approximation bounds.

## Key Contributions

- Proposed a 6-approximation algorithm for the heterogeneous traveling salesman problem (HetTSP), significantly improving over the previous 90(1+δ)-approximation.
- Developed a (9/2 + 2√3)-approximation algorithm (approx. 7.965) for the split-delivery version of the heterogeneous capacitated vehicle routing problem (HetCVRP).
- Developed an (11/2 + 3√2)-approximation algorithm (approx. 9.743) for the unsplit-delivery version of HetCVRP, improving over the previous 450(1+δ)-approximation.

## Limitations

The paper focuses on theoretical approximation guarantees for vehicle routing with nonuniform speeds; empirical evaluations on real-world instances are not discussed.

## Open Questions & Future Work

- [[improved-approximations-heterogeneous-vehicle-routing]]

## Archivist Review

The paper presents theoretical approximation algorithms for vehicle routing with nonuniform speeds. The proposed open question is a duplicate of an existing vault entry ('improved-approximations-heterogeneous-vehicle-routing'), so it was rejected in favor of the existing note, and no new concepts or datasets met the strict novelty or reusability standards.

### Approved Open Questions
- Tight bounds for heterogeneous vehicle routing: Determining tight approximation bounds helps establish the fundamental computational complexity limits for vehicle routing with heterogeneous vehicle speeds and capacities.

### Rejected Candidates
- [open_question] Tight bounds for heterogeneous vehicle routing (`improving-heterogeneous-vehicle-routing-bounds`) - duplicate_existing: A very similar open question regarding heterogeneous vehicle routing already exists in the vault under the slug 'improved-approximations-heterogeneous-vehicle-routing'.

## Links

- [Abstract](https://arxiv.org/abs/2610.12195)
- [PDF](https://arxiv.org/pdf/2610.12195)

