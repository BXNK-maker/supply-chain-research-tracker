---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees"
description: "This paper studies the Unsplittable Capacitated Vehicle Routing Problem (UCVRP), presenting a deterministic $(5/2+\\varepsilon)$-approximation algorithm that runs in polynomial time for any rational $\\varepsilon>0$. The approach improves upon existing approximation ratios by leveraging endpoint quota trees, local search, demand rounding, vertex copies, and weighted graphic matroid parity. This advances the theoretical understanding of vehicle routing problems combining metric travel costs and bin packing difficulties."
resource: "https://arxiv.org/abs/2610.28501"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "approximation-algorithms"
timestamp: "2026-10-30T11:08:57Z"

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
processed_at: "2026-10-30T11:08:57Z"
created_at: "2026-10-30T11:08:57Z"
---

# Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees

**Authors**: Zhenyu Wang
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.28501](https://arxiv.org/abs/2610.28501)

## Summary

This paper studies the Unsplittable Capacitated Vehicle Routing Problem (UCVRP), presenting a deterministic $(5/2+\varepsilon)$-approximation algorithm that runs in polynomial time for any rational $\varepsilon>0$. The approach improves upon existing approximation ratios by leveraging endpoint quota trees, local search, demand rounding, vertex copies, and weighted graphic matroid parity. This advances the theoretical understanding of vehicle routing problems combining metric travel costs and bin packing difficulties.

## Key Contributions

- Proposes a deterministic $(5/2+\varepsilon)$-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) running in $n^{O(1/\varepsilon)}$ time.
- Improves upon the previous state-of-the-art $(2+\ln 2+\varepsilon)$-approximation by Zhao and Xiao (2026).
- Utilizes endpoint quota trees combined with local search, matching, set packing, and weighted graphic matroid parity.

## Archivist Review

Applied strict selectivity standards: quota-trees is a paper-specific combinatorial technique rather than a broad reusable ML/optimization primitive, and the open question is a narrow problem extension rather than a major foundational bottleneck.

### Rejected Candidates
- [concept] Quota Trees (`quota-trees`) - not_reusable: Quota trees are a highly specialized combinatorial construction specific to this specific vehicle routing approximation algorithm, lacking broad recurrence across general machine learning or optimization methods.
- [open_question] Extension to Capacitated Arc Routing (`carp-unsplittable-demands-extension`) - low_impact: This is a routine technical extension of an approximation algorithm to a closely related problem variant (arc routing) rather than a fundamental open research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.28501)
- [PDF](https://arxiv.org/pdf/2610.28501)

