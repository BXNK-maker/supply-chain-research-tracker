---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Routes planning in a condominium company using mathematical optimization"
description: "This paper addresses the daily route planning problem for employees in a condominium company, incorporating customer time windows, employee skill matching, maximum working time limits, and conditional lunch breaks. The authors formulate a mathematical optimization model aiming to minimize total travel distance and lunch break penalties. Using Microsoft Azure APIs for distance and time calculations along with Bing Maps for visualization, the approach demonstrates significant operational efficiency for service providers."
resource: "https://arxiv.org/abs/2610.20080"
tags:
  - "vehicle-routing-problem"
  - "fleet-scheduling"
  - "combinatorial-optimization"
timestamp: "2026-10-22T09:46:40Z"

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
processed_at: "2026-10-22T09:46:40Z"
created_at: "2026-10-22T09:46:40Z"
---

# Routes planning in a condominium company using mathematical optimization

**Authors**: Lara Rocha, Pedro Martins
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.20080](https://arxiv.org/abs/2610.20080)

## Summary

This paper addresses the daily route planning problem for employees in a condominium company, incorporating customer time windows, employee skill matching, maximum working time limits, and conditional lunch breaks. The authors formulate a mathematical optimization model aiming to minimize total travel distance and lunch break penalties. Using Microsoft Azure APIs for distance and time calculations along with Bing Maps for visualization, the approach demonstrates significant operational efficiency for service providers.

## Key Contributions

- Formulated and solved a daily route planning problem for condominium company employees incorporating skill matching, time windows, maximum working times, and conditional lunch breaks.
- Developed a mathematical optimization model that minimizes total travel distance and penalizes lunch breaks while satisfying all pre-scheduled customer visits.
- Demonstrated operational advantages and practical applicability of the route optimization system using Microsoft Azure APIs and Bing Maps integration.

## Limitations

Evaluated specifically on a single condominium management company dataset; generalizability to other large-scale service provider domains requires further extension.

## Archivist Review

Applied strict filtering standards to ensure only highly reusable, foundational concepts and sharp, rigorous research questions enter the vault. The paper applies standard vehicle routing problem (VRP) modeling to a specific condominium company context, so no novel standalone concepts or open questions met the high bar for permanent vault storage.

### Rejected Candidates
- [open_question] Extensions to Field Service Routing Models (`extensions-to-field-service-routing-models-and-solution-methods`) - not_reusable: The proposed open question is a standard collection of future work directions for vehicle routing problems rather than a sharp, technically bounded vault bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.20080)
- [PDF](https://arxiv.org/pdf/2610.20080)

