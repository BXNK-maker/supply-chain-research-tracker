---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees"
description: "This paper presents a deterministic $(5/2+\\varepsilon)$-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) with general capacities and arbitrary positive demands, running in $n^{O(1/\\varepsilon)}$ time. The methodology constructs candidate routes via endpoint quota trees following demand rounding and vertex copying, then combines them with routes from matching and set packing while routing remaining clients via weighted graphic matroid parity. This improves upon existing approximation guarantees for UCVRP."
resource: "https://arxiv.org/abs/2610.28501"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "approximation-algorithms"
timestamp: "2026-10-25T09:32:22Z"

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
    description: "Endpoint quota trees are combinatorial structures used to construct candidate routes in routing algorithms after demand rounding and vertex duplication."
datasets:
  []
open_questions:
  - name: "carp-unsplittable-demands-extension"
    description: "The authors explicitly note that while their analysis for the (5/2 + \\\\epsilon)-approximation algorithm extends to the single-depot undirected capacitated arc routing problem (CARP) with unsplittable demands, they do not develop this extension in the current work."
skill: "GeneralMLSkill"
processed_at: "2026-10-25T09:32:22Z"
created_at: "2026-10-25T09:32:22Z"
---

# Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees

**Authors**: Zhenyu Wang
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.28501](https://arxiv.org/abs/2610.28501)

## Summary

This paper presents a deterministic $(5/2+\varepsilon)$-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) with general capacities and arbitrary positive demands, running in $n^{O(1/\varepsilon)}$ time. The methodology constructs candidate routes via endpoint quota trees following demand rounding and vertex copying, then combines them with routes from matching and set packing while routing remaining clients via weighted graphic matroid parity. This improves upon existing approximation guarantees for UCVRP.

## Key Contributions

- Introduces a deterministic $(5/2+\varepsilon)$-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) running in $n^{O(1/\varepsilon)}$ time.
- Improves upon previous bounds such as the recent $(2+\ln 2+\varepsilon)$-approximation by utilizing local search combined with endpoint quota trees, matching, set packing, and weighted graphic matroid parity.
- Extends approximation guarantees to general capacity and arbitrary positive demands for UCVRP.

## Open Questions & Future Work

- [[carp-unsplittable-demands-extension]]

## Key Concepts

- [[quota-trees]]: Endpoint quota trees are combinatorial structures used to construct candidate routes in routing algorithms after demand rounding and vertex duplication.

## Archivist Review

Approved quota-trees as a core conceptual method for routing approximation. The open question regarding CARP extension matches an existing vault note (carp-unsplittable-demands-extension), so it was rejected as a duplicate and its canonical slug was acknowledged.

### Approved Concepts
- Quota Trees: Quota trees are the primary structural mechanism introduced and utilized for constructing candidate routes in the improved approximation algorithm for UCVRP.

### Approved Open Questions
- Undirected Capacitated Arc Routing: Extending the quota-tree and local-search approximation framework from node routing (UCVRP) to edge routing (CARP) is an important open direction for capacitated routing problems.

### Rejected Candidates
- [open_question] Undirected Capacitated Arc Routing (`capacitated-arc-routing-extension`) - duplicate_existing: Already exists in the vault under carp-unsplittable-demands-extension.

## Links

- [Abstract](https://arxiv.org/abs/2610.28501)
- [PDF](https://arxiv.org/pdf/2610.28501)

