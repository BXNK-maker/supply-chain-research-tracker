---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Matrix-Based Ant Colony Search with Batched Decoding for Hierarchical Replenishment Routing: A Stylized Case Study Based on Korean City Data"
description: "This paper investigates a single-vehicle hierarchical replenishment-routing problem where cities act as both demand and supply points under capacity and detour constraints. To address this, the authors propose a matrix-based ant colony optimization algorithm featuring batched decoding and local search evaluations, evaluated on a newly constructed 100-node benchmark based on Korean geographic and population data. Experimental results show that the proposed approach achieves competitive routing performance compared to genetic algorithms and standard ant systems, with ablation studies highlighting the critical role of batched local search."
resource: "https://arxiv.org/abs/2611.15338"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-11-20T13:47:12Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jun Zhang"
  - literal: "Weijie Yu"
  - literal: "Qian Tong"
  - literal: "Eui Jeong Kwak"
  - literal: "Sang-Woon Jeon"
  - literal: "Hua Ding"
  - literal: "Qijia Jiang"
  - literal: "Hu Jin"
  - literal: "Haewoon Nam"
  - literal: "Changjun Zhou"
issued:
  date-parts:
    - [2026, 11, 11]

# Domain-specific custom fields
paper_id: "2611.15338"
paper_source: "openalex"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "exact-reload-sub-problem-quantification"
    description: "Quantifying the optimality gap introduced by fixed greedy decoding policies versus exact reload sub-problems remains an open problem in replenishment routing optimization."
  - name: "route-anticipating-aco-construction-rules"
    description: "Developing route construction rules that effectively anticipate the remaining route and future replenishment needs during ant colony optimization remains an unresolved challenge."
skill: "GeneralMLSkill"
processed_at: "2026-11-20T13:47:12Z"
created_at: "2026-11-20T13:47:12Z"
---

# Matrix-Based Ant Colony Search with Batched Decoding for Hierarchical Replenishment Routing: A Stylized Case Study Based on Korean City Data

**Authors**: Jun Zhang, Weijie Yu, Qian Tong, Eui Jeong Kwak, Sang-Woon Jeon, Hua Ding, Qijia Jiang, Hu Jin, Haewoon Nam, Changjun Zhou
**Date**: 2026-11-11
**Paper ID**: [openalex:2611.15338](https://arxiv.org/abs/2611.15338)

## Summary

This paper investigates a single-vehicle hierarchical replenishment-routing problem where cities act as both demand and supply points under capacity and detour constraints. To address this, the authors propose a matrix-based ant colony optimization algorithm featuring batched decoding and local search evaluations, evaluated on a newly constructed 100-node benchmark based on Korean geographic and population data. Experimental results show that the proposed approach achieves competitive routing performance compared to genetic algorithms and standard ant systems, with ablation studies highlighting the critical role of batched local search.

## Key Contributions

- Introduces a matrix-based ant colony optimization (MACO) approach coupled with a fixed greedy replenishment-decoding policy and batched local search evaluation for hierarchical replenishment routing.
- Builds a 100-node hierarchical replenishment routing benchmark from Korean population and geographic data across 10 distinct levels with geometric constraints.
- Demonstrates that MACO achieves competitive performance compared to genetic algorithms and MAX-MIN ant systems, while ablation studies identify batched local search as the primary driver of solution quality.

## Limitations

Stylized case study evaluated on a single 100-node instance derived from Korean data; load-aware transition factors yield no significant gain within tested ranges.

## Open Questions & Future Work

- [[exact-reload-sub-problem-quantification]]
- [[route-anticipating-aco-construction-rules]]

## Archivist Review

The proposed open questions are duplicates of existing vault entries (exact-reload-sub-problem-quantification and route-anticipating-aco-construction-rules). No new concepts or datasets meet the high bar for standalone vault notes.

### Approved Open Questions
- Quantifying Reload Decoding Gap: Important for understanding the theoretical limitations of greedy decoding policies versus exact formulations in replenishment-constrained routing problems.
- Route-Anticipating Construction Rules: Critical for enhancing forward-looking metaheuristic construction mechanisms in complex supply and inventory routing domains.

### Rejected Candidates
- [open_question] Quantifying Reload Decoding Gap (`exact-reload-sub-problem-quantification`) - duplicate_existing: This open question is already present in the vault under the exact-reload-sub-problem-quantification slug.
- [open_question] Route-Anticipating Construction Rules (`route-anticipating-aco-construction-rules`) - duplicate_existing: This open question is synonymous with route-anticipating-aco-construction-rules which is already tracked in the vault.

## Links

- [Abstract](https://arxiv.org/abs/2611.15338)
- [PDF](https://arxiv.org/pdf/2611.15338)

