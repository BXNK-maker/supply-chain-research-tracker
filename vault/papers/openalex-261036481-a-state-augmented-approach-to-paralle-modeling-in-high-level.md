---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A State Augmented Approach to Paralle Modeling in High-Level Synthesis"
description: "This paper presents a state-augmented parallel modeling approach for high-level synthesis (HLS) that uses synchronous sequential processes in C++ to expose architectural concurrency in feedback-coupled designs. By explicitly separating designer-controlled architecture from tool-controlled scheduling, the methodology enables fine-grained control over value consumption, timing, and memory-port mapping. Evaluated on a Kintex UltraScale+ FPGA implementing an RV32I processor, the approach achieves superior performance and area efficiency compared to algorithmic HLS baselines and hand-crafted references."
resource: "https://arxiv.org/abs/2610.36481"
tags:
  - "hardware-acceleration"
timestamp: "2026-11-03T12:38:32Z"

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
  - name: "state-augmented-parallel-modeling"
    description: "An explicit architectural modeling methodology using synchronous sequential processes to expose parallelism and decouple designer-controlled architecture from tool-controlled scheduling in high-level synthesis."
datasets:
  []
open_questions:
  - name: "non-processor-evaluation-architectural-modeling"
    description: "Broader applicability beyond the processor case study remains to be evaluated, specifically testing whether the proposed state-augmented synchronous sequential process methodology generalizes effectively to other feedback-coupled designs such as switch arbiters, cryptographic round and key schedules, or cache controllers."
skill: "GeneralMLSkill"
processed_at: "2026-11-03T12:38:32Z"
created_at: "2026-11-03T12:38:32Z"
---

# A State Augmented Approach to Paralle Modeling in High-Level Synthesis

**Authors**: Nicholas Kovacs, Hao Zheng
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.36481](https://arxiv.org/abs/2610.36481)

## Summary

This paper presents a state-augmented parallel modeling approach for high-level synthesis (HLS) that uses synchronous sequential processes in C++ to expose architectural concurrency in feedback-coupled designs. By explicitly separating designer-controlled architecture from tool-controlled scheduling, the methodology enables fine-grained control over value consumption, timing, and memory-port mapping. Evaluated on a Kintex UltraScale+ FPGA implementing an RV32I processor, the approach achieves superior performance and area efficiency compared to algorithmic HLS baselines and hand-crafted references.

## Key Contributions

- Develops an explicit architectural modeling methodology using synchronous sequential processes in C++ for high-level synthesis (HLS) of feedback-coupled designs.
- Demonstrates a CPI-optimized RV32I processor configuration achieving 1.221 CPI at 220 MHz on a Kintex UltraScale+ FPGA, outperforming an algorithmic HLS baseline (4.000 CPI) and an Ibex reference (1.575 CPI at 242 MHz).
- Achieves a 65% reduction in LUTs and 47% reduction in registers with an area-optimized configuration that incurs only 9.7% more benchmark cycles at 250 MHz.

## Open Questions & Future Work

- [[non-processor-evaluation-architectural-modeling]]

## Key Concepts

- [[state-augmented-parallel-modeling]]: An explicit architectural modeling methodology using synchronous sequential processes to expose parallelism and decouple designer-controlled architecture from tool-controlled scheduling in high-level synthesis.

## Archivist Review

Approved one central hardware synthesis methodology concept and one open question regarding its domain generalizability beyond processor implementations.

### Approved Concepts
- State Augmented Parallel Modeling: Proposes a fundamental methodology for explicit architectural modeling in high-level synthesis to expose parallelism in feedback-coupled designs.

### Approved Open Questions
- Non-Processor Domain Evaluation: Establishing whether explicit architectural modeling in C++ scales to non-processor feedback-coupled hardware domains is vital for determining the broader utility of the proposed high-level synthesis paradigm.

## Links

- [Abstract](https://arxiv.org/abs/2610.36481)
- [PDF](https://arxiv.org/pdf/2610.36481)

