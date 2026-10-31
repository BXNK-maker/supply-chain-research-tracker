---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees"
description: "This paper presents an improved deterministic (5/2 + epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) with general capacity and arbitrary positive demands. The method runs in n^{O(1/epsilon)} time and improves upon existing bounds by constructing candidate routes using endpoint quota trees, local search, matching, set packing, and weighted graphic matroid parity."
resource: "https://arxiv.org/abs/2610.28501"
tags:
  - "combinatorial-optimization"
  - "approximation-algorithms"
  - "vehicle-routing-problem"
timestamp: "2026-10-31T10:42:47Z"

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
    description: "A combinatorial tree structure used to construct candidate routes in vehicle routing approximation algorithms."
datasets:
  []
open_questions:
  - name: "ucvrp-to-carp-extension"
    description: "Extending the single-depot undirected capacitated arc routing problem (CARP) with unsplittable demands to achieve the same (5/2 + \\varepsilon)-approximation guarantee using additional arguments for serving entire edges."
skill: "GeneralMLSkill"
processed_at: "2026-10-31T10:42:47Z"
created_at: "2026-10-31T10:42:47Z"
---

# Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees

**Authors**: Zhenyu Wang
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.28501](https://arxiv.org/abs/2610.28501)

## Summary

This paper presents an improved deterministic (5/2 + epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) with general capacity and arbitrary positive demands. The method runs in n^{O(1/epsilon)} time and improves upon existing bounds by constructing candidate routes using endpoint quota trees, local search, matching, set packing, and weighted graphic matroid parity.

## Key Contributions

- Proposed a deterministic (5/2 + epsilon)-approximation algorithm running in n^{O(1/epsilon)} time for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP).
- Improved upon the prior (2 + ln 2 + epsilon)-approximation by Zhao and Xiao (2026) for general capacity and arbitrary positive demands.
- Employed endpoint quota trees, demand rounding, vertex copies, and weighted graphic matroid parity to construct disjoint client routes.

## Limitations

Running time is n^{O(1/epsilon)}, which depends polynomially on 1/epsilon.

## Open Questions & Future Work

- [[ucvrp-to-carp-extension]]

## Key Concepts

- [[quota-trees]]: A combinatorial tree structure used to construct candidate routes in vehicle routing approximation algorithms.

## Archivist Review

Applied strict selection criteria for permanent vault storage. Quota Trees is approved as a distinct combinatorial structure for vehicle routing approximation, and the CARP extension is approved as a well-defined open question raised by the paper's theoretical framework.

### Approved Concepts
- Quota Trees: Central technique for constructing candidate routes in the improved approximation algorithm for UCVRP.

### Approved Open Questions
- Capacitated Arc Routing Extension: Extends the algorithmic techniques developed for vertex routing (CVRP) to arc routing (CARP) with unsplittable demands.

## Links

- [Abstract](https://arxiv.org/abs/2610.28501)
- [PDF](https://arxiv.org/pdf/2610.28501)

