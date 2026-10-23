---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees"
description: "This paper presents an improved deterministic (5/2 + \\varepsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) with arbitrary positive demands. The approach combines local search, endpoint quota trees after demand rounding, matching, set packing, and weighted graphic matroid parity to improve upon prior approximation guarantees."
resource: "https://arxiv.org/abs/2610.28501"
tags:
  - "approximation-algorithms"
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-23T09:44:44Z"

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
    description: "A tree-based structural construction used to form valid candidate routes in capacitated vehicle routing problems."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-23T09:44:44Z"
created_at: "2026-10-23T09:44:44Z"
---

# Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees

**Authors**: Zhenyu Wang
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.28501](https://arxiv.org/abs/2610.28501)

## Summary

This paper presents an improved deterministic (5/2 + \varepsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) with arbitrary positive demands. The approach combines local search, endpoint quota trees after demand rounding, matching, set packing, and weighted graphic matroid parity to improve upon prior approximation guarantees.

## Key Contributions

- Proposes a deterministic (5/2 + \varepsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) running in n^{O(1/\varepsilon)} time.
- Generalizes to arbitrary positive demands and general capacity bounds beyond restrictive demand regimes.
- Introduces a novel route construction mechanism combining endpoint quota trees, local search, matching, set packing, and weighted graphic matroid parity.

## Limitations

Running time scales as n^{O(1/\varepsilon)}, which can be high for very small \varepsilon.

## Key Concepts

- [[quota-trees]]: A tree-based structural construction used to form valid candidate routes in capacitated vehicle routing problems.

## Archivist Review

Quota trees are approved as a distinctive structural concept for route construction in vehicle routing approximation. The open question is rejected because it is a routine domain extension (applying the technique to arc routing) rather than a deep, reusable algorithmic bottleneck.

### Approved Concepts
- Quota Trees: Quota trees serve as the core structural component used for constructing candidate routes in the improved approximation algorithm for UCVRP.

### Rejected Candidates
- [open_question] Undirected Capacitated Arc Routing Extension (`undirected-capacitated-arc-routing-problem-extension`) - not_novel: Future work request for adapting the algorithm to a related routing variant without posing a distinct fundamental bottleneck or general methodological question.

## Links

- [Abstract](https://arxiv.org/abs/2610.28501)
- [PDF](https://arxiv.org/pdf/2610.28501)

