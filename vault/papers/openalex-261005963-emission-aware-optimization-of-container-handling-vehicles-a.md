---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Emission-Aware Optimization of Container Handling Vehicles: A HaminaKotka Port Case Study"
description: "This paper presents a data-driven fleet scheduling framework for landside port operations at the Port of HaminaKotka, aimed at operational decarbonization. By formulating the scheduling task as a linear programming workload allocation problem, the framework reallocates operating hours away from high-intensity vehicles to more efficient units. Evaluated on a two-year dataset from 77 port vehicles, the optimized schedule achieves approximately a 31% reduction in total CO2eq emissions and a 9.4% reduction in energy consumption without reducing total operating hours."
resource: "https://arxiv.org/abs/2610.05963"
tags:
  - "decarbonization"
  - "fleet-scheduling"
  - "smart-ports"
timestamp: "2026-10-15T09:35:26Z"

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
  - name: "operational-realism-multi-objective-port-fleet-optimization"
    description: "Extend the linear programming fleet scheduling and port decarbonization framework to integrate operational realism, including minimum and maximum utilization constraints, vehicle availability windows, maintenance schedules, and multi-objective optimization models that jointly minimize emissions, energy use, and operational costs."
skill: "GeneralMLSkill"
processed_at: "2026-10-15T09:35:26Z"
created_at: "2026-10-15T09:35:26Z"
---

# Emission-Aware Optimization of Container Handling Vehicles: A HaminaKotka Port Case Study

**Authors**: Hafiz Majid Hussain, Juha Haakana, Mehar Ullah
**Date**: 2026-10-05
**Paper ID**: [openalex:2610.05963](https://arxiv.org/abs/2610.05963)

## Summary

This paper presents a data-driven fleet scheduling framework for landside port operations at the Port of HaminaKotka, aimed at operational decarbonization. By formulating the scheduling task as a linear programming workload allocation problem, the framework reallocates operating hours away from high-intensity vehicles to more efficient units. Evaluated on a two-year dataset from 77 port vehicles, the optimized schedule achieves approximately a 31% reduction in total CO2eq emissions and a 9.4% reduction in energy consumption without reducing total operating hours.

## Key Contributions

- Formulates a linear programming workload allocation framework for container handling vehicles that minimizes total CO2eq emissions while preserving aggregate workload.
- Utilizes a two-year operational dataset from 77 port vehicles at the Port of HaminaKotka to derive vehicle-specific emission intensity metrics.
- Demonstrates through HiGHS-based optimization that shifting utilization toward efficient units achieves a ~31% reduction in total CO2eq and a 9.4% reduction in total energy consumption.

## Limitations

The framework focuses on workload reallocation under fixed aggregate hours and does not dynamically optimize real-time routing or variable arrival schedules.

## Open Questions & Future Work

- [[operational-realism-multi-objective-port-fleet-optimization]]

## Archivist Review

Approved the open question on operational realism and multi-objective port fleet optimization as it addresses a substantive methodological bottleneck in smart-port fleet decarbonization. No concepts or datasets met the strict reusability and novelty criteria.

### Approved Open Questions
- Operational Realism and Multi-Objective Optimization in Port Fleets: Crucial for bridging the gap between theoretical linear optimization models and practical, implementable smart-port fleet management systems under real-world constraints.

## Links

- [Abstract](https://arxiv.org/abs/2610.05963)
- [PDF](https://arxiv.org/pdf/2610.05963)

