---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Can a Language Model Write the Weights? An Empirical Study of LLM-Written Scoring Networks for Column Generation and MILP Branching, with a Bus-Driver Scheduling Application"
description: "This paper investigates weight-space programming (WSP), wherein a large language model directly writes the weights of a small neural network without gradient training, and tests it on exact operations research algorithms including column generation for vehicle routing and MILP branching. Across four studies—covering vehicle routing, synthetic independent-set instances, MIPLIB 2017 instances, and a real-world bus-driver scheduling application from Atlanta's MARTA—the author finds that while some speedups are achieved, performance gains stem from computational cheapness rather than advanced weight discovery by the LLM. All code, logs, and experimental data are publicly released."
resource: "https://arxiv.org/abs/2611.09559"
tags:
  - "machine-learning"
  - "combinatorial-optimization"
timestamp: "2026-11-18T13:53:50Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Renan Butkeraites"
issued:
  date-parts:
    - [2026, 11, 6]

# Domain-specific custom fields
paper_id: "2611.09559"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "weight-space-programming"
    description: "A paradigm where an LLM directly writes the weights of a small neural network based on forward-pass outputs without gradient training."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-18T13:53:50Z"
created_at: "2026-11-18T13:53:50Z"
---

# Can a Language Model Write the Weights? An Empirical Study of LLM-Written Scoring Networks for Column Generation and MILP Branching, with a Bus-Driver Scheduling Application

**Authors**: Renan Butkeraites
**Date**: 2026-11-06
**Paper ID**: [openalex:2611.09559](https://arxiv.org/abs/2611.09559)

## Summary

This paper investigates weight-space programming (WSP), wherein a large language model directly writes the weights of a small neural network without gradient training, and tests it on exact operations research algorithms including column generation for vehicle routing and MILP branching. Across four studies—covering vehicle routing, synthetic independent-set instances, MIPLIB 2017 instances, and a real-world bus-driver scheduling application from Atlanta's MARTA—the author finds that while some speedups are achieved, performance gains stem from computational cheapness rather than advanced weight discovery by the LLM. All code, logs, and experimental data are publicly released.

## Key Contributions

- Evaluated weight-space programming (WSP) using LLMs to write scoring network weights for column generation and MILP branching without gradient training.
- Demonstrated that for vehicle routing column generation, LLM-written weight levers yielded no material performance gains.
- Showed that for MILP branching, hand-written and LLM-written networks outperformed default SCIP rules on synthetic independent-set instances, but underperformed on MIPLIB 2017 instances.
- Applied WSP to a real-world Atlanta MARTA bus-driver scheduling problem, showing speedups over default SCIP settings that were ultimately attributable to computational cheapness rather than sophisticated LLM weight discovery.

## Key Concepts

- [[weight-space-programming]]: A paradigm where an LLM directly writes the weights of a small neural network based on forward-pass outputs without gradient training.

## Archivist Review

Approved 'Weight-space programming' as a distinct and reusable paradigm for direct weight assignment by LLMs without gradient training. Rejected MIPLIB 2017 as a standard external benchmark dataset.

### Approved Concepts
- Weight-space programming: Introduces a novel paradigm where large language models directly write neural network weights without gradient training.

### Rejected Candidates
- [dataset] miplib-2017 (`miplib-2017`) - not_novel: Standard external mixed-integer programming benchmark rather than a novel or custom dataset introduced by the paper.

## Links

- [Abstract](https://arxiv.org/abs/2611.09559)
- [PDF](https://arxiv.org/pdf/2611.09559)

