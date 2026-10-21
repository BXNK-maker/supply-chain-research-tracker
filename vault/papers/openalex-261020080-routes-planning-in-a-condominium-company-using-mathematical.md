---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Routes planning in a condominium company using mathematical optimization"
description: "This paper addresses the daily route planning problem for employees in a condominium company, requiring doubly-open routes that satisfy employee skill matching, customer time windows, maximum working hours, and conditional lunch break penalties. The authors model the problem using mathematical optimization, utilizing Microsoft Azure APIs for distance and travel time matrices and Bing Maps for visualization. Results demonstrate the operational effectiveness of the optimization approach in real-world condominium management scenarios."
resource: "https://arxiv.org/abs/2610.20080"
tags:
  - "fleet-scheduling"
  - "vehicle-routing-problem"
timestamp: "2026-10-21T09:46:56Z"

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
processed_at: "2026-10-21T09:46:56Z"
created_at: "2026-10-21T09:46:56Z"
---

# Routes planning in a condominium company using mathematical optimization

**Authors**: Lara Rocha, Pedro Martins
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.20080](https://arxiv.org/abs/2610.20080)

## Summary

This paper addresses the daily route planning problem for employees in a condominium company, requiring doubly-open routes that satisfy employee skill matching, customer time windows, maximum working hours, and conditional lunch break penalties. The authors model the problem using mathematical optimization, utilizing Microsoft Azure APIs for distance and travel time matrices and Bing Maps for visualization. Results demonstrate the operational effectiveness of the optimization approach in real-world condominium management scenarios.

## Key Contributions

- Formulates a daily route planning problem for condominium company employees as a mathematical optimization model with skill matching, time windows, and shift constraints.
- Incorporates optional lunch break penalties and period constraints (morning/afternoon/full-day) into doubly-open route construction.
- Integrates real-world distance and travel time collection via Microsoft Azure API with visual deployment on Bing Maps.

## Limitations

Evaluated on a specific condominium management company dataset without large-scale benchmark comparisons.

## Archivist Review

Applied strict reusability and novelty criteria. The open question regarding condominium routing extensions is too domain-specific and enumerative rather than capturing a universal algorithmic bottleneck.

### Rejected Candidates
- [open_question] Extensions to Condominium Routing Models (`extensions-to-condominium-routing-models`) - paper_local: Too domain-specific to condominium routing and general future-work enumeration rather than a fundamental theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.20080)
- [PDF](https://arxiv.org/pdf/2610.20080)

