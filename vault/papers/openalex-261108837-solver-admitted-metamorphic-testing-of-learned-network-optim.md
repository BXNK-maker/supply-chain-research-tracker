---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Solver-Admitted Metamorphic Testing of Learned Network Optimization Surrogates"
description: "This paper introduces solver-admitted metamorphic testing to audit learned network optimization surrogates against equivalent problem encodings, accounting for numerical error and multiple optima. The authors evaluate this framework across alternating-current optimal power flow, traveling salesman, capacitated vehicle routing, and maximum independent set problems, revealing widespread consistency violations in prominent models such as GridSFM-Open, POMO, and DIFUSCO. Furthermore, the study demonstrates that interventions like source patches and post hoc normalization can mitigate specific discrepancies but fail to guarantee uniform accuracy and feasibility."
resource: "https://arxiv.org/abs/2611.08837"
tags:
  - "combinatorial-optimization"
  - "neural-routing-solver"
  - "machine-learning"
timestamp: "2026-11-19T14:13:21Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Vineet Jagadeesan Nair"
  - literal: "Stephen Peng"
  - literal: "Arun Ravindran"
issued:
  date-parts:
    - [2026, 11, 6]

# Domain-specific custom fields
paper_id: "2611.08837"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "solver-admitted-metamorphic-testing"
    description: "A metamorphic testing framework for learned optimization solver surrogates that incorporates explicit eligibility conditions, output alignment, and numerical thresholds."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-19T14:13:21Z"
created_at: "2026-11-19T14:13:21Z"
---

# Solver-Admitted Metamorphic Testing of Learned Network Optimization Surrogates

**Authors**: Vineet Jagadeesan Nair, Stephen Peng, Arun Ravindran
**Date**: 2026-11-06
**Paper ID**: [openalex:2611.08837](https://arxiv.org/abs/2611.08837)

## Summary

This paper introduces solver-admitted metamorphic testing to audit learned network optimization surrogates against equivalent problem encodings, accounting for numerical error and multiple optima. The authors evaluate this framework across alternating-current optimal power flow, traveling salesman, capacitated vehicle routing, and maximum independent set problems, revealing widespread consistency violations in prominent models such as GridSFM-Open, POMO, and DIFUSCO. Furthermore, the study demonstrates that interventions like source patches and post hoc normalization can mitigate specific discrepancies but fail to guarantee uniform accuracy and feasibility.

## Key Contributions

- Constructed metamorphic tests for optimization solver surrogates incorporating explicit eligibility conditions, output alignment, and numerical thresholds.
- Demonstrated that GridSFM-Open violates multiple metamorphic relations across power flow test grids, with untrained random copies failing similarly.
- Showed that routing models such as POMO exhibit sharply increasing rotation and reflection violation rates as problem scale increases from 20 to 100 cities.
- Evaluated DIFUSCO on maximum independent set problems, showing that post hoc normalization within connected components effectively removes disjoint-union relation violations.

## Limitations

No evaluated intervention fully establishes preserved accuracy and feasibility within the declared margin across every tested grid or problem instance.

## Key Concepts

- [[solver-admitted-metamorphic-testing]]: A metamorphic testing framework for learned optimization solver surrogates that incorporates explicit eligibility conditions, output alignment, and numerical thresholds.

## Archivist Review

Approved the core overarching concept 'solver-admitted-metamorphic-testing' which already exists in the vault under a very similar name or is central enough to stand alone as a testing methodology. Rejected the open question as it bundles routine future work items rather than a distinct bottleneck.

### Approved Concepts
- Solver-Admitted Metamorphic Testing: Provides a rigorous testing framework for learned network optimization surrogates by auditing equivalent problem encodings under numerical error and multiple optima.

### Rejected Candidates
- [open_question] Validating Optima Bounds and Structural Failures (`validating-optima-bounds-and-structural-failures`) - not_reusable: Combines routine future work suggestions (training from scratch, testing composed relations) without identifying a sharp, standalone bottleneck distinct from existing open questions.

## Links

- [Abstract](https://arxiv.org/abs/2611.08837)
- [PDF](https://arxiv.org/pdf/2611.08837)

