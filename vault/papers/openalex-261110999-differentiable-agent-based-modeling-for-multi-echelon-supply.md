---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Differentiable Agent-Based Modeling for Multi-Echelon Supply Chains: Gradient-Based Optimization of Heterogeneous Policies at Scale"
description: "This paper proposes a differentiable agent-based modeling framework for multi-echelon inventory management that implements stochastic dynamics via differentiable tensor operations to enable direct gradient propagation through simulation. The approach successfully recovers theoretical Newsvendor optima without supervision and optimizes 10,000 distinct agent policies simultaneously in seconds, achieving a 53% cost reduction over scalar baselines. Furthermore, the framework leverages gradient sensitivity analysis to generate causal heatmaps and recover inherent lead-time delays directly from the computation graph."
resource: "https://arxiv.org/abs/2611.10999"
tags:
  - "reinforcement-learning"
  - "stochastic-demands"
  - "time-series"
  - "machine-learning"
timestamp: "2026-11-19T14:04:02Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Bülent Soykan"
  - literal: "Murtadha Alsayegh"
  - literal: "Sean C. Mondesire"
  - literal: "Ghaith Rabadi"
issued:
  date-parts:
    - [2026, 11, 7]

# Domain-specific custom fields
paper_id: "2611.10999"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "differentiable-agent-based-modeling"
    description: "An agent-based modeling paradigm implemented via differentiable tensor operations that enables direct gradient propagation through simulation dynamics."
datasets:
  []
open_questions:
  - name: "memory-efficient-bptt-differentiable-abm"
    description: "Future work involves addressing the memory constraints of backpropagation through time (BPTT) in differentiable agent-based modeling by incorporating gradient checkpointing or implicit differentiation techniques to reduce memory usage for long time horizons."
skill: "GeneralMLSkill"
processed_at: "2026-11-19T14:04:02Z"
created_at: "2026-11-19T14:04:02Z"
---

# Differentiable Agent-Based Modeling for Multi-Echelon Supply Chains: Gradient-Based Optimization of Heterogeneous Policies at Scale

**Authors**: Bülent Soykan, Murtadha Alsayegh, Sean C. Mondesire, Ghaith Rabadi
**Date**: 2026-11-07
**Paper ID**: [openalex:2611.10999](https://arxiv.org/abs/2611.10999)

## Summary

This paper proposes a differentiable agent-based modeling framework for multi-echelon inventory management that implements stochastic dynamics via differentiable tensor operations to enable direct gradient propagation through simulation. The approach successfully recovers theoretical Newsvendor optima without supervision and optimizes 10,000 distinct agent policies simultaneously in seconds, achieving a 53% cost reduction over scalar baselines. Furthermore, the framework leverages gradient sensitivity analysis to generate causal heatmaps and recover inherent lead-time delays directly from the computation graph.

## Key Contributions

- Proposed a differentiable agent-based modeling framework for multi-echelon inventory management enabling direct gradient propagation through stochastic simulation dynamics.
- Demonstrated mass personalization by optimizing 10,000 distinct agent policies simultaneously in seconds, achieving a 53% cost reduction over scalar baselines.
- Utilized gradient sensitivity analysis to generate causal heatmaps and accurately recover inherent lead-time delays directly from the computation graph.

## Limitations

Limitations and scalability bounds under highly non-stationary environments or adversarial multi-agent dynamics are not explicitly detailed in the abstract.

## Open Questions & Future Work

- [[memory-efficient-bptt-differentiable-abm]]

## Key Concepts

- [[differentiable-agent-based-modeling]]: An agent-based modeling paradigm implemented via differentiable tensor operations that enables direct gradient propagation through simulation dynamics.

## Archivist Review

Approved Differentiable Agent-Based Modeling as a core concept already present or suitable for vault inclusion, and the open question regarding memory-efficient backpropagation through time for differentiable agent-based modeling. Rejected mass personalization as a descriptive application term.

### Approved Concepts
- Differentiable Agent-Based Modeling: Enables direct gradient propagation through complex multi-agent supply chain simulations for gradient-based policy optimization.

### Approved Open Questions
- Memory-Efficient BPTT for Differentiable ABM: Memory complexity scales linearly with time and agent count, posing a critical scalability bottleneck for applying differentiable simulations to long-horizon supply chain forecasting and optimization.

### Rejected Candidates
- [concept] Mass Personalization (`mass-personalization`) - subcomponent_of_broader_mechanism: Term used here as an application of optimizing distinct policies rather than a distinct algorithmic architecture or method.

## Links

- [Abstract](https://arxiv.org/abs/2611.10999)
- [PDF](https://arxiv.org/pdf/2611.10999)

