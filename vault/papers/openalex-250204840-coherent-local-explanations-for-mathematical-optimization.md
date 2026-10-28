---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Coherent local explanations for mathematical optimization"
description: "Explaining decisions in mathematical optimization is often hindered by standard XAI methods that ignore problem structure. To overcome this, the authors introduce CLEMO (Coherent Local Explanations for Mathematical Optimization), which simultaneously explains objective values and decision variables while preserving feasibility and problem structure. Empirical evaluations on shortest path, knapsack, and vehicle routing problems demonstrate its effectiveness over unstructured approaches like LIME."
resource: "https://arxiv.org/abs/2502.04840"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
  - "interpretable-machine-learning"
timestamp: "2026-10-28T10:58:11Z"

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
    description: "An explainable AI framework that generates coherent local explanations for both objective values and decision variables in mathematical optimization problems."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-28T10:58:11Z"
created_at: "2026-10-28T10:58:11Z"
---

# Coherent local explanations for mathematical optimization

**Authors**: Daan Otto, Jannis Kurtz, Ş. İlker Birbil
**Date**: 2026-10-19
**Paper ID**: [openalex:2502.04840](https://arxiv.org/abs/2502.04840)

## Summary

Explaining decisions in mathematical optimization is often hindered by standard XAI methods that ignore problem structure. To overcome this, the authors introduce CLEMO (Coherent Local Explanations for Mathematical Optimization), which simultaneously explains objective values and decision variables while preserving feasibility and problem structure. Empirical evaluations on shortest path, knapsack, and vehicle routing problems demonstrate its effectiveness over unstructured approaches like LIME.

## Key Contributions

- Introduced CLEMO (Coherent Local Explanations for Mathematical Optimization) to explain both objective values and decision variables simultaneously.
- Ensures coherence with underlying mathematical optimization problem structures, addressing the limitations of unstructured methods like LIME.
- Demonstrated effectiveness across shortest path, knapsack, and vehicle routing problems.

## Key Concepts

- [[clemo]]: An explainable AI framework that generates coherent local explanations for both objective values and decision variables in mathematical optimization problems.

## Archivist Review

Approved CLEMO as a reusable framework for explainable mathematical optimization. Rejected the generic combinatorial optimization benchmark label as it represents broad problem domains rather than a specific named dataset.

### Approved Concepts
- Coherent Local Explanations for Mathematical Optimization (CLEMO): Introduces a novel explainable AI framework explicitly tailored for mathematical optimization that guarantees structural coherence for both objective values and decision variables.

### Rejected Candidates
- [dataset] combinatorial-optimization-benchmarks (`combinatorial-optimization-benchmarks`) - generic: Generic aggregate label for standard problem classes rather than a specific named dataset.

## Links

- [Abstract](https://arxiv.org/abs/2502.04840)
- [PDF](https://arxiv.org/pdf/2502.04840)

