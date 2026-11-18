---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Differentiable Agent-Based Modeling for Multi-Echelon Supply Chains: Gradient-Based Optimization of Heterogeneous Policies at Scale"
description: "The paper proposes a Differentiable Agent-Based Modeling framework for multi-echelon supply chain inventory management by implementing stochastic dynamics via differentiable tensor operations. This allows direct gradient propagation through the simulation, bypassing the sample inefficiency of traditional reinforcement learning. The approach successfully recovers theoretical Newsvendor optima and achieves Mass Personalization by optimizing 10,000 distinct agent policies simultaneously in seconds, yielding a 53% cost reduction over scalar baselines. Additionally, gradient sensitivity analysis is used to construct causal heatmaps that accurately recover inherent lead-time delays, providing a foundation for self-correcting Digital Twins."
resource: "https://arxiv.org/abs/2611.10999"
tags:
  - "reinforcement-learning"
  - "demand-forecasting"
  - "stochastic-demands"
  - "machine-learning"
timestamp: "2026-11-18T13:41:54Z"

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
    description: "An agent-based modeling paradigm implemented via differentiable tensor operations to enable gradient-based policy optimization at scale."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-18T13:41:54Z"
created_at: "2026-11-18T13:41:54Z"
---

# Differentiable Agent-Based Modeling for Multi-Echelon Supply Chains: Gradient-Based Optimization of Heterogeneous Policies at Scale

**Authors**: Bülent Soykan, Murtadha Alsayegh, Sean C. Mondesire, Ghaith Rabadi
**Date**: 2026-11-07
**Paper ID**: [openalex:2611.10999](https://arxiv.org/abs/2611.10999)

## Summary

The paper proposes a Differentiable Agent-Based Modeling framework for multi-echelon supply chain inventory management by implementing stochastic dynamics via differentiable tensor operations. This allows direct gradient propagation through the simulation, bypassing the sample inefficiency of traditional reinforcement learning. The approach successfully recovers theoretical Newsvendor optima and achieves Mass Personalization by optimizing 10,000 distinct agent policies simultaneously in seconds, yielding a 53% cost reduction over scalar baselines. Additionally, gradient sensitivity analysis is used to construct causal heatmaps that accurately recover inherent lead-time delays, providing a foundation for self-correcting Digital Twins.

## Key Contributions

- Proposes a Differentiable Agent-Based Modeling framework for multi-echelon inventory management using differentiable tensor operations.
- Recovers theoretical Newsvendor optima without supervision by enabling direct gradient propagation through simulation dynamics.
- Demonstrates Mass Personalization by optimizing 10,000 distinct agent policies simultaneously in seconds, achieving a 53% cost reduction over scalar baselines.
- Utilizes gradient sensitivity analysis to generate causal heatmaps and accurately recover lead-time delays from computation graphs.

## Key Concepts

- [[differentiable-agent-based-modeling]]: An agent-based modeling paradigm implemented via differentiable tensor operations to enable gradient-based policy optimization at scale.

## Archivist Review

Approved the central methodological concept of differentiable agent-based modeling, which is highly reusable for gradient-based optimization in multi-agent systems and supply chains. Rejected the open question because its scope is too broad and speculative.

### Approved Concepts
- Differentiable Agent-Based Modeling: Enables direct gradient propagation through complex agent-based simulations via differentiable tensor operations, bridging simulation and optimization.

### Rejected Candidates
- [open_question] Real-World Digital Twin Calibration (`data-driven-digital-twin-calibration-and-graph-policies`) - low_impact: Future work direction combining digital twin calibration and graph neural policies is too broad and speculative compared to existing vault questions.

## Links

- [Abstract](https://arxiv.org/abs/2611.10999)
- [PDF](https://arxiv.org/pdf/2611.10999)

