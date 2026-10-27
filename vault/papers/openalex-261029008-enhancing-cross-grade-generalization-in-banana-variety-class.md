---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation"
description: "This paper investigates cross-grade banana variety classification under significant domain shift caused by variations in quality grades, maturity, and illumination. To tackle the limitations of single-paradigm models, the authors propose a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation to align probabilistic feature representations across both streams. Evaluated under a rigorous Leave-One-Grade-Out protocol on a large-scale dataset of 31,678 banana images, the proposed framework achieves superior cross-grade generalization with a mean accuracy of 81.25%. Qualitative analysis confirms that the hybrid approach improves discriminative feature transferability, attention localization, and optimization stability."
resource: "https://arxiv.org/abs/2610.29008"
tags:
  - "object-detection"
  - "time-series"
timestamp: "2026-10-27T10:10:38Z"

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
processed_at: "2026-10-27T10:10:38Z"
created_at: "2026-10-27T10:10:38Z"
---

# Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation

**Authors**: Khush Kataruka, Mohammad Muzammila, Zahid Akhtar, Raghavendra Ramachandra, Praveen Kumar Chandaliya
**Date**: 2026-10-21
**Paper ID**: [openalex:2610.29008](https://arxiv.org/abs/2610.29008)

## Summary

This paper investigates cross-grade banana variety classification under significant domain shift caused by variations in quality grades, maturity, and illumination. To tackle the limitations of single-paradigm models, the authors propose a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation to align probabilistic feature representations across both streams. Evaluated under a rigorous Leave-One-Grade-Out protocol on a large-scale dataset of 31,678 banana images, the proposed framework achieves superior cross-grade generalization with a mean accuracy of 81.25%. Qualitative analysis confirms that the hybrid approach improves discriminative feature transferability, attention localization, and optimization stability.

## Key Contributions

- Introduces a dual-stream Swin ResNet hybrid framework combined with KL-divergence-based self-distillation for cross-grade banana variety classification under domain shift.
- Evaluates models under a rigorous Leave-One-Grade-Out protocol across a large-scale dataset of 31,678 banana images covering three varieties and three quality grades.
- Demonstrates that the hybrid self-distillation approach attains a mean accuracy of 81.25%, outperforming individual CNN and Transformer baseline models.

## Archivist Review

Applied rigorous vault standards: rejected the open question because it merely suggests standard future work directions such as data augmentation and lightweight variants without identifying a distinct fundamental bottleneck. No concepts or datasets met the strict criteria for standalone permanence.

### Rejected Candidates
- [open_question] Cross-Grade Agricultural Domain Generalization (`cross-grade-agricultural-domain-generalization`) - low_impact: The proposed open question asks for standard extensions like data augmentation, lightweight variants, and multi-fruit datasets rather than isolating a specific unresolved theoretical or algorithmic bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.29008)
- [PDF](https://arxiv.org/pdf/2610.29008)

