---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Vehicle Routing Problem"
description: "This paper investigates the cross-scale generalization degradation of attention-based Pointer Networks trained with reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify three key failure factors—node density shifts, attention dispersion, and graph context dilution—and evaluate various architectural modifications including entropy-based attention scaling and permutation-invariant graph-context aggregation. Leveraging the complementarity of these approaches, they propose an approach selector that chooses the best model per size pair, achieving up to 3.2% cost reduction across seen and unseen problem sizes."
resource: "https://arxiv.org/abs/2610.27936"
tags:
  - "reinforcement-learning"
  - "vehicle-routing-problem"
timestamp: "2026-11-01T11:36:38Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Sofiene Lassoued"
  - literal: "Devara Tertia"
  - literal: "Stefan Lier"
  - literal: "Andreas Schwung"
issued:
  date-parts:
    - [2026, 10, 20]

# Domain-specific custom fields
paper_id: "2610.27936"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "approach-selector-for-cross-scale-generalization"
    description: "An approach selector that chooses the best model for each training-target size pair to enhance cross-scale generalization."
datasets:
  []
open_questions:
  - name: "unified-multiscale-neural-routing-model"
    description: "Investigating the integration of attention rescaling mechanisms with learned graph-context aggregation methods into a single unified model trained simultaneously across multiple scales remains an important direction for future work."
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:36:38Z"
created_at: "2026-11-01T11:36:38Z"
---

# From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Vehicle Routing Problem

**Authors**: Sofiene Lassoued, Devara Tertia, Stefan Lier, Andreas Schwung
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27936](https://arxiv.org/abs/2610.27936)

## Summary

This paper investigates the cross-scale generalization degradation of attention-based Pointer Networks trained with reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify three key failure factors—node density shifts, attention dispersion, and graph context dilution—and evaluate various architectural modifications including entropy-based attention scaling and permutation-invariant graph-context aggregation. Leveraging the complementarity of these approaches, they propose an approach selector that chooses the best model per size pair, achieving up to 3.2% cost reduction across seen and unseen problem sizes.

## Key Contributions

- Identified three contributing factors to cross-scale generalization degradation in pointer networks for CVRP: shifts in node density, attention dispersion, and dilution of the mean-pooled graph context.
- Proposed a learned, permutation-invariant graph-context aggregation mechanism (weighted average and Set2Set) and entropy-based attention scaling.
- Introduced an approach selector that chooses the best model for each training-target size pair, reducing cost by up to 3.2% across seen and unseen sizes.

## Limitations

Evaluated specifically on the Capacitated Vehicle Routing Problem (CVRP) as a controlled proxy.

## Open Questions & Future Work

- [[unified-multiscale-neural-routing-model]]

## Key Concepts

- [[approach-selector-for-cross-scale-generalization]]: An approach selector that chooses the best model for each training-target size pair to enhance cross-scale generalization.

## Archivist Review

Approved the approach selector as a distinct methodological concept and the unified multi-scale neural routing question as a valuable open research direction. Rejected Set2Set context aggregation as it relies on an established pooling architecture rather than a new standalone concept.

### Approved Concepts
- Approach Selector for Cross-Scale Generalization: Combines complementary cross-scale generalization strategies to consistently improve vehicle routing solutions across varying problem sizes.

### Approved Open Questions
- Unified Multi-Scale Neural Routing: Combining complementary downscaling and upscaling levers into a single multi-scale trained model addresses the fundamental cross-size generalization bottleneck in neural combinatorial optimization.

### Rejected Candidates
- [concept] Set2Set Context Aggregation (`set2set-context-aggregation`) - not_novel: Set2Set is an existing established mechanism applied here rather than a novel conceptual contribution of this paper.

## Links

- [Abstract](https://arxiv.org/abs/2610.27936)
- [PDF](https://arxiv.org/pdf/2610.27936)

