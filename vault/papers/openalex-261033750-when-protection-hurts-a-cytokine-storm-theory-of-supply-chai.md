---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "When Protection Hurts: A Cytokine Storm Theory of Supply Chain Overreaction"
description: "This paper introduces a decision-theoretic framework to analyze how excessive defensive actions in supply chains can amplify rather than mitigate disruptions. The author defines Protective Response Intensity and Response-Induced Loss, deriving a critical threshold known as a Supply Chain Cytokine Storm where defensive costs exceed original disruptions. Additionally, a Cytokine Storm Index and spectral stability conditions are established to characterize network-wide propagation risks."
resource: "https://arxiv.org/abs/2610.33750"
tags:
  - "demand-forecasting"
  - "stochastic-demands"
  - "time-series"
timestamp: "2026-11-03T12:36:27Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Gurkirat Wadhwa"
issued:
  date-parts:
    - [2026, 10, 24]

# Domain-specific custom fields
paper_id: "2610.33750"
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
processed_at: "2026-11-03T12:36:27Z"
created_at: "2026-11-03T12:36:27Z"
---

# When Protection Hurts: A Cytokine Storm Theory of Supply Chain Overreaction

**Authors**: Gurkirat Wadhwa
**Date**: 2026-10-24
**Paper ID**: [openalex:2610.33750](https://arxiv.org/abs/2610.33750)

## Summary

This paper introduces a decision-theoretic framework to analyze how excessive defensive actions in supply chains can amplify rather than mitigate disruptions. The author defines Protective Response Intensity and Response-Induced Loss, deriving a critical threshold known as a Supply Chain Cytokine Storm where defensive costs exceed original disruptions. Additionally, a Cytokine Storm Index and spectral stability conditions are established to characterize network-wide propagation risks.

## Key Contributions

- Develops a decision-theoretic framework modeling Protective Response Intensity (PRI) and Response-Induced Loss (RIL) in supply chains
- Derives a closed-form critical response threshold termed the Supply Chain Cytokine Storm, beyond which defensive actions worsen the original disruption
- Introduces the Cytokine Storm Index (CSI) to measure response-induced loss relative to original disruption intensity
- Establishes a spectral stability condition for interconnected supply networks distinguishing bounded responses from network-wide propagation

## Limitations

The framework currently relies on idealized theoretical modeling and numerical experiments, requiring further empirical calibration on large-scale operational data.

## Archivist Review

Applied strict filtering standards to ensure that only core concepts and substantial, non-routine open questions are added to the vault. The paper's supply chain-specific game and calibration questions were rejected as domain-specific extensions without broader ML relevance.

### Rejected Candidates
- [open_question] Multi-Agent Strategic Game Analysis (`multi-agent-strategic-game-supply-network`) - not_novel: Future work proposing a standard game-theoretic extension in a supply chain domain without machine learning relevance.
- [open_question] Empirical Estimation of Parameters (`empirical-estimation-cytokine-storm-parameters`) - not_novel: Routine request for empirical parameter calibration on industry data rather than an unresolved algorithmic or theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.33750)
- [PDF](https://arxiv.org/pdf/2610.33750)

