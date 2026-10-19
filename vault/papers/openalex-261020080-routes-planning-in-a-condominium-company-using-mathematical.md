---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Routes planning in a condominium company using mathematical optimization"
description: "This paper addresses the daily route planning problem for employees in a condominium company, incorporating customer time windows, skill matching, maximum working hours, and conditional lunch break constraints. The optimization model aims to minimize total travel distance and lunch break penalties while utilizing Microsoft Azure APIs for distance matrices and Bing Maps for visualization. Results demonstrate the operational effectiveness of the proposed routing approach in real-world service management."
resource: "https://arxiv.org/abs/2610.20080"
tags:
  - "fleet-scheduling"
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-10-19T10:26:48Z"

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
processed_at: "2026-10-19T10:26:48Z"
created_at: "2026-10-19T10:26:48Z"
---

# Routes planning in a condominium company using mathematical optimization

**Authors**: Lara Rocha, Pedro Martins
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.20080](https://arxiv.org/abs/2610.20080)

## Summary

This paper addresses the daily route planning problem for employees in a condominium company, incorporating customer time windows, skill matching, maximum working hours, and conditional lunch break constraints. The optimization model aims to minimize total travel distance and lunch break penalties while utilizing Microsoft Azure APIs for distance matrices and Bing Maps for visualization. Results demonstrate the operational effectiveness of the proposed routing approach in real-world service management.

## Key Contributions

- Formulates daily route planning for condominium company employees as a mathematical optimization problem with skills, time windows, and lunch break penalties
- Incorporates real-world constraints including employee working time limits, specific skill requirements per customer, and operational time windows from 9 AM to 6:30 PM
- Integrates Microsoft Azure API for travel distance/time estimation and Bing Maps for route visualization in a real-world case study

## Limitations

Evaluated primarily on a specific condominium management company setting without large-scale public benchmark comparisons

## Archivist Review

The paper applies standard mathematical optimization and routing constraints to a specific real-world condominium company case study without introducing broadly reusable methods, novel core architectures, or unique datasets. Consequently, no new standalone notes are warranted.

### Rejected Candidates
- [open_question] Extended Field Service Routing Models (`extended-field-service-routing-models-multiemployee-weekly`) - not_novel: This is a standard list of future work items typical for an applied operations research paper rather than a major unresolved bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.20080)
- [PDF](https://arxiv.org/pdf/2610.20080)

