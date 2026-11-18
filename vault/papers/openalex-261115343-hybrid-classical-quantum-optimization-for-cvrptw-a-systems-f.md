---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hybrid Classical-Quantum Optimization for CVRPTW: A Systems Framework with Provable Feasibility and Empirical Hardware Limits"
description: "This paper presents a hybrid classical-quantum systems framework for solving the Capacitated Vehicle Routing Problem with Time Windows (CVRPTW) by decomposing monolithic problems into vehicle-level QUBOs solved via classical simulated bifurcation and near-term quantum processors. Evaluated on realistic London traffic benchmarks, the approach demonstrates verified fleet-distance reductions while establishing empirical hardware limits for QAOA constraint satisfaction. Diagnostic analysis further reveals that time-window tightness serves as the primary scalability bottleneck for these hybrid solvers."
resource: "https://arxiv.org/abs/2611.15343"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "quantum-reinforcement-learning"
  - "nisq-systems"
timestamp: "2026-11-18T13:50:04Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Syamasundar Gopasana"
  - literal: "Swatantra Singh"
  - literal: "Rohan Joydhar"
  - literal: "Shubhashis Sengupta"
issued:
  date-parts:
    - [2026, 11, 11]

# Domain-specific custom fields
paper_id: "2611.15343"
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
processed_at: "2026-11-18T13:50:04Z"
created_at: "2026-11-18T13:50:04Z"
---

# Hybrid Classical-Quantum Optimization for CVRPTW: A Systems Framework with Provable Feasibility and Empirical Hardware Limits

**Authors**: Syamasundar Gopasana, Swatantra Singh, Rohan Joydhar, Shubhashis Sengupta
**Date**: 2026-11-11
**Paper ID**: [openalex:2611.15343](https://arxiv.org/abs/2611.15343)

## Summary

This paper presents a hybrid classical-quantum systems framework for solving the Capacitated Vehicle Routing Problem with Time Windows (CVRPTW) by decomposing monolithic problems into vehicle-level QUBOs solved via classical simulated bifurcation and near-term quantum processors. Evaluated on realistic London traffic benchmarks, the approach demonstrates verified fleet-distance reductions while establishing empirical hardware limits for QAOA constraint satisfaction. Diagnostic analysis further reveals that time-window tightness serves as the primary scalability bottleneck for these hybrid solvers.

## Key Contributions

- Proposed a hybrid classical-quantum architecture combining MILP with vehicle-level QUBO for solving CVRPTW.
- Achieved fleet-distance reductions of 2.80% on 25-customer and 0.22% on 55-customer realistic benchmarks using Toshiba SQBM+.
- Established current quantum hardware boundaries for reliable constraint satisfaction using QAOA on Rigetti Ankaa-3 and IQM Emerald up to 4 customers (16 qubits).
- Identified assignment-level time-window tightness as the dominant scalability bottleneck rather than local route optimization.

## Archivist Review

The single candidate open question was rejected because it is narrowly tied to near-term quantum hardware benchmarking and specific NISQ processors rather than representing a broad, enduring ML or optimization bottleneck. No concepts or datasets were proposed or approved, maintaining strict selectivity for the vault.

### Rejected Candidates
- [open_question] Algorithm versus Hardware Contributions (`quantum-algorithm-hardware-co-design`) - paper_local: The proposed question is too paper-local and specific to near-term quantum hardware benchmarking rather than a foundational, recurring open bottleneck across diverse ML fields.

## Links

- [Abstract](https://arxiv.org/abs/2611.15343)
- [PDF](https://arxiv.org/pdf/2611.15343)

