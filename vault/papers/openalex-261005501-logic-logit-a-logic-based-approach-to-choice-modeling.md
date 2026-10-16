---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Logic-Logit: A Logic-Based Approach to Choice Modeling"
description: "This paper introduces Logic-Logit, a novel rule-based choice model designed to mimic human consider-then-choose decision processes through disjunctive logic rules (OR-of-ANDs). By combining column generation techniques and the Frank-Wolfe algorithm, the approach efficiently addresses the NP-hard problem of rule extraction for preference modeling. Empirical evaluations on synthetic, commercial, and healthcare datasets demonstrate superior performance in both interpretability and accuracy compared to baseline models."
resource: "https://arxiv.org/abs/2610.05501"
tags:
  - "choice-modeling"
  - "interpretable-machine-learning"
timestamp: "2026-10-16T09:36:02Z"

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
    description: "A rule-based interpretable choice model that learns disjunctive logic rules for consider-then-choose human decision processes."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-16T09:36:02Z"
created_at: "2026-10-16T09:36:02Z"
---

# Logic-Logit: A Logic-Based Approach to Choice Modeling

**Authors**: Shuhan Zhang, Wendi Ren, Shuang Li
**Date**: 2026-10-04
**Paper ID**: [openalex:2610.05501](https://arxiv.org/abs/2610.05501)

## Summary

This paper introduces Logic-Logit, a novel rule-based choice model designed to mimic human consider-then-choose decision processes through disjunctive logic rules (OR-of-ANDs). By combining column generation techniques and the Frank-Wolfe algorithm, the approach efficiently addresses the NP-hard problem of rule extraction for preference modeling. Empirical evaluations on synthetic, commercial, and healthcare datasets demonstrate superior performance in both interpretability and accuracy compared to baseline models.

## Key Contributions

- Proposes Logic-Logit, a novel rule-based interpretable choice model that mimics human consider-then-choose decision processes using disjunctions of conjunctions (OR-of-ANDs).
- Combines column generation techniques and the Frank-Wolfe algorithm to efficiently extract logic rules for preference modeling, overcoming the NP-hard nature of the problem.
- Demonstrates through empirical evaluation on synthetic, commercial, and healthcare datasets that Logic-Logit outperforms baseline models in both interpretability and prediction accuracy.

## Limitations

The abstract does not explicitly detail limitations, though rule extraction is noted as an NP-hard problem managed via column generation and Frank-Wolfe.

## Key Concepts

- [[logic-logit]]: A rule-based interpretable choice model that learns disjunctive logic rules for consider-then-choose human decision processes.

## Archivist Review

Approved the core concept 'logic-logit' as it represents a novel and reusable rule-based choice modeling paradigm. No standalone datasets or open questions met the rigorous inclusion bar for permanent vault entries.

### Approved Concepts
- Logic-Logit: It is the core model proposed in the paper, combining logic rules and choice modeling for high interpretability and accuracy.

## Links

- [Abstract](https://arxiv.org/abs/2610.05501)
- [PDF](https://arxiv.org/pdf/2610.05501)

