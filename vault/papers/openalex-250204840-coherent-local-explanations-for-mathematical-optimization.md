---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Coherent local explanations for mathematical optimization"
description: "Explaining decisions in mathematical optimization is underexplored, and standard XAI methods like LIME often fail because they ignore underlying problem structure and feasibility constraints. The authors introduce CLEMO (Coherent Local Explanations for Mathematical Optimization), which simultaneously explains objective values and decision variables while ensuring structural coherence. Experiments across shortest path, knapsack, and vehicle routing problems demonstrate the method's effectiveness."
resource: "https://arxiv.org/abs/2502.04840"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "interpretable-machine-learning"
timestamp: "2026-11-01T11:36:56Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Daan Otto"
  - literal: "Jannis Kurtz"
  - literal: "Ş. İlker Birbil"
issued:
  date-parts:
    - [2026, 10, 19]

# Domain-specific custom fields
paper_id: "2502.04840"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "clemo"
    description: "A method for explaining mathematical optimization decisions by simultaneously accounting for objective values and decision variable feasibility."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:36:56Z"
created_at: "2026-11-01T11:36:56Z"
---

# Coherent local explanations for mathematical optimization

**Authors**: Daan Otto, Jannis Kurtz, Ş. İlker Birbil
**Date**: 2026-10-19
**Paper ID**: [openalex:2502.04840](https://arxiv.org/abs/2502.04840)

## Summary

Explaining decisions in mathematical optimization is underexplored, and standard XAI methods like LIME often fail because they ignore underlying problem structure and feasibility constraints. The authors introduce CLEMO (Coherent Local Explanations for Mathematical Optimization), which simultaneously explains objective values and decision variables while ensuring structural coherence. Experiments across shortest path, knapsack, and vehicle routing problems demonstrate the method's effectiveness.

## Key Contributions

- Introduces CLEMO (Coherent Local Explanations for Mathematical Optimization) to explain both objective values and decision variables while preserving problem structure coherence.
- Addresses the limitations of standard XAI methods like LIME that ignore underlying optimization and feasibility constraints.
- Demonstrates effectiveness on shortest path, knapsack, and vehicle routing problems.

## Key Concepts

- [[clemo]]: A method for explaining mathematical optimization decisions by simultaneously accounting for objective values and decision variable feasibility.

## Archivist Review

Approved the core concept CLEMO, mapping its slug to the existing vault entry 'clemo'. No datasets or open questions met the stringent inclusion threshold.

### Approved Concepts
- Coherent Local Explanations for Mathematical Optimization (CLEMO): It is the core methodological contribution of the paper, bridging explainable AI and mathematical optimization by maintaining structural coherence.

## Links

- [Abstract](https://arxiv.org/abs/2502.04840)
- [PDF](https://arxiv.org/pdf/2502.04840)

