---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Routes planning in a condominium company using mathematical optimization"
description: "This paper addresses the daily route planning problem for employees in a condominium management company, aiming to minimize travel distance and lunch break penalties while satisfying customer time windows, skill requirements, and maximum working hours. The problem is modeled as a variant of the vehicle routing problem with doubly-open routes and conditional lunch breaks. Distances and travel times are obtained via Microsoft Azure APIs, and the resulting routes are visualized using Bing Maps. Results demonstrate the operational effectiveness of the mathematical optimization approach in real-world service management."
resource: "https://arxiv.org/abs/2610.20080"
tags:
  - "fleet-scheduling"
  - "vehicle-routing-problem"
timestamp: "2026-10-20T09:46:01Z"

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
processed_at: "2026-10-20T09:46:01Z"
created_at: "2026-10-20T09:46:01Z"
---

# Routes planning in a condominium company using mathematical optimization

**Authors**: Lara Rocha, Pedro Martins
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.20080](https://arxiv.org/abs/2610.20080)

## Summary

This paper addresses the daily route planning problem for employees in a condominium management company, aiming to minimize travel distance and lunch break penalties while satisfying customer time windows, skill requirements, and maximum working hours. The problem is modeled as a variant of the vehicle routing problem with doubly-open routes and conditional lunch breaks. Distances and travel times are obtained via Microsoft Azure APIs, and the resulting routes are visualized using Bing Maps. Results demonstrate the operational effectiveness of the mathematical optimization approach in real-world service management.

## Key Contributions

- Formulates and solves a real-world daily route planning problem for employees of a condominium company with skills constraints and time windows.
- Incorporates complex operational constraints including doubly-open routes, maximum working times, and conditional lunch break penalties.
- Integrates Microsoft Azure APIs for distance/time matrix collection and Bing Maps for route visualization in an applied setting.

## Limitations

Evaluated on a specific condominium management company case study without broad comparative evaluation on standard benchmark instances.

## Archivist Review

The paper applies standard vehicle routing optimization techniques to a specific enterprise case study using off-the-shelf APIs and exact solvers. No novel machine learning or algorithmic concepts met the strict bar for standalone vault notes, and the sole proposed open question is a standard scaling challenge in operations research rather than a novel foundational bottleneck.

### Rejected Candidates
- [open_question] Approximate Methods for Large-Scale Routing (`approximate-methods-large-scale-routing`) - not_novel: This open question is a general request for heuristics to scale exact optimization models, which is a standard perennial challenge in operations research rather than a specific unresolved mechanism tied uniquely to this work.

## Links

- [Abstract](https://arxiv.org/abs/2610.20080)
- [PDF](https://arxiv.org/pdf/2610.20080)

