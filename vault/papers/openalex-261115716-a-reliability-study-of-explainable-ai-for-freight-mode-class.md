---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Reliability Study of Explainable AI for Freight Mode Classification"
description: "This study investigates the reliability of explainable AI methods (SHAP and LIME) for freight mode classification using the PEPFAR supply chain dataset. The authors compare multiple machine learning architectures across 100 random replications, evaluating both predictive accuracy and the stability and faithfulness of feature attributions. Results show that tree ensembles outperform neural and linear models while yielding more stable feature rankings, though models with similar accuracy can still exhibit substantial disagreement on feature importance."
resource: "https://arxiv.org/abs/2611.15716"
tags:
  - "machine-learning"
  - "interpretable-machine-learning"
timestamp: "2026-11-20T13:48:41Z"

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
  - name: "conditional-replacement-faithfulness-testing"
    description: "Develop and evaluate advanced feature replacement strategies, such as conditional replacement and counterfactual perturbation methods, to measure explanation faithfulness without generating unrealistic feature combinations or violating underlying feature dependencies."
skill: "GeneralMLSkill"
processed_at: "2026-11-20T13:48:41Z"
created_at: "2026-11-20T13:48:41Z"
---

# A Reliability Study of Explainable AI for Freight Mode Classification

**Authors**: Ali Alawi Balfaqih, Mansur Arief
**Date**: 2026-11-11
**Paper ID**: [openalex:2611.15716](https://arxiv.org/abs/2611.15716)

## Summary

This study investigates the reliability of explainable AI methods (SHAP and LIME) for freight mode classification using the PEPFAR supply chain dataset. The authors compare multiple machine learning architectures across 100 random replications, evaluating both predictive accuracy and the stability and faithfulness of feature attributions. Results show that tree ensembles outperform neural and linear models while yielding more stable feature rankings, though models with similar accuracy can still exhibit substantial disagreement on feature importance.

## Key Contributions

- Evaluated explainable machine learning methods (SHAP and LIME) for freight mode classification using 5,964 shipment records across 100 random replications.
- Demonstrated that tree ensembles significantly outperform neural and linear models, achieving 86.8% mean testing accuracy and higher feature ranking stability.
- Showed via feature-deletion tests that removing the top five SHAP- or LIME-ranked features alters predicted probabilities roughly four times more than removing random features.
- Revealed that models with similar predictive accuracy can exhibit substantial disagreement on feature importance, highlighting the necessity of assessing explanation reliability before operational deployment.

## Limitations

Models with similar accuracy disagree substantially on feature importance, and explanation stability and faithfulness must be explicitly assessed to avoid untrustworthy transport decisions.

## Open Questions & Future Work

- [[conditional-replacement-faithfulness-testing]]

## Archivist Review

The paper presents an empirical reliability study of explainability methods in freight transportation. The concepts and datasets are domain-specific or application-level evaluations without broader reusable ML architecture innovations. One open question on conditional replacement in faithfulness testing was retained because it targets a genuine methodological limitation in feature deletion and perturbation tests.

### Approved Open Questions
- Conditional Replacement for Faithfulness: Essential for ensuring that faithfulness benchmarks and feature-deletion tests reflect realistic data distributions rather than out-of-distribution artifacts.

### Rejected Candidates
- [open_question] Generalizing Freight XAI Reliability (`commercial-freight-xai-generalization`) - low_impact: Routine call for broader dataset evaluation across different commercial domains and cargo types.

## Links

- [Abstract](https://arxiv.org/abs/2611.15716)
- [PDF](https://arxiv.org/pdf/2611.15716)

