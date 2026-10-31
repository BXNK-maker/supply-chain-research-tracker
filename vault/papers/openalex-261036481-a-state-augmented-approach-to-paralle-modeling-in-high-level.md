---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A State Augmented Approach to Paralle Modeling in High-Level Synthesis"
description: "High-level synthesis (HLS) often struggles to extract efficient parallelism from feedback-coupled sequential behavioral models due to obscured architectural state boundaries. This paper introduces an explicit architectural modeling methodology using synchronous sequential processes written in C++ to separate designer-controlled architecture from tool-controlled scheduling. Evaluating a five-stage RV32I processor on a Kintex UltraScale+ FPGA, the proposed CPI-optimized configuration achieves 1.221 cycles per instruction at 220 MHz, outperforming both an algorithmic HLS baseline and an Ibex reference design. Additionally, an area-optimized configuration achieves substantial resource reductions while maintaining high operating frequencies."
resource: "https://arxiv.org/abs/2610.36481"
tags:
  - "hardware-acceleration"
timestamp: "2026-10-31T10:43:49Z"

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
  - name: "broader-architectural-applicability-hls"
    description: "Investigate and evaluate the broader applicability of explicit architectural modeling beyond processor case studies, extending the synchronous sequential process methodology to other feedback-coupled architectures such as switch arbiters, cryptographic round and key schedules, or cache controllers."
skill: "GeneralMLSkill"
processed_at: "2026-10-31T10:43:49Z"
created_at: "2026-10-31T10:43:49Z"
---

# A State Augmented Approach to Paralle Modeling in High-Level Synthesis

**Authors**: Nicholas Kovacs, Hao Zheng
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.36481](https://arxiv.org/abs/2610.36481)

## Summary

High-level synthesis (HLS) often struggles to extract efficient parallelism from feedback-coupled sequential behavioral models due to obscured architectural state boundaries. This paper introduces an explicit architectural modeling methodology using synchronous sequential processes written in C++ to separate designer-controlled architecture from tool-controlled scheduling. Evaluating a five-stage RV32I processor on a Kintex UltraScale+ FPGA, the proposed CPI-optimized configuration achieves 1.221 cycles per instruction at 220 MHz, outperforming both an algorithmic HLS baseline and an Ibex reference design. Additionally, an area-optimized configuration achieves substantial resource reductions while maintaining high operating frequencies.

## Key Contributions

- Developed an explicit architectural modeling methodology using synchronous sequential processes in C++ for high-level synthesis (HLS) to overcome the concurrency limitations of sequential behavioral models.
- Demonstrated a CPI-optimized RV32I processor configuration achieving 1.221 cycles per instruction at 220 MHz on a Kintex UltraScale+ FPGA, outperforming an algorithmic HLS baseline (4.000 CPI) and an Ibex reference (1.575 CPI at 242 MHz).
- Demonstrated an area-optimized RV32I processor configuration achieving a 65% reduction in LUTs and a 47% reduction in registers compared to the baseline while maintaining competitive performance (9.7% more benchmark cycles at 250 MHz).

## Open Questions & Future Work

- [[broader-architectural-applicability-hls]]

## Archivist Review

Applied strict vault standards, rejecting paper-local hardware design terms while preserving the open question on generalizing explicit architectural modeling in high-level synthesis beyond simple processor cores.

### Approved Open Questions
- Broader Applicability Beyond Processors: Determining whether explicit architectural modeling generalizes beyond RISC-V processors to arbitrary control-intensive and feedback-coupled hardware is crucial for establishing the methodology as a universal HLS design paradigm.

### Rejected Candidates
- [concept] State Augmented Parallel Modeling in High-Level Synthesis (`state-augmented-parallel-modeling-hls`) - paper_local: Paper-specific hardware synthesis technique tailored to RV32I processor pipelines rather than a broadly recurring ML vault concept.

## Links

- [Abstract](https://arxiv.org/abs/2610.36481)
- [PDF](https://arxiv.org/pdf/2610.36481)

