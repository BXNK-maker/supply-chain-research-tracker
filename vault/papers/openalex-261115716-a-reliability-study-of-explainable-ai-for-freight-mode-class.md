---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Reliability Study of Explainable AI for Freight Mode Classification"
description: "This study investigates the reliability of explainable machine learning models for freight mode classification (Air/Air Charter vs. Truck/Ocean) using the PEPFAR Supply Chain Management System Delivery History dataset. The authors compare Logistic Regression, Random Forest, gradient boosting, and MLPs across one hundred random replications, evaluating both classification performance and explanation reliability through SHAP stability, LIME faithfulness, and geographic destination effects. Results reveal that tree ensembles achieve superior accuracy and feature stability, while feature-deletion tests confirm that top-ranked attribution features significantly impact model predictions. However, the substantial disagreement in feature importance across models with similar accuracy emphasizes that explanation stability and faithfulness must be verified prior to supporting operational freight transport decisions."
resource: "https://arxiv.org/abs/2611.15716"
tags:
  - "interpretable-machine-learning"
  - "machine-learning"
timestamp: "2026-11-19T14:11:40Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Ali Alawi Balfaqih"
  - literal: "Mansur Arief"
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
  - name: "robustness-of-post-hoc-explanations"
    description: "Investigate the impact of larger explanation sample sizes, alternative background dataset selection methods, and more advanced feature replacement strategies on the stability and robustness of post-hoc explanations in tabular models."
skill: "GeneralMLSkill"
processed_at: "2026-11-19T14:11:40Z"
created_at: "2026-11-19T14:11:40Z"
---

# A Reliability Study of Explainable AI for Freight Mode Classification

**Authors**: Ali Alawi Balfaqih, Mansur Arief, Ali Alawi Balfaqih, Mansur Arief
**Date**: 2026-11-11
**Paper ID**: [openalex:2611.15716](https://arxiv.org/abs/2611.15716)

## Summary

This study investigates the reliability of explainable machine learning models for freight mode classification (Air/Air Charter vs. Truck/Ocean) using the PEPFAR Supply Chain Management System Delivery History dataset. The authors compare Logistic Regression, Random Forest, gradient boosting, and MLPs across one hundred random replications, evaluating both classification performance and explanation reliability through SHAP stability, LIME faithfulness, and geographic destination effects. Results reveal that tree ensembles achieve superior accuracy and feature stability, while feature-deletion tests confirm that top-ranked attribution features significantly impact model predictions. However, the substantial disagreement in feature importance across models with similar accuracy emphasizes that explanation stability and faithfulness must be verified prior to supporting operational freight transport decisions.

## Key Contributions

- Evaluated explainable machine learning reliability for freight mode classification using tree ensembles, neural networks, and linear models across 100 random replications.
- Demonstrated that tree ensembles significantly outperform neural and linear models, achieving 86.8% mean testing accuracy while maintaining the most stable leading SHAP feature rankings across retraining.
- Showed via feature-deletion tests that removing the top 5 features ranked by SHAP or LIME changes predicted probabilities roughly four times as much as removing random features.
- Found that models with similar predictive accuracy disagree substantially on feature importance, highlighting the necessity of assessing explanation stability and faithfulness before deployment in transport decisions.

## Limitations

Models with comparable predictive accuracy disagree substantially on which features matter most, underscoring risks in relying on single explanations without rigorous reliability testing.

## Open Questions & Future Work

- [[robustness-of-post-hoc-explanations]]

## Archivist Review

Approved the open question on post-hoc explanation robustness as it addresses a fundamental and recurring limitation in XAI reliability. Rejected the dataset as a specialized application-domain dataset of low broader reusability across general ML vault topics.

### Approved Open Questions
- Robustness of Post-Hoc Explanations: Post-hoc attribution methods are sensitive to background data selection and replacement strategies, and rigorous robustness benchmarking is essential for dependable operational deployment.

### Rejected Candidates
- [dataset] PEPFAR Supply Chain Management System Delivery History dataset (`pepfar-supply-chain-management-system-delivery-history-dataset`) - low_impact: Domain-specific proprietary/administrative dataset that is not a standard general machine learning benchmark or foundational corpus.

## Links

- [Abstract](https://arxiv.org/abs/2611.15716)
- [PDF](https://arxiv.org/pdf/2611.15716)

