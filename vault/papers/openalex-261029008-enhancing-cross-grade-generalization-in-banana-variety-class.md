---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation"
description: "This paper addresses the challenge of cross-grade banana variety classification under domain shift caused by varying quality grades, maturity, and post-harvest conditions. The authors propose a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation to align probabilistic feature representations across both CNN and Transformer streams. Evaluated on a large-scale dataset of 31,678 images using a Leave-One-Grade-Out protocol, the proposed approach achieves a mean accuracy of 81.25%, outperforming individual baseline models."
resource: "https://arxiv.org/abs/2610.29008"
tags:
  - "object-detection"
timestamp: "2026-11-03T12:38:10Z"

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
processed_at: "2026-11-03T12:38:10Z"
created_at: "2026-11-03T12:38:10Z"
---

# Enhancing Cross-Grade Generalization in Banana Variety Classification via Hybrid CNN-Transformers and Knowledge Self-Distillation

**Authors**: Khush Kataruka, Mohammad Muzammila, Zahid Akhtar, Raghavendra Ramachandra, Praveen Kumar Chandaliya
**Date**: 2026-10-21
**Paper ID**: [openalex:2610.29008](https://arxiv.org/abs/2610.29008)

## Summary

This paper addresses the challenge of cross-grade banana variety classification under domain shift caused by varying quality grades, maturity, and post-harvest conditions. The authors propose a dual-stream Swin ResNet hybrid framework enhanced with KL-divergence-based self-distillation to align probabilistic feature representations across both CNN and Transformer streams. Evaluated on a large-scale dataset of 31,678 images using a Leave-One-Grade-Out protocol, the proposed approach achieves a mean accuracy of 81.25%, outperforming individual baseline models.

## Key Contributions

- Proposes a dual-stream Swin ResNet hybrid framework with KL-divergence-based self-distillation for cross-grade banana variety classification.
- Evaluates models under a rigorous Leave-One-Grade-Out protocol using a large-scale dataset of 31,678 banana images spanning three varieties and three quality grades.
- Demonstrates that the proposed hybrid framework achieves a mean accuracy of 81.25%, outperforming individual CNN and Transformer baseline models.

## Archivist Review

Applied strict selectivity standards to avoid approving paper-local agricultural application extensions, routine future work suggestions, or non-reusable domain-specific model combinations. No candidates met the stringent threshold for standalone vault inclusion.

### Rejected Candidates
- [open_question] Cross-Grade Agricultural Generalization and Deployment (`cross-grade-agricultural-generalization-and-lightweight-deployment`) - not_novel: Standard future work request calling for broader datasets, lightweight deployment, and domain generalization extensions without defining an explicit unresolved technical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.29008)
- [PDF](https://arxiv.org/pdf/2610.29008)

