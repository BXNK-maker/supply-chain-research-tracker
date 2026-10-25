---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Routes planning in a condominium company using mathematical optimization"
description: "This paper addresses the daily route planning problem for employees in a condominium management company using mathematical optimization. The proposed approach constructs doubly-open routes satisfying customer time windows, employee skill requirements, maximum working hours, and conditional lunch break periods, with the objective of minimizing total distance and lunch break penalties. Real-world travel times are retrieved via Microsoft Azure APIs and solutions are visualized using Bing Maps, demonstrating practical operational advantages for service providers."
resource: "https://arxiv.org/abs/2610.20080"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
  - "time-series"
timestamp: "2026-10-25T09:31:29Z"

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
processed_at: "2026-10-25T09:31:29Z"
created_at: "2026-10-25T09:31:29Z"
---

# Routes planning in a condominium company using mathematical optimization

**Authors**: Lara Rocha, Pedro Martins
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.20080](https://arxiv.org/abs/2610.20080)

## Summary

This paper addresses the daily route planning problem for employees in a condominium management company using mathematical optimization. The proposed approach constructs doubly-open routes satisfying customer time windows, employee skill requirements, maximum working hours, and conditional lunch break periods, with the objective of minimizing total distance and lunch break penalties. Real-world travel times are retrieved via Microsoft Azure APIs and solutions are visualized using Bing Maps, demonstrating practical operational advantages for service providers.

## Key Contributions

- Developed a mathematical optimization model for planning daily doubly-open routes for employees in a condominium management company.
- Incorporated skill-matching constraints, time windows, maximum working hours, and conditional lunch break penalties into a routing framework.
- Integrated Microsoft Azure APIs for distance/time calculation and Bing Maps for operational route visualization.

## Limitations

Evaluated primarily on a specific condominium management company setting, though the framework is generalizable.

## Archivist Review

The paper presents an application of mathematical optimization to daily route planning for a condominium management company. No novel reusable concepts or foundational open questions were proposed that meet the vault's high standards for standalone permanence.

### Rejected Candidates
- [open_question] Extensions for Large-Scale Condominium Routing (`large-scale-condominium-routing-extensions`) - low_impact: This open question is a standard collection of future work extensions for a vehicle routing application rather than a critical foundational bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.20080)
- [PDF](https://arxiv.org/pdf/2610.20080)

