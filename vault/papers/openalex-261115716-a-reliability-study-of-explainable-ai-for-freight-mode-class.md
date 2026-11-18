---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Reliability Study of Explainable AI for Freight Mode Classification"
description: "This study investigates the reliability of explainable machine learning models for freight mode classification using the PEPFAR Supply Chain Management System Delivery History dataset. The authors compare neural, linear, and tree-based models across one hundred random replications, finding that tree ensembles achieve superior accuracy. They further evaluate explanation stability via SHAP feature rankings across retraining and model types, as well as attribution faithfulness via feature-deletion tests. The findings demonstrate that explanation stability and faithfulness vary significantly across models, suggesting they must be rigorously assessed before guiding freight transportation decisions."
resource: "https://arxiv.org/abs/2611.15716"
tags:
  - "interpretable-machine-learning"
  - "machine-learning"
timestamp: "2026-11-18T13:44:53Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Ali Alawi Balfaqih"
  - literal: "Mansur Arief"
issued:
  date-parts:
    - [2026, 11, 11]

# Domain-specific custom fields
paper_id: "2611.15716"
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
processed_at: "2026-11-18T13:44:53Z"
created_at: "2026-11-18T13:44:53Z"
---

# A Reliability Study of Explainable AI for Freight Mode Classification

**Authors**: Ali Alawi Balfaqih, Mansur Arief
**Date**: 2026-11-11
**Paper ID**: [openalex:2611.15716](https://arxiv.org/abs/2611.15716)

## Summary

This study investigates the reliability of explainable machine learning models for freight mode classification using the PEPFAR Supply Chain Management System Delivery History dataset. The authors compare neural, linear, and tree-based models across one hundred random replications, finding that tree ensembles achieve superior accuracy. They further evaluate explanation stability via SHAP feature rankings across retraining and model types, as well as attribution faithfulness via feature-deletion tests. The findings demonstrate that explanation stability and faithfulness vary significantly across models, suggesting they must be rigorously assessed before guiding freight transportation decisions.

## Key Contributions

- Compared three MLP architectures, Logistic Regression, Random Forest, and gradient boosting on freight mode classification across one hundred random replications using imbalance-aware metrics.
- Demonstrated that tree ensembles significantly outperform neural and linear models (86.8% vs 83.3-85.0% mean testing accuracy).
- Evaluated explanation stability and faithfulness, showing that removing top SHAP/LIME features changes predicted probabilities roughly four times as much as removing random features.
- Revealed that models with similar accuracy disagree substantially on feature importance, highlighting the necessity of assessing explanation reliability before deployment in freight transport decisions.

## Archivist Review

Applied strict selection standards: rejected the domain-specific open question as it focuses on incremental dataset generalization and routine robustness checks rather than a fundamental algorithmic bottleneck.

### Rejected Candidates
- [open_question] Generalizing XAI Reliability in Freight Logistics (`generalizing-xai-reliability-freight-logistics`) - low_impact: This is a domain-specific evaluation extension and robustness check rather than a standalone theoretical or architectural bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2611.15716)
- [PDF](https://arxiv.org/pdf/2611.15716)

