---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Coherent local explanations for mathematical optimization"
description: "Explaining decisions in mathematical optimization is challenging because standard XAI methods like LIME ignore problem structure and feasibility. This paper introduces CLEMO (Coherent Local Explanations for Mathematical Optimization), a framework that simultaneously explains objective values and decision variables while maintaining structural coherence. Experiments across shortest path, knapsack, and vehicle routing problems demonstrate the method's effectiveness."
resource: "https://arxiv.org/abs/2502.04840"
tags:
  - "combinatorial-optimization"
  - "interpretable-machine-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-29T11:14:33Z"

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
    description: "A local explanation method for mathematical optimization that simultaneously explains objective values and decision variables while respecting problem structure and feasibility."
datasets:
  []
open_questions:
  - name: "extending-clemo-components-and-surrogates"
    description: "Extend coherent local explanation frameworks beyond objective values and decision variables to incorporate other model components such as constraint slacks, algorithmic runtime, and optimality gaps, as well as investigate alternative classes of interpretable surrogate functions like decision trees instead of parametric linear models."
skill: "GeneralMLSkill"
processed_at: "2026-10-29T11:14:33Z"
created_at: "2026-10-29T11:14:33Z"
---

# Coherent local explanations for mathematical optimization

**Authors**: Daan Otto, Jannis Kurtz, Ş. İlker Birbil
**Date**: 2026-10-19
**Paper ID**: [openalex:2502.04840](https://arxiv.org/abs/2502.04840)

## Summary

Explaining decisions in mathematical optimization is challenging because standard XAI methods like LIME ignore problem structure and feasibility. This paper introduces CLEMO (Coherent Local Explanations for Mathematical Optimization), a framework that simultaneously explains objective values and decision variables while maintaining structural coherence. Experiments across shortest path, knapsack, and vehicle routing problems demonstrate the method's effectiveness.

## Key Contributions

- Introduces Coherent Local Explanations for Mathematical Optimization (CLEMO) to explain both objective values and decision variables simultaneously.
- Ensures coherence with the underlying problem structure and feasibility of decision variables, overcoming limitations of unstructured XAI methods like LIME.
- Demonstrates effectiveness on shortest path, knapsack, and vehicle routing problems.

## Open Questions & Future Work

- [[extending-clemo-components-and-surrogates]]

## Key Concepts

- [[clemo]]: A local explanation method for mathematical optimization that simultaneously explains objective values and decision variables while respecting problem structure and feasibility.

## Archivist Review

Approved CLEMO as it is already present in the vault as an established concept, along with its associated open question on extending optimization explainability components. No datasets are approved as the paper evaluates on standard problem domains rather than specific named datasets.

### Approved Concepts
- CLEMO: Introduces a novel explainable AI framework specifically designed for mathematical optimization that preserves feasibility and problem structure.

### Approved Open Questions
- Extending Components and Surrogates in Optimization Explainability: Broadening explainability to constraints, runtime, and non-linear surrogate functions is critical for comprehensive transparency in complex mixed-integer and heuristic optimization pipelines.

## Links

- [Abstract](https://arxiv.org/abs/2502.04840)
- [PDF](https://arxiv.org/pdf/2502.04840)

