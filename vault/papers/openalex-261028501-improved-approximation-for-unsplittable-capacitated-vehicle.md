---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees"
description: "The paper presents a deterministic (5/2 + \\epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP), improving upon the previous (2 + \\ln 2 + \\epsilon)-approximation. The method combines local search, endpoint quota trees with rounded demands, matching, set packing, and weighted graphic matroid parity techniques. This approach applies to general capacities and arbitrary positive client demands while operating in polynomial time for fixed \\epsilon."
resource: "https://arxiv.org/abs/2610.28501"
tags:
  - "vehicle-routing-problem"
  - "approximation-algorithms"
timestamp: "2026-11-03T12:37:43Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Zhenyu Wang"
issued:
  date-parts:
    - [2026, 10, 20]

# Domain-specific custom fields
paper_id: "2610.28501"
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
processed_at: "2026-11-03T12:37:43Z"
created_at: "2026-11-03T12:37:43Z"
---

# Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees

**Authors**: Zhenyu Wang
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.28501](https://arxiv.org/abs/2610.28501)

## Summary

The paper presents a deterministic (5/2 + \epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP), improving upon the previous (2 + \ln 2 + \epsilon)-approximation. The method combines local search, endpoint quota trees with rounded demands, matching, set packing, and weighted graphic matroid parity techniques. This approach applies to general capacities and arbitrary positive client demands while operating in polynomial time for fixed \epsilon.

## Key Contributions

- Proposes a deterministic (5/2 + \epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) running in n^{O(1/\epsilon)} time.
- Introduces endpoint quota trees for constructing candidate routes after demand rounding and vertex duplication.
- Combines local search, matching, set packing, and weighted graphic matroid parity tour partitioning to handle general capacities and arbitrary positive demands.

## Archivist Review

No concepts, datasets, or open questions met the stringent bar for permanent vault addition. The open question regarding the UCVRP approximation ratio is too narrow and specific to theoretical operations research rather than representing a broad, foundational machine learning research direction.

### Rejected Candidates
- [open_question] Improving UCVRP Approximation Ratio (`improving-ucvrp-approximation-ratio`) - low_impact: This open question concerns tightening the approximation ratio for a specific algorithmic problem, which is standard incremental theory work rather than a foundational bottleneck across diverse ML paradigms.

## Links

- [Abstract](https://arxiv.org/abs/2610.28501)
- [PDF](https://arxiv.org/pdf/2610.28501)

