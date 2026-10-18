---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Routes planning in a condominium company using mathematical optimization"
description: "This paper addresses the daily route planning problem for employees in a condominium management company, incorporating customer time windows, skill requirements, maximum working hours, and conditional lunch break penalties. Using a mathematical optimization model integrated with Microsoft Azure and Bing Maps APIs, the approach minimizes total travel distance and lunch break penalties while guaranteeing all visits. Real-world evaluation demonstrates significant operational efficiencies for service provider routing."
resource: "https://arxiv.org/abs/2610.20080"
tags:
  - "fleet-scheduling"
  - "vehicle-routing-problem"
timestamp: "2026-10-18T09:16:33Z"

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
processed_at: "2026-10-18T09:16:33Z"
created_at: "2026-10-18T09:16:33Z"
---

# Routes planning in a condominium company using mathematical optimization

**Authors**: Lara Rocha, Pedro Martins
**Date**: 2026-10-14
**Paper ID**: [openalex:2610.20080](https://arxiv.org/abs/2610.20080)

## Summary

This paper addresses the daily route planning problem for employees in a condominium management company, incorporating customer time windows, skill requirements, maximum working hours, and conditional lunch break penalties. Using a mathematical optimization model integrated with Microsoft Azure and Bing Maps APIs, the approach minimizes total travel distance and lunch break penalties while guaranteeing all visits. Real-world evaluation demonstrates significant operational efficiencies for service provider routing.

## Key Contributions

- Formulates a mathematical optimization model for daily route planning in a condominium management company with skill matching, time windows, and shift constraints.
- Incorporates conditional lunch break periods that can be avoided if routes are completed entirely within the morning or afternoon.
- Demonstrates operational advantages of optimized route planning using real-world geographic and travel time data via Microsoft Azure and Bing Maps APIs.

## Limitations

Evaluated on a specific condominium company dataset; scalability to large-scale urban delivery or routing remains to be fully explored.

## Archivist Review

No concepts or datasets met the strict novelty and reuse thresholds for the vault. The single proposed open question was also rejected because routing extensions like multi-employee collaboration are standard operational research variations rather than major conceptual bottlenecks for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2610.20080)
- [PDF](https://arxiv.org/pdf/2610.20080)

