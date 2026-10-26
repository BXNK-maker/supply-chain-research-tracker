---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation"
description: "This paper addresses the challenge of cross-grade banana variety classification under significant domain shift, where models must generalize to unseen fruit quality grades. The authors propose a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation to align probabilistic features between CNN and Transformer streams. Evaluated under a Leave-One-Grade-Out protocol on 31,678 banana images, the proposed framework achieves a mean accuracy of 81.25%, outperforming baseline models."
resource: "https://arxiv.org/abs/2610.29008"
tags:
  - "object-detection"
timestamp: "2026-10-26T10:42:44Z"

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
processed_at: "2026-10-26T10:42:44Z"
created_at: "2026-10-26T10:42:44Z"
---

# Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation

**Authors**: Khush Kataruka, Mohammad Muzammila, Zahid Akhtar, Raghavendra Ramachandra, Praveen Kumar Chandaliya
**Date**: 2026-10-21
**Paper ID**: [openalex:2610.29008](https://arxiv.org/abs/2610.29008)

## Summary

This paper addresses the challenge of cross-grade banana variety classification under significant domain shift, where models must generalize to unseen fruit quality grades. The authors propose a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation to align probabilistic features between CNN and Transformer streams. Evaluated under a Leave-One-Grade-Out protocol on 31,678 banana images, the proposed framework achieves a mean accuracy of 81.25%, outperforming baseline models.

## Key Contributions

- Presents a dual-stream Swin ResNet hybrid framework with KL-divergence-based self-distillation for cross-grade banana variety classification.
- Evaluates models under a rigorous Leave-One-Grade-Out protocol using a dataset of 31,678 banana images across three varieties and three quality grades.
- Achieves a mean accuracy of 81.25%, outperforming individual CNN and Transformer baseline models.

## Limitations

Evaluated specifically on banana varieties and quality grades; broader generalizability to other fruits and crops remains to be explored.

## Archivist Review

Applied strict criteria for vault admission, rejecting domain-specific open questions regarding banana grading and edge deployment as they lack broad cross-domain machine learning reusability. No concepts or datasets were proposed or approved.

### Rejected Candidates
- [open_question] Cross-Grade Domain Generalization Robustness (`cross-grade-domain-generalization-robustness`) - low_impact: Too domain-specific to fruit grading and quality shifts to warrant a permanent vault note.
- [open_question] Lightweight Hybrid Models for Edge Deployment (`lightweight-hybrid-models-edge-deployment`) - not_reusable: Standard boilerplate future work on efficiency and edge deployment without a unique theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.29008)
- [PDF](https://arxiv.org/pdf/2610.29008)

