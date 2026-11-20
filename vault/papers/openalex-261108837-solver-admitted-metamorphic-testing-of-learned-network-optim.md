---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Solver-Admitted Metamorphic Testing of Learned Network Optimization Surrogates"
description: "This paper constructs metamorphic tests with explicit eligibility conditions, output alignment, and numerical thresholds to evaluate learned network optimization surrogates under equivalent problem encodings. Evaluating across alternating-current optimal power flow (AC-OPF), the traveling salesman problem (TSP), the capacitated vehicle routing problem (CVRP), and maximum independent set (MIS), the authors show that prominent neural models frequently violate expected metamorphic relations due to numerical errors and multiple optima. The findings demonstrate that standard interventions like input canonicalization and post hoc normalization alleviate specific discrepancies but fail to universally guarantee accuracy and feasibility, highlighting the need to report metamorphic consistency alongside traditional metrics."
resource: "https://arxiv.org/abs/2611.08837"
tags:
  - "combinatorial-optimization"
  - "machine-learning"
  - "vehicle-routing-problem"
timestamp: "2026-11-20T13:50:12Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Vineet Jagadeesan Nair"
  - literal: "Stephen Peng"
  - literal: "Arun Ravindran"
issued:
  date-parts:
    - [2026, 11, 6]

# Domain-specific custom fields
paper_id: "2611.08837"
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
processed_at: "2026-11-20T13:50:12Z"
created_at: "2026-11-20T13:50:12Z"
---

# Solver-Admitted Metamorphic Testing of Learned Network Optimization Surrogates

**Authors**: Vineet Jagadeesan Nair, Stephen Peng, Arun Ravindran
**Date**: 2026-11-06
**Paper ID**: [openalex:2611.08837](https://arxiv.org/abs/2611.08837)

## Summary

This paper constructs metamorphic tests with explicit eligibility conditions, output alignment, and numerical thresholds to evaluate learned network optimization surrogates under equivalent problem encodings. Evaluating across alternating-current optimal power flow (AC-OPF), the traveling salesman problem (TSP), the capacitated vehicle routing problem (CVRP), and maximum independent set (MIS), the authors show that prominent neural models frequently violate expected metamorphic relations due to numerical errors and multiple optima. The findings demonstrate that standard interventions like input canonicalization and post hoc normalization alleviate specific discrepancies but fail to universally guarantee accuracy and feasibility, highlighting the need to report metamorphic consistency alongside traditional metrics.

## Key Contributions

- Constructed metamorphic tests for optimization solver surrogates incorporating explicit eligibility conditions, output alignment, and numerical thresholds.
- Demonstrated that learned surrogates across AC-OPF, TSP, CVRP, and MIS exhibit substantial violations of metamorphic relations (e.g., GridSFM-Open violating relations across multiple grids, POMO rotation/reflection violation rates rising up to 89.5% with city scale, and DIFUSCO violating disjoint-union relations on 35.6% of draws).
- Evaluated mitigation strategies including source patches, input canonicalization, and post hoc normalization, showing that interventions can remove specific discrepancies but fail to universally preserve accuracy and feasibility within declared margins.

## Limitations

None explicitly detailed in the abstract beyond noting that proposed interventions do not uniformly establish preserved accuracy and feasibility across all tested domains and grids.

## Archivist Review

No concepts or datasets met the strict novelty and reusability criteria for permanent vault entries.

## Links

- [Abstract](https://arxiv.org/abs/2611.08837)
- [PDF](https://arxiv.org/pdf/2611.08837)

