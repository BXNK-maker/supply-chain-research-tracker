---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Emission-Aware Optimization of Container Handling Vehicles: A HaminaKotka Port Case Study"
description: "This paper presents an emission-aware fleet scheduling framework for container handling vehicles at the Port of HaminaKotka, formulated as a linear programming workload allocation problem. Using a two-year operational dataset from 77 vehicles, the optimization reallocates operating hours from high-emission units to more efficient ones while keeping total workload fixed. Results demonstrate a 31% reduction in total CO2eq emissions and a 9.4% reduction in energy consumption without sacrificing aggregate operating productivity."
resource: "https://arxiv.org/abs/2610.05963"
tags:
  - "decarbonization"
  - "fleet-scheduling"
timestamp: "2026-10-17T09:00:09Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Hafiz Majid Hussain"
  - literal: "Juha Haakana"
  - literal: "Mehar Ullah"
issued:
  date-parts:
    - [2026, 10, 5]

# Domain-specific custom fields
paper_id: "2610.05963"
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
processed_at: "2026-10-17T09:00:09Z"
created_at: "2026-10-17T09:00:09Z"
---

# Emission-Aware Optimization of Container Handling Vehicles: A HaminaKotka Port Case Study

**Authors**: Hafiz Majid Hussain, Juha Haakana, Mehar Ullah
**Date**: 2026-10-05
**Paper ID**: [openalex:2610.05963](https://arxiv.org/abs/2610.05963)

## Summary

This paper presents an emission-aware fleet scheduling framework for container handling vehicles at the Port of HaminaKotka, formulated as a linear programming workload allocation problem. Using a two-year operational dataset from 77 vehicles, the optimization reallocates operating hours from high-emission units to more efficient ones while keeping total workload fixed. Results demonstrate a 31% reduction in total CO2eq emissions and a 9.4% reduction in energy consumption without sacrificing aggregate operating productivity.

## Key Contributions

- Formulates a linear programming workload allocation framework for container handling vehicles that minimizes total CO2eq emissions while preserving aggregate workload.
- Demonstrates an approximately 31% reduction in total CO2eq emissions and a 9.4% reduction in total energy consumption on the Port of HaminaKotka Mussalo terminal dataset without reducing operating hours.
- Derives vehicle-specific intensity metrics (CO2eq per operating hour) from a two-year operational dataset spanning 77 port vehicles.

## Limitations

The framework assumes fixed total workload and operating hours without modeling dynamic real-time traffic congestion, battery charging constraints for electric vehicles, or stochastic arrival processes.

## Archivist Review

Applied strict filtering criteria, ensuring no domain-specific or application-level case studies were admitted as standalone vault notes. The paper contributes an applied case study of linear programming for port vehicle decarbonization rather than a generalizable ML concept or foundational open question.

### Rejected Candidates
- [open_question] Operational Realism in Port Fleet Scheduling (`operational-realism-multi-objective-port-scheduling`) - low_impact: The open question focuses on applying standard operational constraints and multi-objective optimization to port fleet scheduling, which is domain-specific and lacks broader foundational relevance across general machine learning or AI research.

## Links

- [Abstract](https://arxiv.org/abs/2610.05963)
- [PDF](https://arxiv.org/pdf/2610.05963)

