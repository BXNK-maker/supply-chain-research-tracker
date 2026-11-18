---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Solver-Admitted Metamorphic Testing of Learned Network Optimization Surrogates"
description: "This paper introduces solver-admitted metamorphic testing to audit learned optimization surrogates for invariance under equivalent problem encodings while accounting for numerical error and multiple optima. Evaluating models across AC-OPF, TSP, CVRP, and MIS reveals frequent violations of metamorphic relations in prominent surrogate architectures like GridSFM-Open, POMO, and DIFUSCO. The findings highlight that current learned surrogates frequently lack structural consistency and motivate reporting metamorphic consistency alongside standard optimality and feasibility metrics."
resource: "https://arxiv.org/abs/2611.08837"
tags:
  - "combinatorial-optimization"
  - "interpretable-machine-learning"
  - "time-series"
  - "vehicle-routing-problem"
timestamp: "2026-11-18T13:51:07Z"

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
  - name: "solver-admitted-metamorphic-testing"
    description: "A testing framework for optimization solver surrogates using explicit eligibility conditions, output alignment, and numerical thresholds."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-18T13:51:07Z"
created_at: "2026-11-18T13:51:07Z"
---

# Solver-Admitted Metamorphic Testing of Learned Network Optimization Surrogates

**Authors**: Vineet Jagadeesan Nair, Stephen Peng, Arun Ravindran
**Date**: 2026-11-06
**Paper ID**: [openalex:2611.08837](https://arxiv.org/abs/2611.08837)

## Summary

This paper introduces solver-admitted metamorphic testing to audit learned optimization surrogates for invariance under equivalent problem encodings while accounting for numerical error and multiple optima. Evaluating models across AC-OPF, TSP, CVRP, and MIS reveals frequent violations of metamorphic relations in prominent surrogate architectures like GridSFM-Open, POMO, and DIFUSCO. The findings highlight that current learned surrogates frequently lack structural consistency and motivate reporting metamorphic consistency alongside standard optimality and feasibility metrics.

## Key Contributions

- Constructs metamorphic tests for optimization solver surrogates with explicit eligibility conditions, output alignment, and numerical thresholds.
- Evaluates surrogate models across alternating-current optimal power flow (AC-OPF), TSP, CVRP, and MIS, revealing widespread invariance violations in state-of-the-art models like GridSFM-Open, POMO, and DIFUSCO.
- Demonstrates that post hoc normalization and source patches can remove selected discrepancies, but no single intervention establishes preserved accuracy and feasibility across all test cases.

## Key Concepts

- [[solver-admitted-metamorphic-testing]]: A testing framework for optimization solver surrogates using explicit eligibility conditions, output alignment, and numerical thresholds.

## Archivist Review

Approved the core concept of solver-admitted metamorphic testing as a distinct and reusable validation methodology for learned optimization surrogates. Rejected the open question candidate as it essentially restated boilerplate future directions for surrogate repair and validation.

### Approved Concepts
- Solver-Admitted Metamorphic Testing: Introduces a principled testing methodology for learned network optimization surrogates that accounts for numerical error and multiple optima under equivalent problem encodings.

### Rejected Candidates
- [open_question] Validation and Repair of Learned Optimization Surrogates (`future-work-learned-surrogates-validation`) - not_novel: Too broad and acts as a generic call for future work on model validation rather than pinpointing a standalone unresolved technical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2611.08837)
- [PDF](https://arxiv.org/pdf/2611.08837)

