---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A State Augmented Approach to Paralle Modeling in High-Level Synthesis"
description: "High-level synthesis (HLS) often struggles with feedback-coupled designs because sequential behavioral models obscure architectural state boundaries and hazard resolution. This paper introduces an explicit architectural modeling methodology based on synchronous sequential processes to separate designer-controlled architecture from tool-controlled scheduling. Evaluated on a five-stage RV32I processor on a Kintex UltraScale+ FPGA, the approach significantly outperforms algorithmic HLS baselines in both CPI and resource utilization."
resource: "https://arxiv.org/abs/2610.36481"
tags:
  - "hardware-acceleration"
timestamp: "2026-11-01T11:39:55Z"

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
  - name: "variable-latency-memory-hls-modeling"
    description: "Investigate the integration of variable-latency external memory systems and caches within the synchronous sequential process modeling framework, where memory misses act as dynamic hold conditions rather than extending iteration latency."
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:39:55Z"
created_at: "2026-11-01T11:39:55Z"
---

# A State Augmented Approach to Paralle Modeling in High-Level Synthesis

**Authors**: Nicholas Kovacs, Hao Zheng
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.36481](https://arxiv.org/abs/2610.36481)

## Summary

High-level synthesis (HLS) often struggles with feedback-coupled designs because sequential behavioral models obscure architectural state boundaries and hazard resolution. This paper introduces an explicit architectural modeling methodology based on synchronous sequential processes to separate designer-controlled architecture from tool-controlled scheduling. Evaluated on a five-stage RV32I processor on a Kintex UltraScale+ FPGA, the approach significantly outperforms algorithmic HLS baselines in both CPI and resource utilization.

## Key Contributions

- Developed an explicit architectural modeling methodology using synchronous sequential processes to overcome concurrency limits in high-level synthesis (HLS) for feedback-coupled designs.
- Achieved 1.221 cycles per instruction at 220 MHz on a Kintex UltraScale+ FPGA using a CPI-optimized RV32I processor configuration, outperforming an algorithmic HLS baseline of 4.000 cycles per instruction.
- Demonstrated an area-optimized RV32I configuration that reduces LUTs by 65% and registers by 47% compared to the CPI-optimized configuration, while increasing benchmark cycles by only 9.7%.

## Open Questions & Future Work

- [[variable-latency-memory-hls-modeling]]

## Archivist Review

Applied strict reusability and scarcity standards. No concepts were proposed or approved because the paper's synchronous sequential process methodology is deeply tied to hardware high-level synthesis (HLS) design patterns and does not constitute a broadly reusable ML concept. The open question regarding variable-latency memory in HLS process models was approved as it targets a fundamental limitation in hardware synthesis modeling.

### Approved Open Questions
- Variable-Latency Memory in HLS Process Models: Extending the state-augmented modeling methodology to handle variable-latency external memory and caches is critical to demonstrating its viability for general-purpose processor designs operating outside idealized on-chip memory environments.

## Links

- [Abstract](https://arxiv.org/abs/2610.36481)
- [PDF](https://arxiv.org/pdf/2610.36481)

