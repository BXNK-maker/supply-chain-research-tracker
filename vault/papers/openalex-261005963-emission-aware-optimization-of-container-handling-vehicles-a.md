---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Emission-Aware Optimization of Container Handling Vehicles: A HaminaKotka Port Case Study"
description: "This paper presents a data-driven fleet scheduling framework for landside port operations at the Port of HaminaKotka to minimize carbon emissions without sacrificing workload. By formulating the task as a linear programming workload allocation problem using vehicle-specific intensity metrics derived from a two-year fleet dataset, the optimized schedule achieves a 31% reduction in total CO2eq and a 9.4% reduction in energy consumption."
resource: "https://arxiv.org/abs/2610.05963"
tags:
  - "decarbonization"
  - "fleet-scheduling"
  - "smart-ports"
timestamp: "2026-10-16T09:36:50Z"

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
processed_at: "2026-10-16T09:36:50Z"
created_at: "2026-10-16T09:36:50Z"
---

# Emission-Aware Optimization of Container Handling Vehicles: A HaminaKotka Port Case Study

**Authors**: Hafiz Majid Hussain, Juha Haakana, Mehar Ullah
**Date**: 2026-10-05
**Paper ID**: [openalex:2610.05963](https://arxiv.org/abs/2610.05963)

## Summary

This paper presents a data-driven fleet scheduling framework for landside port operations at the Port of HaminaKotka to minimize carbon emissions without sacrificing workload. By formulating the task as a linear programming workload allocation problem using vehicle-specific intensity metrics derived from a two-year fleet dataset, the optimized schedule achieves a 31% reduction in total CO2eq and a 9.4% reduction in energy consumption.

## Key Contributions

- Formulated a data-driven fleet scheduling framework as a linear programming workload allocation problem to minimize total CO2eq emissions while preserving aggregate workload.
- Derived vehicle-specific intensity metrics (CO2eq per operating hour) from a two-year operational dataset of 77 port vehicles at the Port of HaminaKotka.
- Achieved an approximately 31% reduction in total CO2eq emissions and a 9.4% reduction in total energy consumption without reducing total operating hours.

## Limitations

The study relies on aggregated monthly and annual data and assumes fixed total required operating hours for landside port operations.

## Archivist Review

Applied strict filtering criteria, resulting in no approved concepts or datasets as the work focuses on a localized port fleet case study using standard linear programming rather than reusable architectural primitives or canonical benchmarks.

### Rejected Candidates
- [dataset] haminakotka-port-fleet-dataset (`haminakotka-port-fleet-dataset`) - not_reusable: Local case study dataset tied to a specific port and proprietary fleet records rather than a broadly adopted benchmark.

## Links

- [Abstract](https://arxiv.org/abs/2610.05963)
- [PDF](https://arxiv.org/pdf/2610.05963)

