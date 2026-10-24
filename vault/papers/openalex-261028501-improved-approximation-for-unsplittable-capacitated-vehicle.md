---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees"
description: "The paper presents an improved deterministic (5/2 + epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) applicable to general capacity and arbitrary positive demands. The methodology leverages local search, endpoint quota trees with demand rounding, vertex copies, matching, set packing, and weighted graphic matroid parity to improve upon previous approximation bounds."
resource: "https://arxiv.org/abs/2610.28501"
tags:
  - "vehicle-routing-problem"
  - "approximation-algorithms"
timestamp: "2026-10-24T09:15:41Z"

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
    description: "A tree-based route construction mechanism used in vehicle routing approximation algorithms to handle capacity and demand constraints."
datasets:
  []
open_questions:
  - name: "carp-unsplittable-demands-extension"
    description: "Extend the analysis of the proposed (5/2 + \\epsilon)-approximation algorithm using endpoint quota trees to the single-depot undirected capacitated arc routing problem (CARP) with unsplittable demands."
skill: "GeneralMLSkill"
processed_at: "2026-10-24T09:15:41Z"
created_at: "2026-10-24T09:15:41Z"
---

# Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees

**Authors**: Zhenyu Wang
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.28501](https://arxiv.org/abs/2610.28501)

## Summary

The paper presents an improved deterministic (5/2 + epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) applicable to general capacity and arbitrary positive demands. The methodology leverages local search, endpoint quota trees with demand rounding, vertex copies, matching, set packing, and weighted graphic matroid parity to improve upon previous approximation bounds.

## Key Contributions

- Proposes a deterministic (5/2 + epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) running in n^{O(1/epsilon)} time.
- Introduces local search combined with endpoint quota trees, demand rounding, and vertex copies to construct candidate routes.
- Combines routes using matching and set packing with a weighted graphic matroid parity tour partitioning strategy for remaining clients.

## Open Questions & Future Work

- [[carp-unsplittable-demands-extension]]

## Key Concepts

- [[quota-trees]]: A tree-based route construction mechanism used in vehicle routing approximation algorithms to handle capacity and demand constraints.

## Archivist Review

Approved quota-trees as it is already present in the vault and central to this paper's methodological contribution. Approved the open question on extending the approximation bounds to CARP as it identifies a clear theoretical extension explicitly mentioned in the text. No datasets were proposed or required.

### Approved Concepts
- Quota Trees: Central routing mechanism introduced to construct candidate routes for the UCVRP approximation algorithm.

### Approved Open Questions
- Capacitated Arc Routing Extension: Extending routing approximations from node routing (CVRP) to edge routing (CARP) is a significant theoretical step for capacitated arc routing problems.

## Links

- [Abstract](https://arxiv.org/abs/2610.28501)
- [PDF](https://arxiv.org/pdf/2610.28501)

