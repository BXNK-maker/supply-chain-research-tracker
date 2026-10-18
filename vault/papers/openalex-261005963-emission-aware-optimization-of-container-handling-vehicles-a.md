---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Emission-Aware Optimization of Container Handling Vehicles: A HaminaKotka Port Case Study"
description: "This paper presents a data-driven fleet scheduling framework for landside port operations at the Port of HaminaKotka, aimed at reducing CO2eq emissions and energy consumption. Using a two-year dataset of 77 port-operating vehicles, the scheduling task is formulated as a linear programming workload allocation problem that reallocates operating hours away from high-intensity vehicles. Solved via the HiGHS linear programming solver, the optimized schedule achieves approximately a 31% reduction in total CO2eq emissions and a 9.4% reduction in energy consumption while maintaining the exact aggregate workload."
resource: "https://arxiv.org/abs/2610.05963"
tags:
  - "fleet-scheduling"
  - "decarbonization"
  - "time-series"
timestamp: "2026-10-18T09:18:46Z"

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
processed_at: "2026-10-18T09:18:46Z"
created_at: "2026-10-18T09:18:46Z"
---

# Emission-Aware Optimization of Container Handling Vehicles: A HaminaKotka Port Case Study

**Authors**: Hafiz Majid Hussain, Juha Haakana, Mehar Ullah
**Date**: 2026-10-05
**Paper ID**: [openalex:2610.05963](https://arxiv.org/abs/2610.05963)

## Summary

This paper presents a data-driven fleet scheduling framework for landside port operations at the Port of HaminaKotka, aimed at reducing CO2eq emissions and energy consumption. Using a two-year dataset of 77 port-operating vehicles, the scheduling task is formulated as a linear programming workload allocation problem that reallocates operating hours away from high-intensity vehicles. Solved via the HiGHS linear programming solver, the optimized schedule achieves approximately a 31% reduction in total CO2eq emissions and a 9.4% reduction in energy consumption while maintaining the exact aggregate workload.

## Key Contributions

- Proposes a data-driven fleet scheduling framework that reallocates vehicle operating hours to minimize total CO2eq emissions while preserving aggregate workload at the Port of HaminaKotka.
- Formulates the scheduling task as a linear programming workload allocation problem solved using HiGHS via SciPy, incorporating per-vehicle operating limits and fleet-level caps on CO2eq and energy use.
- Achieves an approximately 31% reduction in total CO2eq emissions and a 9.4% reduction in total energy consumption without reducing total operating hours based on a two-year dataset of 77 port vehicles.

## Limitations

The study focuses specifically on landside operations at the Port of HaminaKotka (Mussalo terminal), and future work could evaluate dynamic scheduling or extension to maritime operations.

## Archivist Review

The submitted paper presents an application of linear programming (using HiGHS via SciPy) to decarbonize container handling vehicle fleets at a specific port (HaminaKotka). It does not introduce any novel core ML concepts or reusable foundational mechanisms. The proposed open question is application-specific future work tied to port vehicle maintenance and multi-objective trade-offs, which does not rise to the level of a standalone vault note.

### Rejected Candidates
- [open_question] Multi-Objective Fleet Scheduling and Maintenance Integration (`multi-objective-fleet-scheduling-port-decarbonization`) - paper_local: The open question is essentially standard application-domain future work (integrating maintenance windows and multi-objective optimization for port vehicles) rather than a fundamental methodological bottleneck across machine learning or operations research.

## Links

- [Abstract](https://arxiv.org/abs/2610.05963)
- [PDF](https://arxiv.org/pdf/2610.05963)

