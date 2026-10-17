---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Routes planning in a condominium company using mathematical optimization"
description: "This paper addresses the daily route planning problem for employees in a condominium management company, incorporating customer time windows, skill-matching constraints, employee working time limits, and flexible lunch breaks. The authors formulate this as a combinatorial optimization problem aiming to minimize total travel distance and lunch break penalties. Using Microsoft Azure APIs for distance matrices and Bing Maps for visualization, the approach demonstrates practical operational benefits for service provider route management."
resource: "https://arxiv.org/abs/2610.20080"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-10-17T08:58:55Z"

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
processed_at: "2026-10-17T08:58:55Z"
created_at: "2026-10-17T08:58:55Z"
---

# Routes planning in a condominium company using mathematical optimization

**Authors**: Lara Rocha, Pedro Martins
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.20080](https://arxiv.org/abs/2610.20080)

## Summary

This paper addresses the daily route planning problem for employees in a condominium management company, incorporating customer time windows, skill-matching constraints, employee working time limits, and flexible lunch breaks. The authors formulate this as a combinatorial optimization problem aiming to minimize total travel distance and lunch break penalties. Using Microsoft Azure APIs for distance matrices and Bing Maps for visualization, the approach demonstrates practical operational benefits for service provider route management.

## Key Contributions

- Formulates a specialized doubly-open vehicle routing problem with skill-matching constraints, time windows, and flexible lunch breaks for condominium service employees.
- Integrates Microsoft Azure routing APIs and Bing Maps visualization for real-world distance and time collection.
- Demonstrates operational efficiency improvements in daily route planning for a condominium management company.

## Limitations

Evaluated primarily on a specific condominium management company case study; generalization to broader multi-depot or large-scale multi-service domains requires further extension.

## Archivist Review

Applied strict selection criteria, keeping the vault clean by approving no concepts or open questions from this application-focused operations research paper.

### Rejected Candidates
- [concept] Doubly-open routes (`doubly-open-routes`) - not_reusable: Standard variant of vehicle routing problem paths rather than a foundational algorithmic innovation.

## Links

- [Abstract](https://arxiv.org/abs/2610.20080)
- [PDF](https://arxiv.org/pdf/2610.20080)

