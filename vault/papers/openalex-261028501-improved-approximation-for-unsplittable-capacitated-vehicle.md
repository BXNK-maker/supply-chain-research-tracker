---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees"
description: "This paper presents a deterministic (5/2 + \\epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) under general capacity and arbitrary positive demands. The approach uses local search, endpoint quota trees, matching, set packing, and weighted graphic matroid parity to construct disjoint client routes. This improves upon previous approximation ratios such as the recent (2 + \\ln 2 + \\epsilon)-approximation."
resource: "https://arxiv.org/abs/2610.28501"
tags:
  - "approximation-algorithms"
  - "vehicle-routing-problem"
timestamp: "2026-10-27T10:10:26Z"

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
    description: "A structural tree construction used in routing algorithms to select endpoint quotas for candidate routes after demand rounding and vertex replication."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-27T10:10:26Z"
created_at: "2026-10-27T10:10:26Z"
---

# Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees

**Authors**: Zhenyu Wang
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.28501](https://arxiv.org/abs/2610.28501)

## Summary

This paper presents a deterministic (5/2 + \epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) under general capacity and arbitrary positive demands. The approach uses local search, endpoint quota trees, matching, set packing, and weighted graphic matroid parity to construct disjoint client routes. This improves upon previous approximation ratios such as the recent (2 + \ln 2 + \epsilon)-approximation.

## Key Contributions

- Provides a deterministic (5/2 + \epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) running in n^{O(1/\epsilon)} time.
- Handles general capacity and arbitrary positive demands through local search route selection combined with endpoint quota trees, matching, and set packing.
- Employs weighted graphic matroid parity to partition a constructed tour for serving remaining clients with disjoint client sets.

## Limitations

Runs in polynomial time n^{O(1/\epsilon)} which depends exponentially on 1/\epsilon.

## Key Concepts

- [[quota-trees]]: A structural tree construction used in routing algorithms to select endpoint quotas for candidate routes after demand rounding and vertex replication.

## Archivist Review

Approved the existing concept 'quota-trees' which is already present in the vault as a canonical entry and is central to this paper's algorithmic contributions. Rejected the standard problem definition since UCVRP is a classical operations research/theoretical computer science problem.

### Approved Concepts
- Quota Trees: Quota trees are the primary structural mechanism introduced and utilized to construct candidate routes for the UCVRP algorithm.

### Rejected Candidates
- [concept] Unsplittable Capacitated Vehicle Routing Problem (`unsplittable-capacitated-vehicle-routing-problem`) - not_novel: Standard well-known problem rather than a newly introduced machine learning or algorithmic concept.

## Links

- [Abstract](https://arxiv.org/abs/2610.28501)
- [PDF](https://arxiv.org/pdf/2610.28501)

