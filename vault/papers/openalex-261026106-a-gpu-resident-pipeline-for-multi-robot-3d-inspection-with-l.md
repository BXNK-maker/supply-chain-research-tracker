---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
description: "The paper presents a GPU-resident pipeline for multi-robot 3D inspection of underwater structures under limited perception. Given a triangle mesh and a fleet of robots with short-range cameras, the approach decomposes the NP-hard joint problem into five stages: viewpoint generation, visibility computation, set cover, min-max vehicle routing solved via MIP, and priority-based multi-agent path finding with continuous-time conflict checking. The method achieves GPU acceleration through custom CUDA kernels, parallel-frontier search extensions, and customized routing cuts, and is evaluated on complex meshes up to 7.2 million faces."
resource: "https://arxiv.org/abs/2610.26106"
tags:
  - "multi-agent-reinforcement-learning"
timestamp: "2026-10-29T11:16:16Z"

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
processed_at: "2026-10-29T11:16:16Z"
created_at: "2026-10-29T11:16:16Z"
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

**Authors**: Kryštof Pšenička, Stefan Edelkamp
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.26106](https://arxiv.org/abs/2610.26106)

## Summary

The paper presents a GPU-resident pipeline for multi-robot 3D inspection of underwater structures under limited perception. Given a triangle mesh and a fleet of robots with short-range cameras, the approach decomposes the NP-hard joint problem into five stages: viewpoint generation, visibility computation, set cover, min-max vehicle routing solved via MIP, and priority-based multi-agent path finding with continuous-time conflict checking. The method achieves GPU acceleration through custom CUDA kernels, parallel-frontier search extensions, and customized routing cuts, and is evaluated on complex meshes up to 7.2 million faces.

## Key Contributions

- An end-to-end GPU-accelerated pipeline for multi-robot 3D inspection of underwater structures featuring five decomposed stages.
- A GPU batch adaptation of Lien's epsilon-visibility utilizing four custom CUDA kernels.
- A beta-aware per-vehicle tour upper bound combined with Desrochers-Laporte coefficient lift and forbidden-pair cuts for min-max vehicle routing.
- A 4D space-time extension of Zhou and Zeng's GPU parallel-frontier A* algorithm for priority-based multi-agent path finding.
- An experimental evaluation across 14 meshes with up to 7.2 million faces, auditing collision freedom and waypoint attainment.

## Archivist Review

Applied strict criteria for permanent vault inclusion. The open question on coupled location-routing viewpoint selection is highly domain-specific to multi-robot 3D inspection and vehicle routing rather than a broad, reusable machine learning or general robotics bottleneck, so it was rejected. No concepts or datasets met the threshold.

### Rejected Candidates
- [open_question] Coupled Location-Routing Viewpoint Selection (`location-routing-viewpoint-selection`) - low_impact: Too domain-specific to multi-robot 3D inspection and routing pipelines rather than a broad foundational ML or robotics bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.26106)
- [PDF](https://arxiv.org/pdf/2610.26106)

