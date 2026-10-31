---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Coherent local explanations for mathematical optimization"
description: "Explaining decisions in mathematical optimization is challenging because standard XAI techniques ignore underlying problem structure and feasibility. The authors introduce Coherent Local Explanations for Mathematical Optimization (CLEMO), a framework that explains both objective values and decision variables while preserving problem coherence. Experiments on shortest path, knapsack, and vehicle routing problems show that CLEMO provides reliable explanations respecting problem constraints."
resource: "https://arxiv.org/abs/2502.04840"
tags:
  - "combinatorial-optimization"
  - "interpretable-machine-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-31T10:41:54Z"

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
    description: "A local explanation method for mathematical optimization that ensures coherence with problem structure, feasibility, and objective values."
datasets:
  []
open_questions:
  - name: "extensions-of-coherent-local-explanations-for-mathematical-optimization"
    description: "Future work involves extending the Coherent Local Explanations for Mathematical Optimization (CLEMO) framework to explain additional components such as constraint slacks, algorithmic runtime, and optimality gaps, as well as exploring alternative interpretable surrogate function families like decision trees and investigating synergies between machine learning and optimization models in predict-then-optimize frameworks."
skill: "GeneralMLSkill"
processed_at: "2026-10-31T10:41:54Z"
created_at: "2026-10-31T10:41:54Z"
---

# Coherent local explanations for mathematical optimization

**Authors**: Daan Otto, Jannis Kurtz, Ş. İlker Birbil
**Date**: 2026-10-19
**Paper ID**: [openalex:2502.04840](https://arxiv.org/abs/2502.04840)

## Summary

Explaining decisions in mathematical optimization is challenging because standard XAI techniques ignore underlying problem structure and feasibility. The authors introduce Coherent Local Explanations for Mathematical Optimization (CLEMO), a framework that explains both objective values and decision variables while preserving problem coherence. Experiments on shortest path, knapsack, and vehicle routing problems show that CLEMO provides reliable explanations respecting problem constraints.

## Key Contributions

- Introduces CLEMO, a novel explainable AI framework designed specifically for mathematical optimization that simultaneously explains decision variables and objective values.
- Incorporates the underlying problem structure and feasibility of decision variables into the explanation process, overcoming limitations of unstructured methods like LIME.
- Demonstrates effectiveness across multiple combinatorial optimization tasks including shortest path, knapsack, and vehicle routing problems.

## Open Questions & Future Work

- [[extensions-of-coherent-local-explanations-for-mathematical-optimization]]

## Key Concepts

- [[clemo]]: A local explanation method for mathematical optimization that ensures coherence with problem structure, feasibility, and objective values.

## Archivist Review

Approved the core framework concept (CLEMO) as a reusable contribution bridging XAI and combinatorial optimization, along with the specific open research directions regarding its extension. No new datasets were qualified for standalone vault entry.

### Approved Concepts
- Coherent Local Explanations for Mathematical Optimization: Introduces a novel explainability framework specifically tailored to mathematical optimization problems, bridging XAI and operations research.

### Approved Open Questions
- Extensions of Coherent Local Explanations: Extending structural coherence explanation methods to broader optimization outputs and alternative surrogate models is crucial for generalizability across operations research and machine learning applications.

## Links

- [Abstract](https://arxiv.org/abs/2502.04840)
- [PDF](https://arxiv.org/pdf/2502.04840)

