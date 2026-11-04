---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation"
description: "This paper investigates cross-grade banana variety classification under domain shift caused by variations in quality grades, proposing a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation. Evaluated under a rigorous Leave-One-Grade-Out protocol on a large-scale dataset of 31,678 images, the proposed approach achieves a mean accuracy of 81.25% and outperforms conventional CNN and Transformer baselines. The results show that probabilistic feature alignment across the dual streams improves discriminative feature transferability and attention localization for unseen grades."
resource: "https://arxiv.org/abs/2610.29008"
tags:
  - "object-detection"
timestamp: "2026-11-04T12:47:23Z"

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
processed_at: "2026-11-04T12:47:23Z"
created_at: "2026-11-04T12:47:23Z"
---

# Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation

**Authors**: Khush Kataruka, Mohammad Muzammila, Zahid Akhtar, Raghavendra Ramachandra, Praveen Kumar Chandaliya
**Date**: 2026-10-21
**Paper ID**: [openalex:2610.29008](https://arxiv.org/abs/2610.29008)

## Summary

This paper investigates cross-grade banana variety classification under domain shift caused by variations in quality grades, proposing a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation. Evaluated under a rigorous Leave-One-Grade-Out protocol on a large-scale dataset of 31,678 images, the proposed approach achieves a mean accuracy of 81.25% and outperforms conventional CNN and Transformer baselines. The results show that probabilistic feature alignment across the dual streams improves discriminative feature transferability and attention localization for unseen grades.

## Key Contributions

- Proposed a dual-stream Swin ResNet hybrid framework combined with KL-divergence-based self-distillation for cross-grade banana variety classification.
- Evaluated the framework under a rigorous Leave-One-Grade-Out protocol using a large-scale dataset of 31,678 banana images across three varieties and three quality grades.
- Demonstrated that the hybrid framework attains a mean accuracy of 81.25%, outperforming individual CNN and Transformer baseline models by improving feature transferability and attention localization.

## Archivist Review

Applied strict scarcity and reusability standards. No concepts or open questions met the high bar for permanent vault notes, as the work is an application of existing hybrid architectures and self-distillation to a specific agricultural domain.

### Rejected Candidates
- [open_question] Cross-Grade Agricultural Domain Generalization (`cross-grade-domain-generalization-agriculture`) - not_novel: The question describes routine future work proposing standard exploration of data augmentation and lightweight variants rather than a deep unresolved algorithmic bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.29008)
- [PDF](https://arxiv.org/pdf/2610.29008)

