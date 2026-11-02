---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A State Augmented Approach to Paralle Modeling in High-Level Synthesis"
description: "This paper proposes a state-augmented approach to parallel modeling in high-level synthesis (HLS) using synchronous sequential processes to unlock concurrency in feedback-coupled designs. By explicitly representing persistent state, communication, and feedback control in C++, the methodology separates designer-controlled architecture from tool-controlled scheduling. Evaluations on a Kintex UltraScale+ FPGA using a five-stage RV32I processor show that the CPI-optimized design achieves 1.221 cycles per instruction at 220 MHz, significantly outperforming algorithmic HLS baselines and reference processors."
resource: "https://arxiv.org/abs/2610.36481"
tags:
  - "hardware-acceleration"
timestamp: "2026-11-02T13:07:17Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Nicholas Kovacs"
  - literal: "Hao Zheng"
issued:
  date-parts:
    - [2026, 10, 27]

# Domain-specific custom fields
paper_id: "2610.36481"
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
processed_at: "2026-11-02T13:07:17Z"
created_at: "2026-11-02T13:07:17Z"
---

# A State Augmented Approach to Paralle Modeling in High-Level Synthesis

**Authors**: Nicholas Kovacs, Hao Zheng
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.36481](https://arxiv.org/abs/2610.36481)

## Summary

This paper proposes a state-augmented approach to parallel modeling in high-level synthesis (HLS) using synchronous sequential processes to unlock concurrency in feedback-coupled designs. By explicitly representing persistent state, communication, and feedback control in C++, the methodology separates designer-controlled architecture from tool-controlled scheduling. Evaluations on a Kintex UltraScale+ FPGA using a five-stage RV32I processor show that the CPI-optimized design achieves 1.221 cycles per instruction at 220 MHz, significantly outperforming algorithmic HLS baselines and reference processors.

## Key Contributions

- Developed an explicit architectural modeling methodology using synchronous sequential processes to improve concurrency in high-level synthesis (HLS) for feedback-coupled designs.
- Demonstrated a CPI-optimized RV32I processor configuration achieving 1.221 cycles per instruction at 220 MHz on a Kintex UltraScale+ FPGA, outperforming an algorithmic HLS baseline and an Ibex reference.
- Demonstrated an area-optimized RV32I configuration achieving a 65% reduction in LUTs and 47% in registers compared to the baseline while maintaining competitive performance.

## Archivist Review

Applied strict quality and reusability standards. No concepts, datasets, or open questions from this hardware synthesis paper met the criteria for permanent standalone vault notes.

### Rejected Candidates
- [open_question] Broader Applicability of Architectural Modeling (`broader-applicability-of-architectural-modeling`) - other: This is a standard future work suggestion exploring generalizability across different hardware workloads rather than a distinct, rigorous technical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.36481)
- [PDF](https://arxiv.org/pdf/2610.36481)

