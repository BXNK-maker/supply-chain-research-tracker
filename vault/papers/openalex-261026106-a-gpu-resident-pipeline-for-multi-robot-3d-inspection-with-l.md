---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
description: "This paper presents an end-to-end, GPU-resident pipeline for multi-robot 3D inspection of underwater structures using fleets of robots with limited field-of-view cameras. The pipeline decomposes the NP-hard joint problem into five core stages—candidate viewpoint generation, visibility computation, set cover, MIP-based min-max vehicle routing, and priority-based multi-agent path finding—all accelerated via custom CUDA kernels. Evaluations across 14 complex meshes containing up to 7.2 million faces demonstrate the effectiveness of the proposed routing cuts, parallel-frontier search, and trajectory smoothing."
resource: "https://arxiv.org/abs/2610.26106"
tags:
  - "vehicle-routing-problem"
  - "multi-agent-reinforcement-learning"
timestamp: "2026-10-27T10:10:44Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Kryštof Pšenička"
  - literal: "Stefan Edelkamp"
issued:
  date-parts:
    - [2026, 10, 19]

# Domain-specific custom fields
paper_id: "2610.26106"
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
processed_at: "2026-10-27T10:10:44Z"
created_at: "2026-10-27T10:10:44Z"
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

**Authors**: Kryštof Pšenička, Stefan Edelkamp
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.26106](https://arxiv.org/abs/2610.26106)

## Summary

This paper presents an end-to-end, GPU-resident pipeline for multi-robot 3D inspection of underwater structures using fleets of robots with limited field-of-view cameras. The pipeline decomposes the NP-hard joint problem into five core stages—candidate viewpoint generation, visibility computation, set cover, MIP-based min-max vehicle routing, and priority-based multi-agent path finding—all accelerated via custom CUDA kernels. Evaluations across 14 complex meshes containing up to 7.2 million faces demonstrate the effectiveness of the proposed routing cuts, parallel-frontier search, and trajectory smoothing.

## Key Contributions

- Proposes an end-to-end GPU-resident pipeline for multi-robot 3D inspection under limited perception and short-range fields of view, integrating viewpoint generation, visibility, set cover, MIP routing, and multi-agent path finding.
- Develops a GPU batch adaptation of Lien's epsilon-visibility using four custom CUDA kernels.
- Introduces a beta-aware per-vehicle tour upper bound and forbidden-pair cuts to strengthen mixed-integer programming for min-max vehicle routing.
- Extends Zhou and Zeng's GPU parallel-frontier A* search into a 4D space-time formulation for continuous-time inter-robot conflict checking.
- Evaluates the pipeline on 14 meshes with up to 7.2 million faces, demonstrating end-to-end performance and collision-free waypoint attainment after trajectory smoothing.

## Links

- [Abstract](https://arxiv.org/abs/2610.26106)
- [PDF](https://arxiv.org/pdf/2610.26106)

