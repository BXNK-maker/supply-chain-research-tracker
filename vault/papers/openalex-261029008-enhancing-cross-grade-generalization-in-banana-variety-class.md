---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation"
description: "This paper addresses cross-grade generalization in automated fruit classification, focusing on banana variety grading under domain shifts caused by maturity and quality variations. The authors propose a dual-stream Swin ResNet hybrid architecture integrated with KL-divergence-based self-distillation to align probabilistic features across streams. Evaluated on a Leave-One-Grade-Out protocol across 31,678 images, the proposed framework achieves a mean accuracy of 81.25%, outperforming individual CNN and Transformer baselines."
resource: "https://arxiv.org/abs/2610.29008"
tags:
  - "object-detection"
timestamp: "2026-10-30T11:09:49Z"

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
processed_at: "2026-10-30T11:09:49Z"
created_at: "2026-10-30T11:09:49Z"
---

# Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation

**Authors**: Khush Kataruka, Mohammad Muzammila, Zahid Akhtar, Raghavendra Ramachandra, Praveen Kumar Chandaliya
**Date**: 2026-10-21
**Paper ID**: [openalex:2610.29008](https://arxiv.org/abs/2610.29008)

## Summary

This paper addresses cross-grade generalization in automated fruit classification, focusing on banana variety grading under domain shifts caused by maturity and quality variations. The authors propose a dual-stream Swin ResNet hybrid architecture integrated with KL-divergence-based self-distillation to align probabilistic features across streams. Evaluated on a Leave-One-Grade-Out protocol across 31,678 images, the proposed framework achieves a mean accuracy of 81.25%, outperforming individual CNN and Transformer baselines.

## Key Contributions

- Proposes a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation for cross-grade banana variety classification.
- Evaluates models under a rigorous Leave-One-Grade-Out protocol using a large-scale dataset of 31,678 banana images spanning three varieties and three quality grades.
- Demonstrates that the hybrid framework attains a mean accuracy of 81.25%, significantly surpassing single-paradigm CNN and Transformer baselines in cross-grade generalization.

## Archivist Review

Applied strict review standards, rejecting the generic future work question about domain generalization and data augmentation since it does not target a specific permanent foundational bottleneck. No new concepts or datasets were proposed or approved.

### Rejected Candidates
- [open_question] Domain Generalization for Extreme Agricultural Variability (`domain-generalization-extreme-variability`) - not_reusable: This is a standard future work suggestion about applying domain generalization and data augmentation, lacking a specific unresolved architectural bottleneck or mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2610.29008)
- [PDF](https://arxiv.org/pdf/2610.29008)

