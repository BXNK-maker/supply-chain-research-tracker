---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
description: "The authors present a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures using fleets of robots with limited-FOV cameras. The pipeline decomposes the NP-hard joint coverage and routing problem into five core stages—viewpoint generation, visibility computation, set cover, min-max vehicle routing via a MIP with lifted MTZ subtour elimination, and priority-based multi-agent path finding with continuous-time conflict checking—accelerated via custom CUDA kernels. Experiments across 14 meshes (up to 7.2M faces) demonstrate scalability, effectiveness of routing cuts, and end-to-end performance against theoretical lower bounds."
resource: "https://arxiv.org/abs/2610.26106"
tags:
  - "machine-learning"
timestamp: "2026-10-23T09:45:31Z"

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
processed_at: "2026-10-23T09:45:31Z"
created_at: "2026-10-23T09:45:31Z"
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

**Authors**: Kryštof Pšenička, Stefan Edelkamp
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.26106](https://arxiv.org/abs/2610.26106)

## Summary

The authors present a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures using fleets of robots with limited-FOV cameras. The pipeline decomposes the NP-hard joint coverage and routing problem into five core stages—viewpoint generation, visibility computation, set cover, min-max vehicle routing via a MIP with lifted MTZ subtour elimination, and priority-based multi-agent path finding with continuous-time conflict checking—accelerated via custom CUDA kernels. Experiments across 14 meshes (up to 7.2M faces) demonstrate scalability, effectiveness of routing cuts, and end-to-end performance against theoretical lower bounds.

## Key Contributions

- Developed an end-to-end GPU-accelerated pipeline integrating candidate viewpoint generation, visibility computation, set cover, MIP vehicle routing, and priority-based MAPF for multi-robot 3D surface inspection.
- Designed a GPU batch adaptation of Lien's epsilon-visibility using four custom CUDA kernels.
- Introduced a beta-aware per-vehicle tour upper bound with forbidden-pair cuts to strengthen MIP vehicle routing.
- Extended Zhou and Zeng's GPU parallel-frontier A* search into a 4D space-time domain.

## Limitations

Evaluated primarily on simulated underwater mesh structures up to 7.2M faces under assumptions of limited-FOV cameras and known target geometries.

## Archivist Review

All candidate concepts and open questions from this robotics paper are extremely domain-specific to multi-robot 3D inspection and path finding, and thus lack the cross-cutting reusability required for permanent vault inclusion.

### Rejected Candidates
- [concept] GPU-Resident Multi-Robot 3D Inspection Pipeline (`gpu-resident-multi-robot-inspection-pipeline`) - not_reusable: Too domain-specific to multi-robot underwater structural inspection, making it unlikely to recur across general machine learning literature.
- [open_question] Coupled Location-Routing Viewpoint Selection (`location-routing-viewpoint-selection`) - low_impact: Represents a niche problem formulation in multi-robot view planning rather than a broad foundational bottleneck in machine learning.
- [open_question] CBS-Based MAPF for Dense Fleets (`cbs-mapf-dense-fleets`) - not_reusable: Specific to multi-agent path finding and robotics coordination rather than a general core research direction in ML.
- [open_question] Active Perception and Currents-Aware Planning (`active-perception-currents-aware-planning`) - paper_local: Highly application-specific to underwater robotics and environmental disturbances.

## Links

- [Abstract](https://arxiv.org/abs/2610.26106)
- [PDF](https://arxiv.org/pdf/2610.26106)

