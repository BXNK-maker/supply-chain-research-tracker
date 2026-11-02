---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Coherent local explanations for mathematical optimization"
description: "Explaining decisions in mathematical optimization is challenging because standard explainable AI methods ignore problem structure and feasibility constraints. The authors introduce CLEMO (Coherent Local Explanations for Mathematical Optimization), a novel approach that simultaneously explains objective values and decision variables while remaining coherent with the underlying problem structure. Empirical evaluations on shortest path, knapsack, and vehicle routing problems demonstrate the effectiveness of the proposed framework."
resource: "https://arxiv.org/abs/2502.04840"
tags:
  - "combinatorial-optimization"
  - "interpretable-machine-learning"
  - "vehicle-routing-problem"
timestamp: "2026-11-02T13:04:32Z"

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
    description: "A method for generating local explanations for mathematical optimization models that simultaneously explains objective values and decision variables while respecting problem constraints and structure."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-02T13:04:32Z"
created_at: "2026-11-02T13:04:32Z"
---

# Coherent local explanations for mathematical optimization

**Authors**: Daan Otto, Jannis Kurtz, Ş. İlker Birbil
**Date**: 2026-10-19
**Paper ID**: [openalex:2502.04840](https://arxiv.org/abs/2502.04840)

## Summary

Explaining decisions in mathematical optimization is challenging because standard explainable AI methods ignore problem structure and feasibility constraints. The authors introduce CLEMO (Coherent Local Explanations for Mathematical Optimization), a novel approach that simultaneously explains objective values and decision variables while remaining coherent with the underlying problem structure. Empirical evaluations on shortest path, knapsack, and vehicle routing problems demonstrate the effectiveness of the proposed framework.

## Key Contributions

- Introduces Coherent Local Explanations for Mathematical Optimization (CLEMO), a framework for explaining optimization decisions that preserves underlying problem structure.
- Simultaneously explains both objective function values and decision variable assignments while accounting for feasibility constraints.
- Demonstrates effectiveness on shortest path, knapsack, and vehicle routing problems.

## Key Concepts

- [[clemo]]: A method for generating local explanations for mathematical optimization models that simultaneously explains objective values and decision variables while respecting problem constraints and structure.

## Archivist Review

Approved the canonical concept 'clemo', mapping it to the existing vault slug 'clemo'. Rejected the open question as it is a routine future work suggestion for extending features and surrogate families.

### Approved Concepts
- Coherent Local Explanations for Mathematical Optimization (CLEMO): It directly addresses the core methodological gap of explaining decisions in mathematical optimization while preserving problem structure and feasibility.

### Rejected Candidates
- [open_question] Extended Components and Surrogates for Optimization Explanations (`extended-components-and-surrogates-for-optimization-explanations`) - not_novel: The open question is essentially a routine future work direction suggesting more components and surrogate types rather than a substantive, self-contained bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2502.04840)
- [PDF](https://arxiv.org/pdf/2502.04840)

