---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation"
description: "This paper addresses cross-grade banana variety classification under severe domain shifts by introducing a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation. Evaluated on a large-scale dataset of 31,678 images across three varieties and three quality grades using a Leave-One-Grade-Out protocol, the proposed model achieves a mean accuracy of 81.25%. Qualitative analysis demonstrates that the hybrid approach improves feature transferability, attention localization, and optimization stability compared to pure CNN or Transformer baselines."
resource: "https://arxiv.org/abs/2610.29008"
tags:
  - "machine-learning"
timestamp: "2026-11-02T13:06:49Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Khush Kataruka"
  - literal: "Mohammad Muzammila"
  - literal: "Zahid Akhtar"
  - literal: "Raghavendra Ramachandra"
  - literal: "Praveen Kumar Chandaliya"
issued:
  date-parts:
    - [2026, 10, 21]

# Domain-specific custom fields
paper_id: "2610.29008"
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
processed_at: "2026-11-02T13:06:49Z"
created_at: "2026-11-02T13:06:49Z"
---

# Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation

**Authors**: Khush Kataruka, Mohammad Muzammila, Zahid Akhtar, Raghavendra Ramachandra, Praveen Kumar Chandaliya
**Date**: 2026-10-21
**Paper ID**: [openalex:2610.29008](https://arxiv.org/abs/2610.29008)

## Summary

This paper addresses cross-grade banana variety classification under severe domain shifts by introducing a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation. Evaluated on a large-scale dataset of 31,678 images across three varieties and three quality grades using a Leave-One-Grade-Out protocol, the proposed model achieves a mean accuracy of 81.25%. Qualitative analysis demonstrates that the hybrid approach improves feature transferability, attention localization, and optimization stability compared to pure CNN or Transformer baselines.

## Key Contributions

- Evaluated cross-grade banana variety classification under a rigorous Leave-One-Grade-Out evaluation protocol on a dataset of 31,678 images.
- Proposed a dual-stream Swin ResNet hybrid framework combined with KL-divergence-based self-distillation to align probabilistic feature representations between CNN and Transformer streams.
- Achieved a mean accuracy of 81.25%, outperforming individual CNN and Transformer baseline models under domain shift conditions.

## Archivist Review

The paper applies standard hybrid architectures (Swin ResNet) and self-distillation to agricultural grading, which does not introduce novel vault-worthy concepts or datasets. The proposed open questions are standard future work suggestions (edge deployment, more datasets, domain generalization) rather than deep structural research bottlenecks.

### Rejected Candidates
- [open_question] Domain Generalization for Extreme Variability (`domain-generalization-extreme-variability`) - low_impact: Routine request to test domain generalization techniques under variability, lacking a specific architectural or theoretical bottleneck.
- [open_question] Lightweight Hybrid Edge Deployment (`lightweight-hybrid-edge-deployment`) - low_impact: Standard engineering future work regarding model compression and edge device deployment.
- [open_question] Multi-Fruit and Regional Generalization (`multi-fruit-regional-generalization`) - low_impact: Routine call to evaluate existing frameworks on additional dataset varieties or regions.

## Links

- [Abstract](https://arxiv.org/abs/2610.29008)
- [PDF](https://arxiv.org/pdf/2610.29008)

