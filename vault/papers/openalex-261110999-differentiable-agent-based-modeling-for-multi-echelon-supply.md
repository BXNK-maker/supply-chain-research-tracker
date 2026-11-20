---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Differentiable Agent-Based Modeling for Multi-Echelon Supply Chains: Gradient-Based Optimization of Heterogeneous Policies at Scale"
description: "This paper proposes a Differentiable Agent-Based Model for multi-echelon inventory management, implementing stochastic simulation dynamics via differentiable tensor operations to enable direct gradient propagation. The approach successfully recovers theoretical Newsvendor optima without supervision and achieves a 53% cost reduction by simultaneously optimizing 10,000 distinct agent policies in seconds. Additionally, gradient sensitivity analysis generates causal heatmaps that accurately recover inherent lead-time delays from the computation graph, offering a bridge between simulation and gradient-based optimization for digital twins."
resource: "https://arxiv.org/abs/2611.10999"
tags:
  - "machine-learning"
  - "reinforcement-learning"
  - "stochastic-demands"
timestamp: "2026-11-20T13:47:30Z"

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
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-20T13:47:30Z"
created_at: "2026-11-20T13:47:30Z"
---

# Differentiable Agent-Based Modeling for Multi-Echelon Supply Chains: Gradient-Based Optimization of Heterogeneous Policies at Scale

**Authors**: Bülent Soykan, Murtadha Alsayegh, Sean C. Mondesire, Ghaith Rabadi
**Date**: 2026-11-07
**Paper ID**: [openalex:2611.10999](https://arxiv.org/abs/2611.10999)

## Summary

This paper proposes a Differentiable Agent-Based Model for multi-echelon inventory management, implementing stochastic simulation dynamics via differentiable tensor operations to enable direct gradient propagation. The approach successfully recovers theoretical Newsvendor optima without supervision and achieves a 53% cost reduction by simultaneously optimizing 10,000 distinct agent policies in seconds. Additionally, gradient sensitivity analysis generates causal heatmaps that accurately recover inherent lead-time delays from the computation graph, offering a bridge between simulation and gradient-based optimization for digital twins.

## Key Contributions

- Proposed a Differentiable Agent-Based Modeling framework for multi-echelon inventory management using differentiable tensor operations.
- Demonstrated Mass Personalization by simultaneously optimizing 10,000 distinct agent policies in seconds, achieving a 53% cost reduction over scalar baselines.
- Utilized gradient sensitivity analysis to generate causal heatmaps and accurately recover inherent lead-time delays from the computation graph.

## Limitations

Limitations are not explicitly discussed in the abstract, but scope is focused on multi-echelon inventory management.

## Archivist Review

All proposed concepts and open questions already exist in the knowledge vault as canonical entries (e.g., differentiable-agent-based-modeling, memory-efficient-bptt-differentiable-abm). Therefore, no new vault entries are created to avoid duplication.

### Rejected Candidates
- [concept] Differentiable Agent-Based Modeling (`differentiable-agent-based-modeling`) - duplicate_existing: Already exists in the knowledge vault as a permanent note.
- [open_question] Memory-Efficient Differentiable ABM (`memory-efficient-differentiable-abm`) - duplicate_existing: Already exists in the knowledge vault under the exact same slug/topic.
- [open_question] Hybrid Gradient and Discrete Solvers (`hybrid-gradient-discrete-solvers`) - duplicate_existing: Closely overlaps with existing optimization and hybrid solver challenges in the vault without introducing a sufficiently distinct bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2611.10999)
- [PDF](https://arxiv.org/pdf/2611.10999)

