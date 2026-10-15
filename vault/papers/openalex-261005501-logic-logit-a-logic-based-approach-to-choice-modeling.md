---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Logic-Logit: A Logic-Based Approach to Choice Modeling"
description: "The paper introduces Logic-Logit, a novel rule-based interpretable choice model that mimics human heuristic consider-then-choose decision processes using logic rules. By combining column generation techniques and the Frank-Wolfe algorithm, the approach efficiently addresses the NP-hard problem of rule extraction for preference modeling. Empirical evaluations on synthetic, commercial, and healthcare datasets demonstrate that Logic-Logit outperforms traditional baselines in both prediction accuracy and interpretability."
resource: "https://arxiv.org/abs/2610.05501"
tags:
  - "machine-learning"
  - "choice-modeling"
  - "interpretable-machine-learning"
timestamp: "2026-10-15T04:44:57Z"

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
    description: "A rule-based interpretable choice model that leverages logic rules for preference modeling."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-15T04:44:57Z"
created_at: "2026-10-15T04:44:57Z"
---

# Logic-Logit: A Logic-Based Approach to Choice Modeling

**Authors**: Shuhan Zhang, Wendi Ren, Shuang Li
**Date**: 2026-10-04
**Paper ID**: [openalex:2610.05501](https://arxiv.org/abs/2610.05501)

## Summary

The paper introduces Logic-Logit, a novel rule-based interpretable choice model that mimics human heuristic consider-then-choose decision processes using logic rules. By combining column generation techniques and the Frank-Wolfe algorithm, the approach efficiently addresses the NP-hard problem of rule extraction for preference modeling. Empirical evaluations on synthetic, commercial, and healthcare datasets demonstrate that Logic-Logit outperforms traditional baselines in both prediction accuracy and interpretability.

## Key Contributions

- Introduces Logic-Logit, a rule-based interpretable choice model that mimics human heuristic decision processes using OR-of-ANDs logic rules.
- Formulates and solves the NP-hard rule extraction problem for preference modeling using a novel combination of column generation techniques and the Frank-Wolfe algorithm.
- Demonstrates superior performance over baseline models in both interpretability and accuracy across synthetic, commercial, and healthcare datasets.

## Limitations

The abstract does not explicitly discuss limitations, though rule extraction processes for choice modeling are computationally challenging (NP-hard).

## Key Concepts

- [[logic-logit]]: A rule-based interpretable choice model that leverages logic rules for preference modeling.

## Archivist Review

Approved Logic-Logit as a core concept representing a distinct, reusable methodology for interpretable choice modeling. No open questions or datasets were provided or warranted standalone vault notes.

### Approved Concepts
- Logic-Logit: Central to the paper's novelty as a new rule-based interpretable choice model combining column generation and the Frank-Wolfe algorithm.

## Links

- [Abstract](https://arxiv.org/abs/2610.05501)
- [PDF](https://arxiv.org/pdf/2610.05501)

