---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation"
description: "This paper investigates cross-grade banana variety classification under severe domain shifts caused by varying fruit quality grades, maturity, and post-harvest conditions. To address the limitations of single-paradigm architectures, the authors propose a dual-stream Swin ResNet hybrid framework combined with KL-divergence-based self-distillation to align probabilistic feature representations between the CNN and Transformer streams. Evaluated using a rigorous Leave-One-Grade-Out protocol on a large-scale dataset of 31,678 banana images, the proposed framework achieves an improved mean accuracy of 81.25% over baseline models. Qualitative evaluations further reveal that the method enhances discriminative feature transferability, attention localization, and optimization stability."
resource: "https://arxiv.org/abs/2610.29008"
tags:
  - "object-detection"
timestamp: "2026-10-25T09:32:38Z"

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
processed_at: "2026-10-25T09:32:38Z"
created_at: "2026-10-25T09:32:38Z"
---

# Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation

**Authors**: Khush Kataruka, Mohammad Muzammila, Zahid Akhtar, Raghavendra Ramachandra, Praveen Kumar Chandaliya
**Date**: 2026-10-21
**Paper ID**: [openalex:2610.29008](https://arxiv.org/abs/2610.29008)

## Summary

This paper investigates cross-grade banana variety classification under severe domain shifts caused by varying fruit quality grades, maturity, and post-harvest conditions. To address the limitations of single-paradigm architectures, the authors propose a dual-stream Swin ResNet hybrid framework combined with KL-divergence-based self-distillation to align probabilistic feature representations between the CNN and Transformer streams. Evaluated using a rigorous Leave-One-Grade-Out protocol on a large-scale dataset of 31,678 banana images, the proposed framework achieves an improved mean accuracy of 81.25% over baseline models. Qualitative evaluations further reveal that the method enhances discriminative feature transferability, attention localization, and optimization stability.

## Key Contributions

- Proposes a dual-stream Swin ResNet hybrid framework with KL-divergence-based self-distillation for cross-grade banana variety classification.
- Establishes a rigorous Leave-One-Grade-Out evaluation protocol on a large-scale dataset of 31,678 banana images spanning three varieties and three quality grades.
- Achieves a mean accuracy of 81.25%, outperforming individual CNN and Transformer baseline models under severe domain shifts across quality grades.
- Demonstrates through qualitative analysis that hybrid feature alignment improves discriminative feature transferability, attention localization, and optimization stability.

## Archivist Review

The paper applies standard dual-stream CNN-Transformer hybrid architectures and self-distillation to a domain-specific agricultural classification task. The proposed methods and open questions are domain-specific applications rather than novel vault-worthy concepts or fundamental research problems.

### Rejected Candidates
- [open_question] Domain Generalization for Extreme Variability (`domain-generalization-extreme-variability`) - low_impact: Standard future work proposal suggesting broader domain generalization experiments, lacking a specific unresolved algorithmic bottleneck.
- [open_question] Lightweight Hybrids for Edge Deployment (`lightweight-hybrids-edge-deployment`) - low_impact: Standard hardware efficiency future work direction without a standalone theoretical formulation.
- [open_question] Multi-Fruit and Region Generalization (`multi-fruit-region-generalization`) - low_impact: Routine application scaling suggestion rather than a fundamental conceptual bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.29008)
- [PDF](https://arxiv.org/pdf/2610.29008)

