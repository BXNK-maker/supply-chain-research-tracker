---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Routes planning in a condominium company using mathematical optimization"
description: "This paper proposes a mathematical optimization model for planning daily routes for employees of a condominium management company. The approach determines doubly-open routes satisfying customer time windows, employee skill requirements, maximum working hours, and conditional lunch break periods. Distances and travel times are obtained via Microsoft Azure APIs, and the resulting routes are visualized using Bing Maps. Results demonstrate the operational effectiveness of the model in real-world service routing scenarios."
resource: "https://arxiv.org/abs/2610.20080"
tags:
  - "vehicle-routing-problem"
  - "fleet-scheduling"
  - "combinatorial-optimization"
timestamp: "2026-10-24T09:14:42Z"

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
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-24T09:14:42Z"
created_at: "2026-10-24T09:14:42Z"
---

# Routes planning in a condominium company using mathematical optimization

**Authors**: Lara Rocha, Pedro Martins
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.20080](https://arxiv.org/abs/2610.20080)

## Summary

This paper proposes a mathematical optimization model for planning daily routes for employees of a condominium management company. The approach determines doubly-open routes satisfying customer time windows, employee skill requirements, maximum working hours, and conditional lunch break periods. Distances and travel times are obtained via Microsoft Azure APIs, and the resulting routes are visualized using Bing Maps. Results demonstrate the operational effectiveness of the model in real-world service routing scenarios.

## Key Contributions

- Developed a mathematical optimization model for daily route planning in a condominium management company with employee skill matching, time windows, and maximum working time constraints.
- Incorporated conditional lunch break constraints that penalize and account for routes extending across both morning and afternoon periods.
- Integrated Microsoft Azure APIs for distance and travel time collection and Bing Maps for route visualization in real-world operational scenarios.

## Limitations

Evaluated primarily on a specific condominium management company context without extensive testing across diverse large-scale benchmark instances.

## Archivist Review

Applied strict selectivity: rejected the open question as a standard operations research scaling limitation rather than a reusable theoretical bottleneck. No concepts or datasets met the strict vault criteria.

### Rejected Candidates
- [open_question] Approximate Methods for LargeScale Routing (`approximate-methods-for-large-scale-routing`) - low_impact: This is a generic request for heuristic methods to scale exact solvers, which is a standard limitation and future work direction in operations research rather than a targeted unresolved mechanism or bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.20080)
- [PDF](https://arxiv.org/pdf/2610.20080)

