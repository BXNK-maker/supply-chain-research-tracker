---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "SAG-Sep: Sparse Augmented Graphs and Onion-Guided Search for Rounded Capacity Cut Separation"
description: "The paper introduces SAG-Sep, a neural separator for rounded capacity cuts (RCCs) in capacitated vehicle-routing relaxations that avoids iterative predict-and-coarsen inference by using a single encoder forward pass. SAG-Sep employs a Sparse Augmented Graph (SAG) representation with flow-informed multi-hop edges and an Onion-Sweep (OS) training-free decoder that exploits the nested structure of high-value cuts. Experiments on the NeuralSEP benchmark with N=1000 customer instances demonstrate that SAG-Sep with OS reduces the average root gap by 17.7% over strong baselines while achieving a ~30-fold speedup per iteration."
resource: "https://arxiv.org/abs/2610.37952"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "machine-learning"
timestamp: "2026-11-02T13:07:09Z"

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
    description: "A graph representation technique that adds flow-informed multi-hop edges to expose long-range routing structure for vehicle routing problems."
  - name: "onion-sweep"
    description: "A training-free decoding mechanism that evaluates prefix violations of ranked customer scores to generate nested rounded capacity cut candidates."
datasets:
  []
open_questions:
  - name: "learned-decoder-for-cut-generation-diversity"
    description: "Develop a learned decoder for cut generation that reasons over candidate diversity and relaxation improvement, replacing the hand-designed test-time logic currently used in Onion-Sweep."
skill: "GeneralMLSkill"
processed_at: "2026-11-02T13:07:09Z"
created_at: "2026-11-02T13:07:09Z"
---

# SAG-Sep: Sparse Augmented Graphs and Onion-Guided Search for Rounded Capacity Cut Separation

**Authors**: Haoran Liu, Guanyi Wang, Yu Yang
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.37952](https://arxiv.org/abs/2610.37952)

## Summary

The paper introduces SAG-Sep, a neural separator for rounded capacity cuts (RCCs) in capacitated vehicle-routing relaxations that avoids iterative predict-and-coarsen inference by using a single encoder forward pass. SAG-Sep employs a Sparse Augmented Graph (SAG) representation with flow-informed multi-hop edges and an Onion-Sweep (OS) training-free decoder that exploits the nested structure of high-value cuts. Experiments on the NeuralSEP benchmark with N=1000 customer instances demonstrate that SAG-Sep with OS reduces the average root gap by 17.7% over strong baselines while achieving a ~30-fold speedup per iteration.

## Key Contributions

- Introduces SAG-Sep, a single-pass encoder that scores node membership in rounded capacity cut (RCC) subsets across vehicle-count levels without iterative predict-and-coarsen inference.
- Proposes Sparse Augmented Graph (SAG) encoding, adding flow-informed multi-hop edges to capture long-range routing structure without densifying attention.
- Develops Onion-Sweep (OS), a training-free decoder that leverages nested cut structures to generate structurally coordinated RCC candidates efficiently.
- Achieves a 17.7% reduction in average root gap relative to the strongest NeuralSEP baseline on N=1000 customer instances while delivering a ~30-fold per-iteration neural separation speedup.

## Open Questions & Future Work

- [[learned-decoder-for-cut-generation-diversity]]

## Key Concepts

- [[sparse-augmented-graph]]: A graph representation technique that adds flow-informed multi-hop edges to expose long-range routing structure for vehicle routing problems.
- [[onion-sweep]]: A training-free decoding mechanism that evaluates prefix violations of ranked customer scores to generate nested rounded capacity cut candidates.

## Archivist Review

Approved Sparse Augmented Graph and Onion-Sweep as distinct, highly reusable concepts for neural cut separation and graph representations. Approved one open question on learned decoders for cut generation. Rejected SAG-Sep as an umbrella system name and the NeuralSEP benchmark as a routine evaluation set.

### Approved Concepts
- Sparse Augmented Graph: Introduces a novel graph augmentation technique incorporating flow-informed multi-hop edges to expose long-range routing structure without densifying attention for vehicle-routing relaxations.
- Onion-Sweep: Provides a training-free decoding mechanism that leverages nested cut structures to efficiently generate structurally coordinated rounded capacity cut candidates.

### Approved Open Questions
- Learned Decoder for Cut Generation Diversity: Moving from hand-designed heuristics to learned decors for cut generation is a key step toward end-to-end optimization of cutting-plane procedures in combinatorial optimization solvers.

### Rejected Candidates
- [concept] SAG-Sep (`sag-sep`) - subcomponent_of_broader_mechanism: Duplicate or tightly bound subcomponent of the paper's overarching architecture combining sparse augmented graphs and onion-sweep; the specific reusable innovations are better captured by the sparse augmented graph and onion-sweep concepts.
- [dataset] NeuralSEP benchmark (`neuralsep-benchmark`) - not_reusable: Routine benchmark dataset used locally for evaluation without sufficient standalone reusability outside this specific task domain.

## Links

- [Abstract](https://arxiv.org/abs/2610.37952)
- [PDF](https://arxiv.org/pdf/2610.37952)

