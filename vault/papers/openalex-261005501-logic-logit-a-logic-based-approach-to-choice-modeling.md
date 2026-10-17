---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Logic-Logit: A Logic-Based Approach to Choice Modeling"
description: "The paper introduces Logic-Logit, a novel rule-based interpretable choice model designed to learn and explain human choices by mimicking heuristic consider-then-choose decision processes. By combining column generation and the Frank-Wolfe algorithm, the model efficiently extracts disjunction-of-conjunction logic rules to overcome the NP-hard nature of rule extraction. Empirical evaluations on synthetic, commercial, and healthcare datasets demonstrate that Logic-Logit achieves superior accuracy and interpretability compared to baseline models."
resource: "https://arxiv.org/abs/2610.05501"
tags:
  - "choice-modeling"
  - "interpretable-machine-learning"
timestamp: "2026-10-17T08:59:07Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Shuhan Zhang"
  - literal: "Wendi Ren"
  - literal: "Shuang Li"
issued:
  date-parts:
    - [2026, 10, 4]

# Domain-specific custom fields
paper_id: "2610.05501"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "logic-logit"
    description: "A rule-based interpretable choice model that leverages logic rules (OR-of-ANDs) to learn and explain human decision processes."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-17T08:59:07Z"
created_at: "2026-10-17T08:59:07Z"
---

# Logic-Logit: A Logic-Based Approach to Choice Modeling

**Authors**: Shuhan Zhang, Wendi Ren, Shuang Li
**Date**: 2026-10-04
**Paper ID**: [openalex:2610.05501](https://arxiv.org/abs/2610.05501)

## Summary

The paper introduces Logic-Logit, a novel rule-based interpretable choice model designed to learn and explain human choices by mimicking heuristic consider-then-choose decision processes. By combining column generation and the Frank-Wolfe algorithm, the model efficiently extracts disjunction-of-conjunction logic rules to overcome the NP-hard nature of rule extraction. Empirical evaluations on synthetic, commercial, and healthcare datasets demonstrate that Logic-Logit achieves superior accuracy and interpretability compared to baseline models.

## Key Contributions

- Introduces Logic-Logit, a novel rule-based interpretable choice model that mimics human consider-then-choose heuristic decision processes.
- Combines column generation techniques and the Frank-Wolfe algorithm to efficiently extract NP-hard logic rules for preference modeling.
- Demonstrates through empirical evaluation on synthetic, commercial, and healthcare datasets that Logic-Logit outperforms baseline models in both interpretability and accuracy.

## Limitations

The paper mentions that rule extraction for preference modeling is NP-hard, which may present scalability challenges for extremely large feature spaces, though mitigated by the proposed optimization techniques.

## Key Concepts

- [[logic-logit]]: A rule-based interpretable choice model that leverages logic rules (OR-of-ANDs) to learn and explain human decision processes.

## Archivist Review

Approved the central model concept (Logic-Logit) while correctly rejecting standard optimization algorithms that serve as internal implementation details. No standalone datasets or open questions met the rigorous inclusion standards.

### Approved Concepts
- Logic-Logit: Logic-Logit is the core model introduced in the paper, combining logic rules with logit choice modeling to achieve high interpretability and accuracy.

### Rejected Candidates
- [concept] Column Generation (`column-generation`) - not_novel: Column generation is a well-established optimization technique rather than a novel concept introduced by the paper.
- [concept] Frank-Wolfe Algorithm (`frank-wolfe-algorithm`) - not_novel: The Frank-Wolfe algorithm is a standard optimization method, not a novel contribution of this work.

## Links

- [Abstract](https://arxiv.org/abs/2610.05501)
- [PDF](https://arxiv.org/pdf/2610.05501)

