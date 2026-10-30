---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A State Augmented Approach to Paralle Modeling in High-Level Synthesis"
description: "High-level synthesis (HLS) often struggles to extract concurrency from sequential behavioral models in feedback-coupled designs because architectural state boundaries and hazard resolutions are obscured. This paper develops an explicit architectural modeling methodology using synchronous sequential processes written in C++ to represent persistent state, communication, and feedback control while letting HLS handle scheduling and binding. Applied to a five-stage RV32I processor on a Kintex UltraScale+ FPGA, the approach achieves superior CPI-optimized performance (1.221 CPI at 220 MHz) and significant area reductions compared to algorithmic HLS baselines and hand-written references."
resource: "https://arxiv.org/abs/2610.36481"
tags:
  - "machine-learning"
timestamp: "2026-10-30T11:10:13Z"

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
processed_at: "2026-10-30T11:10:13Z"
created_at: "2026-10-30T11:10:13Z"
---

# A State Augmented Approach to Paralle Modeling in High-Level Synthesis

**Authors**: Nicholas Kovacs, Hao Zheng
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.36481](https://arxiv.org/abs/2610.36481)

## Summary

High-level synthesis (HLS) often struggles to extract concurrency from sequential behavioral models in feedback-coupled designs because architectural state boundaries and hazard resolutions are obscured. This paper develops an explicit architectural modeling methodology using synchronous sequential processes written in C++ to represent persistent state, communication, and feedback control while letting HLS handle scheduling and binding. Applied to a five-stage RV32I processor on a Kintex UltraScale+ FPGA, the approach achieves superior CPI-optimized performance (1.221 CPI at 220 MHz) and significant area reductions compared to algorithmic HLS baselines and hand-written references.

## Key Contributions

- Proposes an explicit architectural modeling methodology using synchronous sequential processes in HLS to separate designer-controlled architecture from tool-controlled scheduling.
- Demonstrates that a CPI-optimized RV32I processor on a Kintex UltraScale+ FPGA achieves 1.221 cycles per instruction at 220 MHz, outperforming an algorithmic HLS baseline (4.000 CPI) and an Ibex reference (1.575 CPI at 242 MHz).
- Shows an area-optimized configuration reducing LUTs by 65% and registers by 47% relative to the baseline while achieving a 250 MHz clock.

## Archivist Review

Applied strict standards for the vault. The paper's contribution is in hardware design and high-level synthesis (FPGA/processor modeling), which falls outside the core machine learning scope of this repository.

### Rejected Candidates
- [open_question] Broader Domain Evaluation for HLS (`broader-domain-evaluation-hls`) - low_impact: The paper focuses on high-level synthesis for hardware design (FPGA/processors), which is outside the core machine learning scope of this vault.

## Links

- [Abstract](https://arxiv.org/abs/2610.36481)
- [PDF](https://arxiv.org/pdf/2610.36481)

