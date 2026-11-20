---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hybrid Classical-Quantum Optimization for CVRPTW: A Systems Framework with Provable Feasibility and Empirical Hardware Limits"
description: "The paper presents a hybrid classical-quantum systems framework for solving the Capacitated Vehicle Routing Problem with Time Windows (CVRPTW) by combining Mixed Integer Linear Programming with vehicle-level QUBO formulations solved via classical and quantum annealers/processors. Evaluated on London traffic benchmarks, the method achieves verified fleet-distance reductions while empirically establishing current hardware limits of QAOA up to 16 qubits."
resource: "https://arxiv.org/abs/2611.15343"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "nisq-systems"
  - "quantum-reinforcement-learning"
timestamp: "2026-11-20T13:49:23Z"

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
processed_at: "2026-11-20T13:49:23Z"
created_at: "2026-11-20T13:49:23Z"
---

# Hybrid Classical-Quantum Optimization for CVRPTW: A Systems Framework with Provable Feasibility and Empirical Hardware Limits

**Authors**: Syamasundar Gopasana, Swatantra Singh, Rohan Joydhar, Shubhashis Sengupta
**Date**: 2026-11-11
**Paper ID**: [openalex:2611.15343](https://arxiv.org/abs/2611.15343)

## Summary

The paper presents a hybrid classical-quantum systems framework for solving the Capacitated Vehicle Routing Problem with Time Windows (CVRPTW) by combining Mixed Integer Linear Programming with vehicle-level QUBO formulations solved via classical and quantum annealers/processors. Evaluated on London traffic benchmarks, the method achieves verified fleet-distance reductions while empirically establishing current hardware limits of QAOA up to 16 qubits.

## Key Contributions

- Proposes a hybrid classical-quantum architecture combining MILP with vehicle-level QUBO for the Capacitated Vehicle Routing Problem with Time Windows (CVRPTW).
- Evaluates the framework on five realistic benchmarks derived from London traffic and location data ranging from 10 to 70 customers.
- Demonstrates fleet-distance reductions of 2.80% for 25-customer instances and 0.22% for 55-customer instances using Toshiba SQBM+.
- Establishes current hardware boundaries for QAOA on Rigetti Ankaa-3 and IQM Emerald, finding reliable constraint satisfaction up to 4 customers (16 qubits).

## Limitations

Assignment-level time-window tightness acts as the dominant scalability bottleneck rather than local route optimization.

## Archivist Review

Applied strict filtering standards to ensure only highly reusable concepts and broadly generalizable open questions enter the vault. No concepts or open questions met the high bar for permanence in this iteration.

### Rejected Candidates
- [open_question] Quantum-Informed Assignment for Scalable Routing (`quantum-informed-assignment-cvrptw`) - paper_local: The question is too paper-local, specifically targeting assignment-level time-window tightness in vehicle routing subproblem decompositions rather than a broad, reusable ML or optimization bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2611.15343)
- [PDF](https://arxiv.org/pdf/2611.15343)

