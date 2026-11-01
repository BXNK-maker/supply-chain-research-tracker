---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation"
description: "This paper investigates cross-grade banana variety classification under domain shift caused by varying quality grades, proposing a dual-stream Swin ResNet hybrid framework combined with KL-divergence-based self-distillation. Evaluated on a large-scale dataset of 31,678 banana images under a Leave-One-Grade-Out protocol, the proposed model achieves a mean accuracy of 81.25%, outperforming single-paradigm CNN and Transformer baselines. The approach successfully aligns probabilistic feature representations between the two streams, enhancing feature transferability and attention localization for precision agriculture applications."
resource: "https://arxiv.org/abs/2610.29008"
tags:
  - "object-detection"
  - "machine-learning"
timestamp: "2026-11-01T11:39:10Z"

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
processed_at: "2026-11-01T11:39:10Z"
created_at: "2026-11-01T11:39:10Z"
---

# Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation

**Authors**: Khush Kataruka, Mohammad Muzammila, Zahid Akhtar, Raghavendra Ramachandra, Praveen Kumar Chandaliya
**Date**: 2026-10-21
**Paper ID**: [openalex:2610.29008](https://arxiv.org/abs/2610.29008)

## Summary

This paper investigates cross-grade banana variety classification under domain shift caused by varying quality grades, proposing a dual-stream Swin ResNet hybrid framework combined with KL-divergence-based self-distillation. Evaluated on a large-scale dataset of 31,678 banana images under a Leave-One-Grade-Out protocol, the proposed model achieves a mean accuracy of 81.25%, outperforming single-paradigm CNN and Transformer baselines. The approach successfully aligns probabilistic feature representations between the two streams, enhancing feature transferability and attention localization for precision agriculture applications.

## Key Contributions

- Introduces a dual-stream Swin ResNet hybrid framework with KL-divergence-based self-distillation for cross-grade banana variety classification.
- Evaluates the framework under a rigorous Leave-One-Grade-Out protocol using a large-scale dataset of 31,678 banana images.
- Achieves a mean accuracy of 81.25%, outperforming individual CNN and Transformer baseline models under domain shift across unseen quality grades.
- Demonstrates through qualitative analysis that self-distillation improves discriminative feature transferability and attention localization across streams.

## Archivist Review

Applied strict screening criteria, rejecting the proposed open question as a broad compilation of standard future work items (lightweight deployment and dataset extensions) rather than a specific unresolved bottleneck. No concepts or datasets met the high bar for permanent standalone vault notes.

### Rejected Candidates
- [open_question] Generalization and Lightweight Deployment in Agriculture (`cross-grade-generalization-lightweight-deployment-multifruit`) - low_impact: The question bundles multiple standard future work directions (lightweight deployment, data augmentation, multi-fruit extension) without pointing to a single precise, foundational unresolved mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2610.29008)
- [PDF](https://arxiv.org/pdf/2610.29008)

