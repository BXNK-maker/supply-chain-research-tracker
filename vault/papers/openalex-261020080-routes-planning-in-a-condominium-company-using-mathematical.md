---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Routes planning in a condominium company using mathematical optimization"
description: "This paper addresses the daily route planning problem for employees of a condominium management company with pre-scheduled customer visits, skill requirements, time windows, and maximum working times. The proposed mathematical optimization model constructs doubly-open routes to minimize total distance while penalizing unnecessary or spanning lunch breaks. Travel times are sourced via Microsoft Azure APIs, and resulting schedules are visualized on Bing Maps to demonstrate operational efficiency."
resource: "https://arxiv.org/abs/2610.20080"
tags:
  - "vehicle-routing-problem"
  - "fleet-scheduling"
timestamp: "2026-10-28T10:58:21Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Lara Rocha"
  - literal: "Pedro Martins"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20080"
paper_source: "openalex"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "approximate-methods-large-scale-routing"
    description: "Future research should focus on developing scalable approximate methods, such as metaheuristics or matheuristics, to enable the application of rich vehicle routing formulations with time windows and lunch breaks to large-scale real-world datasets where exact solvers face memory and time limits."
skill: "GeneralMLSkill"
processed_at: "2026-10-28T10:58:21Z"
created_at: "2026-10-28T10:58:21Z"
---

# Routes planning in a condominium company using mathematical optimization

**Authors**: Lara Rocha, Pedro Martins
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.20080](https://arxiv.org/abs/2610.20080)

## Summary

This paper addresses the daily route planning problem for employees of a condominium management company with pre-scheduled customer visits, skill requirements, time windows, and maximum working times. The proposed mathematical optimization model constructs doubly-open routes to minimize total distance while penalizing unnecessary or spanning lunch breaks. Travel times are sourced via Microsoft Azure APIs, and resulting schedules are visualized on Bing Maps to demonstrate operational efficiency.

## Key Contributions

- Formulates a daily route planning problem for condominium company employees as a mathematical optimization model incorporating skills matching, time windows, and shift limits.
- Incorporates realistic operational constraints such as conditional lunch break penalties depending on whether routes span both morning and afternoon periods.
- Demonstrates real-world integration using Microsoft Azure APIs for distance and travel time collection and Bing Maps for route visualization in a property management context.

## Limitations

Evaluated on a specific condominium management company setting, though the framework is noted as extensible.

## Open Questions & Future Work

- [[approximate-methods-large-scale-routing]]

## Archivist Review

Applied strict selection criteria ensuring high relevance and avoiding duplication with existing vault notes. No concepts met the high bar for universal reusability, and the open question was redundant with existing routing scalability topics in the vault.

### Approved Open Questions
- Approximate Methods for Large-Scale Routing: Exact mathematical formulations for rich routing problems often stall on large real-world instances due to weak lower bounds and high computational complexity, making approximate methods essential for practical industrial deployment.

### Rejected Candidates
- [open_question] Approximate Methods for Large-Scale Routing (`approximate-methods-large-scale-routing`) - duplicate_existing: Already covered by existing open questions on routing scale and heuristics in the vault.

## Links

- [Abstract](https://arxiv.org/abs/2610.20080)
- [PDF](https://arxiv.org/pdf/2610.20080)

