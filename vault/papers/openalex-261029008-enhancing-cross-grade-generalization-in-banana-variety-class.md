---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation"
description: "Automated fruit classification often suffers from domain shift when models trained on specific quality grades must generalize to unseen grades. To tackle this, the authors propose a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation to align probabilistic features across the CNN and Transformer streams. Evaluated on a large-scale dataset of 31,678 banana images under a Leave-One-Grade-Out protocol, the proposed approach achieves a mean accuracy of 81.25%, outperforming standard CNN and Transformer baselines."
resource: "https://arxiv.org/abs/2610.29008"
tags:
  - "object-detection"
timestamp: "2026-10-31T10:43:05Z"

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
processed_at: "2026-10-31T10:43:05Z"
created_at: "2026-10-31T10:43:05Z"
---

# Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation

**Authors**: Khush Kataruka, Mohammad Muzammila, Zahid Akhtar, Raghavendra Ramachandra, Praveen Kumar Chandaliya
**Date**: 2026-10-21
**Paper ID**: [openalex:2610.29008](https://arxiv.org/abs/2610.29008)

## Summary

Automated fruit classification often suffers from domain shift when models trained on specific quality grades must generalize to unseen grades. To tackle this, the authors propose a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation to align probabilistic features across the CNN and Transformer streams. Evaluated on a large-scale dataset of 31,678 banana images under a Leave-One-Grade-Out protocol, the proposed approach achieves a mean accuracy of 81.25%, outperforming standard CNN and Transformer baselines.

## Key Contributions

- Proposes a dual-stream Swin ResNet hybrid framework with KL-divergence-based self-distillation for cross-grade banana variety classification.
- Evaluates the framework under a rigorous Leave-One-Grade-Out protocol using a large-scale dataset of 31,678 banana images.
- Achieves a mean accuracy of 81.25%, outperforming individual CNN and Transformer baseline models in cross-grade generalization.

## Archivist Review

The proposed open questions were rejected as standard boilerplate future work requests (domain generalization and edge deployment) typical of empirical vision papers, and no distinct reusable concepts or named datasets were provided.

### Rejected Candidates
- [open_question] Domain Generalization under Extreme Variability (`domain-generalization-extreme-variability`) - other: Standard future work suggestion regarding domain generalization and data augmentation without a specific unresolved technical mechanism.
- [open_question] Lightweight Hybrid Edge Deployment (`lightweight-hybrid-edge-deployment`) - other: Standard boilerplate call for lightweight model variants for edge deployment.

## Links

- [Abstract](https://arxiv.org/abs/2610.29008)
- [PDF](https://arxiv.org/pdf/2610.29008)

