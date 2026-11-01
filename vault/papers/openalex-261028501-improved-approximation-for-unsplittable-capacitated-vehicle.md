---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees"
description: "This paper studies the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) and presents a deterministic (5/2 + \\epsilon)-approximation algorithm running in n^{O(1/\\epsilon)} time for general capacities and positive demands. The approach relies on constructing candidate routes using endpoint quota trees after demand rounding, combined with matching, set packing, and weighted graphic matroid parity. This improves upon previous approximation bounds for the problem, pushing closer to the inherent hardness limits."
resource: "https://arxiv.org/abs/2610.28501"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "approximation-algorithms"
timestamp: "2026-11-01T11:38:42Z"

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
    description: "Extend the approximation algorithm and analysis for metric UCVRP to the single-depot undirected capacitated arc routing problem (CARP) with unsplittable demands to achieve the same (5/2 + \\\\epsilon)-approximation guarantee."
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:38:42Z"
created_at: "2026-11-01T11:38:42Z"
---

# Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees

**Authors**: Zhenyu Wang
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.28501](https://arxiv.org/abs/2610.28501)

## Summary

This paper studies the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) and presents a deterministic (5/2 + \epsilon)-approximation algorithm running in n^{O(1/\epsilon)} time for general capacities and positive demands. The approach relies on constructing candidate routes using endpoint quota trees after demand rounding, combined with matching, set packing, and weighted graphic matroid parity. This improves upon previous approximation bounds for the problem, pushing closer to the inherent hardness limits.

## Key Contributions

- Proposes a deterministic (5/2 + \epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) running in n^{O(1/\epsilon)} time.
- Applicable to general capacity and arbitrary positive demands by combining local search, endpoint quota trees, matching, set packing, and weighted graphic matroid parity techniques.

## Limitations

The running time is n^{O(1/\epsilon)}, which grows rapidly for very small epsilon values.

## Open Questions & Future Work

- [[ucvrp-to-carp-extension]]

## Key Concepts

- [[quota-trees]]: A tree-based routing structure used to construct candidate routes in capacitated vehicle routing problems.

## Archivist Review

Quota Trees is already in the vault as a concept, so it is reused. The candidate open question for CARP extension matches the existing 'ucvrp-to-carp-extension' vault entry and is therefore rejected as a duplicate, leaving no new open questions to approve.

### Approved Concepts
- Quota Trees: Central algorithmic primitive used for constructing candidate routes in the improved approximation scheme for UCVRP.

### Approved Open Questions
- Capacitated Arc Routing Extension: Extending vehicle routing approximation frameworks to arc routing problems broadens the applicability of quota trees and tour partitioning techniques to broader network design domains.

### Rejected Candidates
- [open_question] Capacitated Arc Routing Extension (`capacitated-arc-routing-extension`) - duplicate_existing: Duplicate or near-equivalent of an existing vault question (ucvrp-to-carp-extension).

## Links

- [Abstract](https://arxiv.org/abs/2610.28501)
- [PDF](https://arxiv.org/pdf/2610.28501)

