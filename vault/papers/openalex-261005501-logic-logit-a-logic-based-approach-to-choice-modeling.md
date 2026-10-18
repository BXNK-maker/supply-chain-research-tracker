---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Logic-Logit: A Logic-Based Approach to Choice Modeling"
description: "This paper proposes Logic-Logit, a rule-based interpretable choice model designed to mimic human heuristic decision processes represented as disjunctions of conjunctions. To overcome the NP-hard nature of rule extraction, the authors introduce an efficient optimization approach combining column generation and the Frank-Wolfe algorithm. Empirical evaluations on synthetic and real-world commercial and healthcare datasets demonstrate that Logic-Logit outperforms baseline models in both interpretability and accuracy."
resource: "https://arxiv.org/abs/2610.05501"
tags:
  - "choice-modeling"
  - "interpretable-machine-learning"
timestamp: "2026-10-18T09:17:47Z"

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
    description: "A novel rule-based interpretable choice model that leverages logic rules for human choice modeling."
datasets:
  []
open_questions:
  - name: "scalable-logic-rule-choice-modeling"
    description: "Investigate advanced scalable optimization techniques and heuristics to handle extremely high-dimensional feature spaces and larger rule conjunction lengths without prohibitive computational overhead during the column generation and Frank-Wolfe steps."
skill: "GeneralMLSkill"
processed_at: "2026-10-18T09:17:47Z"
created_at: "2026-10-18T09:17:47Z"
---

# Logic-Logit: A Logic-Based Approach to Choice Modeling

**Authors**: Shuhan Zhang, Wendi Ren, Shuang Li
**Date**: 2026-10-04
**Paper ID**: [openalex:2610.05501](https://arxiv.org/abs/2610.05501)

## Summary

This paper proposes Logic-Logit, a rule-based interpretable choice model designed to mimic human heuristic decision processes represented as disjunctions of conjunctions. To overcome the NP-hard nature of rule extraction, the authors introduce an efficient optimization approach combining column generation and the Frank-Wolfe algorithm. Empirical evaluations on synthetic and real-world commercial and healthcare datasets demonstrate that Logic-Logit outperforms baseline models in both interpretability and accuracy.

## Key Contributions

- Proposes Logic-Logit, a novel rule-based interpretable choice model that mimics human heuristic decision processes using logic rules (disjunctions of conjunctions).
- Introduces an efficient rule extraction framework combining column generation techniques and the Frank-Wolfe algorithm to tackle the NP-hard preference modeling problem.
- Demonstrates through empirical evaluation on synthetic datasets and real-world commercial and healthcare data that Logic-Logit outperforms baseline models in both interpretability and predictive accuracy.

## Open Questions & Future Work

- [[scalable-logic-rule-choice-modeling]]

## Key Concepts

- [[logic-logit]]: A novel rule-based interpretable choice model that leverages logic rules for human choice modeling.

## Archivist Review

Approved the core concept 'logic-logit' and the open question regarding scalable logic rule choice modeling, as they represent distinct, reusable contributions to interpretable choice modeling. No named datasets were present to approve.

### Approved Concepts
- Logic-Logit: It introduces a new methodology combining column generation and the Frank-Wolfe algorithm to solve the NP-hard problem of rule extraction for choice modeling.

### Approved Open Questions

## Links

- [Abstract](https://arxiv.org/abs/2610.05501)
- [PDF](https://arxiv.org/pdf/2610.05501)

