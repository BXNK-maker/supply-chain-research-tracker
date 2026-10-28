---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation"
description: "This paper addresses cross-grade banana variety classification under significant domain shift by introducing a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation. Evaluated under a Leave-One-Grade-Out protocol on a dataset of 31,678 images, the proposed approach achieves a mean accuracy of 81.25%, outperforming standard CNN and Transformer baselines. Qualitative analysis demonstrates that the hybrid approach improves discriminative feature transferability, attention localization, and optimization stability."
resource: "https://arxiv.org/abs/2610.29008"
tags:
  - "object-detection"
  - "time-series"
timestamp: "2026-10-28T10:59:26Z"

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
processed_at: "2026-10-28T10:59:26Z"
created_at: "2026-10-28T10:59:26Z"
---

# Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation

**Authors**: Khush Kataruka, Mohammad Muzammila, Zahid Akhtar, Raghavendra Ramachandra, Praveen Kumar Chandaliya
**Date**: 2026-10-21
**Paper ID**: [openalex:2610.29008](https://arxiv.org/abs/2610.29008)

## Summary

This paper addresses cross-grade banana variety classification under significant domain shift by introducing a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation. Evaluated under a Leave-One-Grade-Out protocol on a dataset of 31,678 images, the proposed approach achieves a mean accuracy of 81.25%, outperforming standard CNN and Transformer baselines. Qualitative analysis demonstrates that the hybrid approach improves discriminative feature transferability, attention localization, and optimization stability.

## Key Contributions

- Presented a dual-stream Swin ResNet hybrid framework combined with KL-divergence-based self-distillation to enhance cross-grade banana variety classification.
- Evaluated under a rigorous Leave-One-Grade-Out protocol using a large-scale dataset of 31,678 banana images across three varieties and three quality grades.
- Achieved a mean accuracy of 81.25%, outperforming individual CNN and Vision Transformer baseline models in handling domain shift across unseen grades.

## Limitations

Evaluated specifically on banana varieties and quality grades; broader generalization across other fruit types remains to be explored.

## Archivist Review

Applied strict archival standards, rejecting the domain-specific future work open question as generic application extensions rather than a reusable methodological bottleneck. No concepts or datasets were proposed or approved.

### Rejected Candidates
- [open_question] Cross-Domain Agricultural Generalization Limits (`cross-domain-agricultural-generalization`) - generic: The open question describes standard broad future work (more data, diverse crops, lightweight variants) rather than a specific unresolved theoretical mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2610.29008)
- [PDF](https://arxiv.org/pdf/2610.29008)

