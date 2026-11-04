---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "SAG-Sep: Sparse Augmented Graphs and Onion-Guided Search for Rounded Capacity Cut Separation"
description: "This paper introduces SAG-Sep, a fast and effective neural separator for rounded capacity cuts (RCCs) in capacitated vehicle-routing relaxations. SAG-Sep encodes fractional LP solutions using Sparse Augmented Graphs (SAG) to expose long-range routing structure, and uses a training-free decoder called Onion-Sweep (OS) to exploit the nested 'onion-like' structure of high-value cuts. On N=1000 customer instances from the NeuralSEP benchmark, SAG-Sep reduces the average root gap by 17.7% while accelerating separation by approximately 30-fold per iteration compared to existing baselines."
resource: "https://arxiv.org/abs/2610.37952"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-11-04T12:48:24Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Haoran Liu"
  - literal: "Guanyi Wang"
  - literal: "Yu Yang"
issued:
  date-parts:
    - [2026, 10, 27]

# Domain-specific custom fields
paper_id: "2610.37952"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "sag-sep"
    description: "A neural separator for rounded capacity cuts that encodes fractional LP solutions via sparse augmented graphs and decodes nested cuts via onion-guided search."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-04T12:48:24Z"
created_at: "2026-11-04T12:48:24Z"
---

# SAG-Sep: Sparse Augmented Graphs and Onion-Guided Search for Rounded Capacity Cut Separation

**Authors**: Haoran Liu, Guanyi Wang, Yu Yang
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.37952](https://arxiv.org/abs/2610.37952)

## Summary

This paper introduces SAG-Sep, a fast and effective neural separator for rounded capacity cuts (RCCs) in capacitated vehicle-routing relaxations. SAG-Sep encodes fractional LP solutions using Sparse Augmented Graphs (SAG) to expose long-range routing structure, and uses a training-free decoder called Onion-Sweep (OS) to exploit the nested 'onion-like' structure of high-value cuts. On N=1000 customer instances from the NeuralSEP benchmark, SAG-Sep reduces the average root gap by 17.7% while accelerating separation by approximately 30-fold per iteration compared to existing baselines.

## Key Contributions

- Introduces SAG-Sep, a single-pass neural separator for rounded capacity cuts (RCCs) that scores node membership across vehicle-count levels.
- Proposes Sparse Augmented Graph (SAG) encoding to capture long-range routing structure via flow-informed multi-hop edges without densifying attention.
- Develops Onion-Sweep (OS), a training-free decoder that leverages the nested structure of high-value RCCs to generate structurally coordinated cut candidates in a vectorized pass.
- Achieves a 17.7% reduction in average root gap on the N=1000 NeuralSEP benchmark compared to the strongest baseline, alongside a 30-fold speedup per iteration.

## Key Concepts

- [[sag-sep]]: A neural separator for rounded capacity cuts that encodes fractional LP solutions via sparse augmented graphs and decodes nested cuts via onion-guided search.

## Archivist Review

Approved the core concept 'sag-sep' as a central novel architecture for neural cut separation. The open question was rejected because an equivalent question ('learned-decoder-for-cut-generation-diversity') already exists in the vault. No datasets were approved since NeuralSEP is used as a benchmark suite/framework.

### Approved Concepts
- SAG-Sep: Central novel separator architecture combining Sparse Augmented Graphs and Onion-Guided Search for vehicle-routing cuts.

### Rejected Candidates
- [open_question] Learned Decoders for Cut Generation (`learned-decoders-cut-generation`) - duplicate_existing: This question is a close semantic duplicate of the existing vault question 'learned-decoder-for-cut-generation-diversity', which already covers learned decoders and candidate cut diversity.

## Links

- [Abstract](https://arxiv.org/abs/2610.37952)
- [PDF](https://arxiv.org/pdf/2610.37952)

