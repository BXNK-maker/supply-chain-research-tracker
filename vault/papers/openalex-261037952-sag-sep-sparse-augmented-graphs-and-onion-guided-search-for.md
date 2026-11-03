---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "SAG-Sep: Sparse Augmented Graphs and Onion-Guided Search for Rounded Capacity Cut Separation"
description: "The authors present SAG-Sep, a neural separation method for rounded capacity cuts (RCCs) in capacitated vehicle-routing relaxations that outperforms existing separators in speed and solution quality. By encoding fractional LP solutions into Sparse Augmented Graphs (SAG) with flow-informed multi-hop edges and employing a training-free decoder called Onion-Sweep (OS) that leverages the nested structure of high-value cuts, SAG-Sep scores node memberships in a single forward pass. On N=1000 customer instances from the NeuralSEP benchmark, SAG-Sep achieves a ~30-fold speedup per iteration and reduces the average root gap by 17.7% compared to existing neural baselines."
resource: "https://arxiv.org/abs/2610.37952"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "neural-routing-solver"
  - "approximation-algorithms"
timestamp: "2026-11-03T12:38:27Z"

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
  - name: "sparse-augmented-graph"
    description: "An LP-aware sparse encoding technique with flow-informed multi-hop edges that exposes long-range routing structure without densifying graph attention."
  - name: "onion-sweep"
    description: "A training-free decoder that evaluates prefix violations of scored nodes in a vectorized pass to generate nested rounded capacity cut candidates."
datasets:
  []
open_questions:
  - name: "learned-decoder-for-cut-generation-diversity"
    description: "Investigate the development of fully learned decoders that replace hand-designed test-time logic like Onion-Sweep to optimize entire cut sets and relaxation improvements rather than relying on supervised labels or heuristic ranking sweeps."
skill: "GeneralMLSkill"
processed_at: "2026-11-03T12:38:27Z"
created_at: "2026-11-03T12:38:27Z"
---

# SAG-Sep: Sparse Augmented Graphs and Onion-Guided Search for Rounded Capacity Cut Separation

**Authors**: Haoran Liu, Guanyi Wang, Yu Yang
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.37952](https://arxiv.org/abs/2610.37952)

## Summary

The authors present SAG-Sep, a neural separation method for rounded capacity cuts (RCCs) in capacitated vehicle-routing relaxations that outperforms existing separators in speed and solution quality. By encoding fractional LP solutions into Sparse Augmented Graphs (SAG) with flow-informed multi-hop edges and employing a training-free decoder called Onion-Sweep (OS) that leverages the nested structure of high-value cuts, SAG-Sep scores node memberships in a single forward pass. On N=1000 customer instances from the NeuralSEP benchmark, SAG-Sep achieves a ~30-fold speedup per iteration and reduces the average root gap by 17.7% compared to existing neural baselines.

## Key Contributions

- Introduces SAG-Sep, a neural separator for rounded capacity cuts that avoids iterative predict-and-coarsen inference by scoring node membership across vehicle-count levels in a single encoder forward pass.
- Proposes Sparse Augmented Graph (SAG) encoding to expose long-range routing structure via flow-informed multi-hop edges without densifying attention.
- Develops Onion-Sweep (OS), a training-free decoder that converts independent node scores into structured, nested RCC candidates via vectorized prefix evaluation.
- Reduces average root gap by 17.7% relative to the strongest NeuralSEP baseline on N=1000 customer instances while achieving a ~30-fold per-iteration neural separation speedup.

## Open Questions & Future Work

- [[learned-decoder-for-cut-generation-diversity]]

## Key Concepts

- [[sparse-augmented-graph]]: An LP-aware sparse encoding technique with flow-informed multi-hop edges that exposes long-range routing structure without densifying graph attention.
- [[onion-sweep]]: A training-free decoder that evaluates prefix violations of scored nodes in a vectorized pass to generate nested rounded capacity cut candidates.

## Archivist Review

Approved Sparse Augmented Graph and Onion-Sweep as they represent distinct, reusable architectural and decoding mechanisms for neural cut separation. The open question was mapped to the existing vault entry 'learned-decoder-for-cut-generation-diversity' to maintain taxonomy hygiene.

### Approved Concepts
- Sparse Augmented Graph: Introduces a novel LP-aware sparse encoding method that incorporates flow-informed multi-hop edges to expose long-range routing structure for vehicle-routing problems.
- Onion-Sweep: Proposes a training-free decoding strategy that converts independent node scores into structurally coordinated nested cut proposals in a single vectorized pass.

### Approved Open Questions
- Learned Decoders for Cut Generation: Replacing hand-designed decoders with learned scoring or reinforcement learning loops is crucial for scaling neural cutting plane generators to broader combinatorial optimization problems without task-specific heuristic adjustments.

## Links

- [Abstract](https://arxiv.org/abs/2610.37952)
- [PDF](https://arxiv.org/pdf/2610.37952)

