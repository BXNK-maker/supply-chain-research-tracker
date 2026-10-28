---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees"
description: "The paper presents a deterministic (5/2 + \\epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) that runs in n^{O(1/\\epsilon)} time for rational \\epsilon. The approach relies on endpoint quota trees, demand rounding, local search, matching, set packing, and weighted graphic matroid parity to improve upon previous approximation bounds."
resource: "https://arxiv.org/abs/2610.28501"
tags:
  - "vehicle-routing-problem"
  - "approximation-algorithms"
timestamp: "2026-10-28T10:58:38Z"

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
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-28T10:58:38Z"
created_at: "2026-10-28T10:58:38Z"
---

# Improved Approximation for Unsplittable Capacitated Vehicle Routing Using Quota Trees

**Authors**: Zhenyu Wang
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.28501](https://arxiv.org/abs/2610.28501)

## Summary

The paper presents a deterministic (5/2 + \epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) that runs in n^{O(1/\epsilon)} time for rational \epsilon. The approach relies on endpoint quota trees, demand rounding, local search, matching, set packing, and weighted graphic matroid parity to improve upon previous approximation bounds.

## Key Contributions

- Introduces a deterministic (5/2 + \epsilon)-approximation algorithm for the Unsplittable Capacitated Vehicle Routing Problem (UCVRP) running in n^{O(1/\epsilon)} time.
- Utilizes endpoint quota trees after demand rounding and vertex replication for constructing candidate routes.
- Combines route structures with matching, set packing, and a tour partitioned using weighted graphic matroid parity to serve remaining clients.

## Limitations

Running time is n^{O(1/\epsilon)}, which grows rapidly for very small epsilon values.

## Archivist Review

Applied strict evaluation criteria: quota-trees is already present in the vault, and the open question is too paper-local to justify a permanent standalone entry. Consequently, no new items were approved.

### Rejected Candidates
- [concept] Quota Trees (`quota-trees`) - duplicate_existing: Quota trees are already present in the vault under the exact same slug.
- [open_question] Approximation Limits for UCVRP (`improved-approximation-ucvrp-gap`) - paper_local: Paper-local approximation bound question for a specific vehicle routing problem variant without broader cross-cutting generalizability.

## Links

- [Abstract](https://arxiv.org/abs/2610.28501)
- [PDF](https://arxiv.org/pdf/2610.28501)

