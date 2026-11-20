---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Learning Advantage Function Surrogates via Convex Conjugate Matching"
description: "Pure policy-learning algorithms typically yield optimal per-unit decisions without estimating the cost of deviating from them, which is critical for downstream trade-offs and capacity constraints. This paper proposes a method to train an advantage function surrogate using price perturbations driven by a Fenchel-Young loss. The authors describe a two-stage training recipe—fitting the policy first and then the cost model—and demonstrate its utility on a multi-period inventory management problem."
resource: "https://arxiv.org/abs/2611.20199"
tags:
  - "machine-learning"
  - "reinforcement-learning"
timestamp: "2026-11-20T13:47:55Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Alvaro Maggiar"
issued:
  date-parts:
    - [2026, 11, 15]

# Domain-specific custom fields
paper_id: "2611.20199"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "fenchel-young-loss"
    description: "A loss function based on convex duality used here to match and train advantage function surrogates via price perturbations."
datasets:
  []
open_questions:
  - name: "richer-surrogate-families-non-closed-form-conjugates"
    description: "Investigate richer surrogate families, such as input convex neural networks or M^{\\\\natural}-convex functions, to enlarge the set of action-value functions the surrogate can match when closed-form conjugate gradients are unavailable."
skill: "GeneralMLSkill"
processed_at: "2026-11-20T13:47:55Z"
created_at: "2026-11-20T13:47:55Z"
---

# Learning Advantage Function Surrogates via Convex Conjugate Matching

**Authors**: Alvaro Maggiar
**Date**: 2026-11-15
**Paper ID**: [openalex:2611.20199](https://arxiv.org/abs/2611.20199)

## Summary

Pure policy-learning algorithms typically yield optimal per-unit decisions without estimating the cost of deviating from them, which is critical for downstream trade-offs and capacity constraints. This paper proposes a method to train an advantage function surrogate using price perturbations driven by a Fenchel-Young loss. The authors describe a two-stage training recipe—fitting the policy first and then the cost model—and demonstrate its utility on a multi-period inventory management problem.

## Key Contributions

- Proposes a method to train advantage function surrogates through price perturbations motivated by a Fenchel-Young loss.
- Describes a two-stage recipe consisting of first fitting the policy and then the cost model.
- Illustrates the approach on a multi-period inventory management problem.

## Open Questions & Future Work

- [[richer-surrogate-families-non-closed-form-conjugates]]

## Key Concepts

- [[fenchel-young-loss]]: A loss function based on convex duality used here to match and train advantage function surrogates via price perturbations.

## Archivist Review

Approved the Fenchel-Young loss concept for its utility in convex conjugate matching and mapped the open question on surrogate families to the existing vault entry while preserving its specific technical details.

### Approved Concepts
- Fenchel-Young Loss: Introduces a principled convex conjugate matching technique to train advantage function surrogates without standard critic architectures.

### Approved Open Questions
- Richer Surrogate Families: Extending surrogate learning to more expressive, non-quadratic function classes is crucial for handling complex, high-dimensional operational planning and combinatorial optimization problems without closed-form conjugates.

### Rejected Candidates
- [concept] Advantage Function Surrogate (`advantage-function-surrogate`) - not_novel: Advantage functions and surrogates are standard reinforcement learning and optimization concepts rather than a novel standalone ML architecture or technique introduced by this paper.

## Links

- [Abstract](https://arxiv.org/abs/2611.20199)
- [PDF](https://arxiv.org/pdf/2611.20199)

