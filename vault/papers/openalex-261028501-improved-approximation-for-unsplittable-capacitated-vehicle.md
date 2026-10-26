---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees"
description: "This paper presents a deterministic (5/2 + \\epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) with arbitrary positive demands. By combining endpoint quota trees, local search, matching, set packing, and weighted graphic matroid parity, the proposed method improves upon existing approximation bounds. The algorithm runs in polynomial time n^{O(1/\\epsilon)} for rational \\epsilon > 0."
resource: "https://arxiv.org/abs/2610.28501"
tags:
  - "approximation-algorithms"
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-26T10:42:33Z"

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
    description: "A tree-based structure used to construct candidate routes in vehicle routing approximation algorithms."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-26T10:42:33Z"
created_at: "2026-10-26T10:42:33Z"
---

# Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees

**Authors**: Zhenyu Wang
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.28501](https://arxiv.org/abs/2610.28501)

## Summary

This paper presents a deterministic (5/2 + \epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) with arbitrary positive demands. By combining endpoint quota trees, local search, matching, set packing, and weighted graphic matroid parity, the proposed method improves upon existing approximation bounds. The algorithm runs in polynomial time n^{O(1/\epsilon)} for rational \epsilon > 0.

## Key Contributions

- Proposed a deterministic (5/2 + \epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) running in n^{O(1/\epsilon)} time.
- Improved upon the previous (2 + \ln 2 + \epsilon)-approximation by Zhao and Xiao (2026) for general capacity and arbitrary positive demands.
- Utilized endpoint quota trees, demand rounding, and vertex copies combined with weighted graphic matroid parity to construct disjoint routes and achieve better approximation bounds.

## Limitations

The algorithm runs in polynomial time n^{O(1/\epsilon)} depending on the approximation parameter \epsilon.

## Key Concepts

- [[quota-trees]]: A tree-based structure used to construct candidate routes in vehicle routing approximation algorithms.

## Archivist Review

Approved the core algorithmic concept 'quota-trees' which is already registered in the vault. No datasets or open questions were proposed or needed.

### Approved Concepts
- Quota Trees: Central algorithmic novelty used to construct candidate routes for the UCVRP approximation algorithm.

## Links

- [Abstract](https://arxiv.org/abs/2610.28501)
- [PDF](https://arxiv.org/pdf/2610.28501)

