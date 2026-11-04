---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A State Augmented Approach to Paralle Modeling in High-Level Synthesis"
description: "High-level synthesis often struggles with feedback-coupled designs because sequential behavioral models obscure architectural state boundaries and hazard resolution. This paper develops a state-augmented parallel modeling methodology using synchronous sequential processes implemented in C++ to separate designer-controlled architecture from tool-controlled scheduling. Evaluating a five-stage RV32I processor on a Kintex UltraScale+ FPGA shows significant improvements in CPI and area utilization compared to traditional algorithmic HLS baselines."
resource: "https://arxiv.org/abs/2610.36481"
tags:
  - "hardware-acceleration"
timestamp: "2026-11-04T12:48:54Z"

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
  - name: "state-augmented-parallel-modeling-hls"
    description: "An explicit architectural modeling methodology for high-level synthesis using synchronous sequential processes to overcome sequential behavioral obscuration in feedback-coupled designs."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-04T12:48:54Z"
created_at: "2026-11-04T12:48:54Z"
---

# A State Augmented Approach to Paralle Modeling in High-Level Synthesis

**Authors**: Nicholas Kovacs, Hao Zheng
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.36481](https://arxiv.org/abs/2610.36481)

## Summary

High-level synthesis often struggles with feedback-coupled designs because sequential behavioral models obscure architectural state boundaries and hazard resolution. This paper develops a state-augmented parallel modeling methodology using synchronous sequential processes implemented in C++ to separate designer-controlled architecture from tool-controlled scheduling. Evaluating a five-stage RV32I processor on a Kintex UltraScale+ FPGA shows significant improvements in CPI and area utilization compared to traditional algorithmic HLS baselines.

## Key Contributions

- Proposes a state-augmented parallel modeling methodology for high-level synthesis based on synchronous sequential processes that start in lockstep and synchronize completion.
- Demonstrates modeling decisions for a five-stage RV32I processor, clarifying value versions, consumption timing, and memory-to-port mappings.
- Achieves 1.221 CPI at 220 MHz on a Kintex UltraScale+ FPGA for a CPI-optimized configuration, outperforming an algorithmic HLS baseline of 4.000 CPI.
- Provides an area-optimized configuration that reduces LUTs by 65% and registers by 47% relative to the baseline while achieving a 250 MHz clock.

## Key Concepts

- [[state-augmented-parallel-modeling-hls]]: An explicit architectural modeling methodology for high-level synthesis using synchronous sequential processes to overcome sequential behavioral obscuration in feedback-coupled designs.

## Archivist Review

Approved the central concept of state-augmented parallel modeling in high-level synthesis as a distinct and reusable architectural pattern for feedback-coupled hardware designs. The open question regarding broader domain applicability was rejected as a routine request for broader evaluation scope.

### Approved Concepts
- State-Augmented Parallel Modeling in High-Level Synthesis: Introduces an explicit architectural modeling methodology using synchronous sequential processes to overcome limitations in high-level synthesis scheduling for feedback-coupled designs.

### Rejected Candidates
- [open_question] Broader Applicability Beyond Processors (`broader-applicability-beyond-processors-and-matched-rtl`) - low_impact: This is a routine exploration of domain generalizability and future applications common to hardware papers.

## Links

- [Abstract](https://arxiv.org/abs/2610.36481)
- [PDF](https://arxiv.org/pdf/2610.36481)

