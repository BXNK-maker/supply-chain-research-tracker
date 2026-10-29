---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation"
description: "This paper addresses the problem of cross-grade banana variety classification, where models trained on specific quality grades must generalize to unseen grades under significant domain shift. To overcome the limitations of single-paradigm architectures, the authors propose a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation to align feature representations. Evaluated under a Leave-One-Grade-Out protocol on a dataset of 31,678 banana images, the proposed approach achieves a mean accuracy of 81.25%, outperforming standard CNN and Vision Transformer baselines."
resource: "https://arxiv.org/abs/2610.29008"
tags:
  - "object-detection"
  - "time-series"
timestamp: "2026-10-29T11:15:46Z"

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
processed_at: "2026-10-29T11:15:46Z"
created_at: "2026-10-29T11:15:46Z"
---

# Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation

**Authors**: Khush Kataruka, Mohammad Muzammila, Zahid Akhtar, Raghavendra Ramachandra, Praveen Kumar Chandaliya
**Date**: 2026-10-21
**Paper ID**: [openalex:2610.29008](https://arxiv.org/abs/2610.29008)

## Summary

This paper addresses the problem of cross-grade banana variety classification, where models trained on specific quality grades must generalize to unseen grades under significant domain shift. To overcome the limitations of single-paradigm architectures, the authors propose a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation to align feature representations. Evaluated under a Leave-One-Grade-Out protocol on a dataset of 31,678 banana images, the proposed approach achieves a mean accuracy of 81.25%, outperforming standard CNN and Vision Transformer baselines.

## Key Contributions

- A dual-stream Swin ResNet hybrid framework with KL-divergence-based self-distillation is proposed to address cross-grade banana variety classification under domain shift.
- Evaluation under a rigorous Leave-One-Grade-Out protocol using a large-scale dataset of 31,678 banana images across three varieties and three quality grades.
- The proposed framework achieves a mean accuracy of 81.25%, outperforming individual CNN and Transformer baseline models in cross-grade generalization.
- Qualitative analysis demonstrates that the hybrid framework improves discriminative feature transferability, attention localization, and optimization stability.

## Archivist Review

The proposed open question is a routine request to apply standard domain generalization techniques to a specific agricultural setting rather than a major unresolved conceptual bottleneck. No concepts or datasets met the strict vault inclusion criteria.

### Rejected Candidates
- [open_question] Cross-Grade Agricultural Domain Generalization (`cross-grade-agricultural-domain-generalization`) - not_novel: Routine future work request for exploring standard domain generalization and data augmentation schemes in a specific application domain.

## Links

- [Abstract](https://arxiv.org/abs/2610.29008)
- [PDF](https://arxiv.org/pdf/2610.29008)

