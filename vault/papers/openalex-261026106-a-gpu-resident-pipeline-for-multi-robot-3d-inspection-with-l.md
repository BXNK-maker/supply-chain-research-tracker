---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
description: "The authors propose a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures using fleets of robots with limited field-of-view cameras. The pipeline decomposes the NP-hard joint problem into five stages: candidate viewpoint generation, visibility computation, set cover, mixed-integer programming for min-max vehicle routing, and priority-based multi-agent path finding. Through custom CUDA kernels, GPU batch adaptations, and spatial-temporal search extensions, the system achieves efficient end-to-end trajectory generation on complex meshes with up to 7.2 million faces."
resource: "https://arxiv.org/abs/2610.26106"
tags:
  - "fleet-scheduling"
  - "multi-agent-reinforcement-learning"
  - "robotics"
timestamp: "2026-11-01T11:39:13Z"

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
processed_at: "2026-11-01T11:39:13Z"
created_at: "2026-11-01T11:39:13Z"
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

**Authors**: Kryštof Pšenička, Stefan Edelkamp
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.26106](https://arxiv.org/abs/2610.26106)

## Summary

The authors propose a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures using fleets of robots with limited field-of-view cameras. The pipeline decomposes the NP-hard joint problem into five stages: candidate viewpoint generation, visibility computation, set cover, mixed-integer programming for min-max vehicle routing, and priority-based multi-agent path finding. Through custom CUDA kernels, GPU batch adaptations, and spatial-temporal search extensions, the system achieves efficient end-to-end trajectory generation on complex meshes with up to 7.2 million faces.

## Key Contributions

- Proposed an end-to-end GPU-resident pipeline for multi-robot 3D inspection of underwater structures integrating viewpoint generation, visibility computation, set cover, MIP routing, and multi-agent path finding.
- Developed a GPU batch adaptation of Lien's \epsilon-visibility utilizing four custom CUDA kernels.
- Derived a \beta-aware per-vehicle tour upper bound combined with lifted Miller-Tucker-Zemlin subtour elimination and forbidden-pair cuts for min-max vehicle routing.
- Extended Zhou and Zeng's GPU parallel-frontier A* search to a 4D space-time domain with continuous-time inter-robot conflict checking.
- Evaluated the pipeline on 14 meshes with up to 7.2M faces, measuring performance against analytical and LP-relaxation lower bounds.

## Archivist Review

No distinct reusable concepts or named critical datasets were identified that meet the strict novelty and reusability criteria for vault notes.

## Links

- [Abstract](https://arxiv.org/abs/2610.26106)
- [PDF](https://arxiv.org/pdf/2610.26106)

