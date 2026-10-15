---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Logic-Logit: A Logic-Based Approach to Choice Modeling"
description: "This paper introduces Logic-Logit, a novel rule-based interpretable choice model designed to mimic human decision-making by utilizing consider-then-choose processes represented as disjunctions of conjunctions. To overcome the NP-hard nature of rule extraction, the authors propose a novel optimization framework combining column generation and the Frank-Wolfe algorithm. Empirical evaluations across synthetic, commercial, and healthcare datasets show that Logic-Logit achieves superior accuracy and interpretability compared to traditional baseline models."
resource: "https://arxiv.org/abs/2610.05501"
tags:
  - "choice-modeling"
  - "interpretable-machine-learning"
  - "machine-learning"
timestamp: "2026-10-15T09:35:12Z"

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
    description: "A rule-based interpretable choice model that leverages logic rules (disjunctions of conjunctions) for explainable human decision modeling."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-15T09:35:12Z"
created_at: "2026-10-15T09:35:12Z"
---

# Logic-Logit: A Logic-Based Approach to Choice Modeling

**Authors**: Shuhan Zhang, Wendi Ren, Shuang Li
**Date**: 2026-10-04
**Paper ID**: [openalex:2610.05501](https://arxiv.org/abs/2610.05501)

## Summary

This paper introduces Logic-Logit, a novel rule-based interpretable choice model designed to mimic human decision-making by utilizing consider-then-choose processes represented as disjunctions of conjunctions. To overcome the NP-hard nature of rule extraction, the authors propose a novel optimization framework combining column generation and the Frank-Wolfe algorithm. Empirical evaluations across synthetic, commercial, and healthcare datasets show that Logic-Logit achieves superior accuracy and interpretability compared to traditional baseline models.

## Key Contributions

- Proposes Logic-Logit, a novel rule-based interpretable choice model that models human decision processes using disjunctions of conjunctions (OR-of-ANDs).
- Leverages a unique combination of column generation techniques and the Frank-Wolfe algorithm to efficiently extract rules in an NP-hard preference modeling setting.
- Demonstrates through empirical evaluation on synthetic, commercial, and healthcare datasets that Logic-Logit outperforms baseline models in both interpretability and predictive accuracy.

## Limitations

The abstract does not specify limitations, though the rule extraction process relies on solving NP-hard optimization problems which may scale with feature and alternative complexity.

## Key Concepts

- [[logic-logit]]: A rule-based interpretable choice model that leverages logic rules (disjunctions of conjunctions) for explainable human decision modeling.

## Archivist Review

Approved 'Logic-Logit' as the primary novel concept for the vault. All standard optimization subcomponents were rejected per our policy against subcomponents of broader mechanisms. No datasets or open questions met the rigorous threshold for standalone vault inclusion.

### Approved Concepts
- Logic-Logit: Introduces the core rule-based interpretable choice model combining logic rules with logit-based preference modeling.

### Rejected Candidates
- [concept] Frank-Wolfe Column Generation (`frank-wolfe-column-generation`) - subcomponent_of_broader_mechanism: Standard optimization techniques combined here for a specific problem rather than introduced as a novel algorithmic contribution.

## Links

- [Abstract](https://arxiv.org/abs/2610.05501)
- [PDF](https://arxiv.org/pdf/2610.05501)

