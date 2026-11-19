---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Matrix-Based Ant Colony Search with Batched Decoding for Hierarchical Replenishment Routing: A Stylized Case Study Based on Korean City Data"
description: "This paper studies a single-vehicle replenishment-routing problem on a 100-node hierarchical network derived from Korean city data, where vehicles must detour to previously visited supply points when capacity is exhausted. To solve this, the authors propose a matrix-based ant colony optimization algorithm equipped with a fixed greedy replenishment-decoding policy and batched local search. Experimental evaluations demonstrate competitive performance against genetic algorithms and MAX-MIN ant systems, while ablation studies highlight the dominance of batched local search over load-aware transition factors."
resource: "https://arxiv.org/abs/2611.15338"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-11-19T14:03:41Z"

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
    description: "Quantifying the optimality gap introduced by fixed greedy reloading policies through exact reload sub-problems remains an open direction for replenishment routing models."
  - name: "route-anticipating-aco-construction-rules"
    description: "Developing ant colony construction rules that actively anticipate remaining route structures and multi-step reload requirements remains an open challenge."
skill: "GeneralMLSkill"
processed_at: "2026-11-19T14:03:41Z"
created_at: "2026-11-19T14:03:41Z"
---

# Matrix-Based Ant Colony Search with Batched Decoding for Hierarchical Replenishment Routing: A Stylized Case Study Based on Korean City Data

**Authors**: Jun Zhang, Weijie Yu, Qian Tong, Eui Jeong Kwak, Sang-Woon Jeon, Hua Ding, Qijia Jiang, Hu Jin, Haewoon Nam, Changjun Zhou
**Date**: 2026-11-11
**Paper ID**: [openalex:2611.15338](https://arxiv.org/abs/2611.15338)

## Summary

This paper studies a single-vehicle replenishment-routing problem on a 100-node hierarchical network derived from Korean city data, where vehicles must detour to previously visited supply points when capacity is exhausted. To solve this, the authors propose a matrix-based ant colony optimization algorithm equipped with a fixed greedy replenishment-decoding policy and batched local search. Experimental evaluations demonstrate competitive performance against genetic algorithms and MAX-MIN ant systems, while ablation studies highlight the dominance of batched local search over load-aware transition factors.

## Key Contributions

- Proposed a matrix-based ant colony optimization algorithm (MACO) with batched decoding for hierarchical replenishment routing, achieving a mean total distance of 3081.7 km on a 100-node Korean city benchmark.
- Demonstrated through ablation that batch local search is the primary contributor to solution quality in the proposed hierarchical replenishment framework, while load-aware transition factors yield no significant gain.
- Analyzed structural sensitivities in a stylized national logistics network, showing that raising supply coefficients in lower-level cities shortens routes more effectively than relaxing stop limits.

## Open Questions & Future Work

- [[exact-reload-sub-problem-quantification]]
- [[route-anticipating-aco-construction-rules]]

## Archivist Review

Applied strict selectivity criteria. No new concepts warranted permanent vault notes as the core methods are paper-specific routing heuristics. Two open questions regarding reload sub-problem quantification and route-anticipating construction rules were approved as they represent fundamental methodological gaps in constrained vehicle routing.

### Approved Open Questions
- Quantifying Greedy Policy Gaps: Understanding the exact cost discrepancy between greedy decoding policies and optimal reload scheduling is crucial for evaluating and refining large-scale logistics routing heuristics.
- Route-Anticipating ACO Construction Rules: Designing multi-step lookahead or route-anticipating transition rules is vital for improving metaheuristic search efficiency in constrained inventory and replenishment routing domains.

### Rejected Candidates
- [concept] Matrix-Based Ant Colony Search (`matrix-based-ant-colony-search`) - duplicate_existing: Already exists in the vault under matrix-based-ant-colony-search.

## Links

- [Abstract](https://arxiv.org/abs/2611.15338)
- [PDF](https://arxiv.org/pdf/2611.15338)

