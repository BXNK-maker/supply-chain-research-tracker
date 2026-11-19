---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hybrid Classical-Quantum Optimization for CVRPTW: A Systems Framework with Provable Feasibility and Empirical Hardware Limits"
description: "This paper presents a hybrid classical-quantum optimization framework for the Capacitated Vehicle Routing Problem with Time Windows (CVRPTW), combining Mixed Integer Linear Programming with vehicle-level QUBO decomposition to circumvent the limitations of monolithic formulations. The approach is evaluated using Toshiba SQBM+ and QAOA on Rigetti Ankaa-3 and IQM Emerald processors across London traffic benchmarks of 10 to 70 customers. Results demonstrate consistent fleet-distance improvements using classical-simulated annealing solvers, while establishing current hardware boundaries for reliable constraint satisfaction with near-term quantum processors."
resource: "https://arxiv.org/abs/2611.15343"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "nisq-systems"
timestamp: "2026-11-19T14:13:03Z"

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
processed_at: "2026-11-19T14:13:03Z"
created_at: "2026-11-19T14:13:03Z"
---

# Hybrid Classical-Quantum Optimization for CVRPTW: A Systems Framework with Provable Feasibility and Empirical Hardware Limits

**Authors**: Syamasundar Gopasana, Swatantra Singh, Rohan Joydhar, Shubhashis Sengupta
**Date**: 2026-11-11
**Paper ID**: [openalex:2611.15343](https://arxiv.org/abs/2611.15343)

## Summary

This paper presents a hybrid classical-quantum optimization framework for the Capacitated Vehicle Routing Problem with Time Windows (CVRPTW), combining Mixed Integer Linear Programming with vehicle-level QUBO decomposition to circumvent the limitations of monolithic formulations. The approach is evaluated using Toshiba SQBM+ and QAOA on Rigetti Ankaa-3 and IQM Emerald processors across London traffic benchmarks of 10 to 70 customers. Results demonstrate consistent fleet-distance improvements using classical-simulated annealing solvers, while establishing current hardware boundaries for reliable constraint satisfaction with near-term quantum processors.

## Key Contributions

- Introduces a hybrid classical-quantum architecture combining MILP with vehicle-level QUBO decomposition to avoid variable growth and constraint-enforcement difficulties in monolithic CVRPTW QUBO formulations.
- Evaluates the framework on five realistic London traffic and location benchmarks (10–70 customers), demonstrating verified fleet-distance reductions of 2.80% for 25 customers and 0.22% for 55 customers using Toshiba SQBM+.
- Establishes current quantum hardware boundaries using QAOA on Rigetti Ankaa-3 and IQM Emerald processors, achieving reliable constraint satisfaction at subproblems of up to 4 customers (16 qubits).
- Identifies assignment-level time-window tightness as the dominant scalability bottleneck rather than local route optimization through diagnostic results.

## Limitations

Current quantum hardware is limited to reliable constraint satisfaction for subproblems of up to 4 customers (16 qubits) using QAOA.

## Links

- [Abstract](https://arxiv.org/abs/2611.15343)
- [PDF](https://arxiv.org/pdf/2611.15343)

