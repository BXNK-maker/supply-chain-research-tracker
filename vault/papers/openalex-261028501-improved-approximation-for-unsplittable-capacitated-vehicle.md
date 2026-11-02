---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees"
description: "This paper presents a deterministic (5/2 + epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) with general capacity and arbitrary positive demands. The method employs local search combined with endpoint quota trees, demand rounding, vertex copies, matching, set packing, and weighted graphic matroid parity to achieve an improved approximation ratio."
resource: "https://arxiv.org/abs/2610.28501"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "approximation-algorithms"
timestamp: "2026-11-02T13:06:29Z"

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
  - name: "quota-trees"
    description: "A tree-based routing structure used to construct candidate routes in capacitated vehicle routing problems."
datasets:
  []
open_questions:
  - name: "ucvrp-to-carp-extension"
    description: "Developing an extension of the (5/2 + \\\\epsilon)-approximation algorithm and analysis using endpoint quota trees and tour construction for the single-depot undirected capacitated arc routing problem (CARP) with unsplittable demands."
skill: "GeneralMLSkill"
processed_at: "2026-11-02T13:06:29Z"
created_at: "2026-11-02T13:06:29Z"
---

# Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees

**Authors**: Zhenyu Wang
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.28501](https://arxiv.org/abs/2610.28501)

## Summary

This paper presents a deterministic (5/2 + epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) with general capacity and arbitrary positive demands. The method employs local search combined with endpoint quota trees, demand rounding, vertex copies, matching, set packing, and weighted graphic matroid parity to achieve an improved approximation ratio.

## Key Contributions

- Proposes a deterministic (5/2 + epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) running in n^{O(1/epsilon)} time.
- Applies the algorithm to general capacity and arbitrary positive demands through local search, endpoint quota trees, demand rounding, and vertex copies.
- Combines routing structures with matching, set packing, and weighted graphic matroid parity tour partitioning to handle remaining clients.

## Limitations

The time complexity is n^{O(1/epsilon)}, which depends polynomially on 1/epsilon in the exponent for rational epsilon <= 1/9.

## Open Questions & Future Work

- [[ucvrp-to-carp-extension]]

## Key Concepts

- [[quota-trees]]: A tree-based routing structure used to construct candidate routes in capacitated vehicle routing problems.

## Archivist Review

Approved quota-trees as a novel concept note. Reused the existing canonical ucvrp-to-carp-extension slug for the open question, while rejecting the redundant problem-definition concept as UCVRP is standard.

### Approved Concepts
- Quota Trees: Central to constructing candidate routes for the UCVRP approximation algorithm.

### Approved Open Questions
- Capacitated Arc Routing Problem Extension: Extending advanced vehicle routing techniques and quota tree approaches to arc routing problems generalizes the applicability of these approximation frameworks.

### Rejected Candidates
- [concept] Unsplittable Capacitated Vehicle Routing Problem (UCVRP) (`unsplittable-capacitated-vehicle-routing-problem`) - duplicate_existing: Already present or subsumed by existing problem definitions in combinatorial optimization.

## Links

- [Abstract](https://arxiv.org/abs/2610.28501)
- [PDF](https://arxiv.org/pdf/2610.28501)

