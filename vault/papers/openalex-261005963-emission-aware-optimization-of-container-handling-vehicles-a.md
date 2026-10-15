---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Emission-Aware Optimization of Container Handling Vehicles: A HaminaKotka Port Case Study"
description: "This paper presents a data-driven fleet scheduling framework for landside port operations aimed at operational decarbonization, using a two-year dataset of 77 port-operating vehicles from the Port of HaminaKotka. The scheduling task is formulated as a linear programming workload allocation problem that minimizes CO2eq emissions and energy consumption while keeping total operating hours fixed. Solved via the HiGHS linear programming solver, the optimized schedule achieves an approximately 31% reduction in total CO2eq emissions and a 9.4% reduction in total energy consumption without reducing the aggregate workload."
resource: "https://arxiv.org/abs/2610.05963"
tags:
  - "machine-learning"
  - "smart-ports"
  - "decarbonization"
  - "fleet-scheduling"
timestamp: "2026-10-15T04:45:10Z"

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
processed_at: "2026-10-15T04:45:10Z"
created_at: "2026-10-15T04:45:10Z"
---

# Emission-Aware Optimization of Container Handling Vehicles: A HaminaKotka Port Case Study

**Authors**: Hafiz Majid Hussain, Juha Haakana, Mehar Ullah
**Date**: 2026-10-05
**Paper ID**: [openalex:2610.05963](https://arxiv.org/abs/2610.05963)

## Summary

This paper presents a data-driven fleet scheduling framework for landside port operations aimed at operational decarbonization, using a two-year dataset of 77 port-operating vehicles from the Port of HaminaKotka. The scheduling task is formulated as a linear programming workload allocation problem that minimizes CO2eq emissions and energy consumption while keeping total operating hours fixed. Solved via the HiGHS linear programming solver, the optimized schedule achieves an approximately 31% reduction in total CO2eq emissions and a 9.4% reduction in total energy consumption without reducing the aggregate workload.

## Key Contributions

- Formulates a data-driven fleet scheduling framework for landside port operations as a linear programming workload allocation problem that minimizes total CO2eq emissions and energy consumption while preserving the total workload.
- Derives vehicle-specific intensity metrics (CO2eq per operating hour) using a two-year dataset from 77 port-operating vehicles at the Port of HaminaKotka Mussalo terminal.
- Achieves approximately a 31% reduction in total CO2eq emissions and a 9.4% reduction in total energy consumption on the Port of HaminaKotka dataset by reallocating operating hours away from high-intensity vehicles.

## Limitations

The framework focuses specifically on linear programming workload reallocation for landside port operations and relies on historical vehicle-specific intensity metrics derived from a two-year dataset.

## Archivist Review

Applied strict selection criteria. The paper's contribution is a case-specific linear programming application for port vehicle scheduling using standard solvers, which lacks broad foundational methodological novelty or reusable architecture for the core ML vault. The single open question was rejected because it proposes standard application-specific extensions (incorporating maintenance windows and cost terms) rather than a fundamental scientific bottleneck.

### Rejected Candidates
- [open_question] Operational Realism in Fleet Scheduling (`operational-realism-multiobjective-fleet-scheduling`) - low_impact: This open question essentially requests routine extensions to constraints and multi-objective optimization, which is standard application-specific future work rather than an architectural or fundamental ML bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.05963)
- [PDF](https://arxiv.org/pdf/2610.05963)

