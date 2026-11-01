---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "SAG-Sep: Sparse Augmented Graphs and Onion-Guided Search for Rounded Capacity Cut Separation"
description: "This paper introduces SAG-Sep, a neural separator for rounded capacity cuts (RCCs) in capacitated vehicle-routing relaxations. By encoding the fractional LP solution into a Sparse Augmented Graph (SAG) with flow-informed multi-hop edges, SAG-Sep avoids iterative predict-and-coarsen inference and achieves a 30-fold per-iteration speedup. Furthermore, leveraging the observation that high-value RCCs exhibit a nested, onion-like structure, the authors propose Onion-Sweep (OS), a training-free decoder that converts node scores into structurally coordinated cut candidates. Evaluated on N=1000 customer instances from the NeuralSEP benchmark, SAG-Sep with OS reduces the average root gap by 17.7% relative to existing neural baselines."
resource: "https://arxiv.org/abs/2610.37952"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
  - "machine-learning"
timestamp: "2026-11-01T11:39:19Z"

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
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:39:19Z"
created_at: "2026-11-01T11:39:19Z"
---

# SAG-Sep: Sparse Augmented Graphs and Onion-Guided Search for Rounded Capacity Cut Separation

**Authors**: Haoran Liu, Guanyi Wang, Yu Yang
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.37952](https://arxiv.org/abs/2610.37952)

## Summary

This paper introduces SAG-Sep, a neural separator for rounded capacity cuts (RCCs) in capacitated vehicle-routing relaxations. By encoding the fractional LP solution into a Sparse Augmented Graph (SAG) with flow-informed multi-hop edges, SAG-Sep avoids iterative predict-and-coarsen inference and achieves a 30-fold per-iteration speedup. Furthermore, leveraging the observation that high-value RCCs exhibit a nested, onion-like structure, the authors propose Onion-Sweep (OS), a training-free decoder that converts node scores into structurally coordinated cut candidates. Evaluated on N=1000 customer instances from the NeuralSEP benchmark, SAG-Sep with OS reduces the average root gap by 17.7% relative to existing neural baselines.

## Key Contributions

- Introduces SAG-Sep, a single-pass neural separator for rounded capacity cuts (RCCs) that scores node membership across vehicle-count levels without iterative predict-and-coarsen inference.
- Proposes Sparse Augmented Graph (SAG) encoding to expose long-range routing structure via flow-informed multi-hop edges without densifying attention.
- Develops Onion-Sweep (OS), a training-free decoder that leverages the nested onion-like structure of high-value RCCs to generate structurally coordinated cut candidates in a vectorized pass.
- Achieves a 17.7% reduction in average root gap compared to the strongest NeuralSEP baseline on N=1000 customer instances while providing a 30-fold speedup per iteration.

## Archivist Review

No concepts or datasets met the strict reusability and criticality criteria for standalone vault notes.

## Links

- [Abstract](https://arxiv.org/abs/2610.37952)
- [PDF](https://arxiv.org/pdf/2610.37952)

