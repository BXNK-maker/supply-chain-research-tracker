---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings"
description: "Autonomous indoor delivery in large-scale buildings requires coordinated planning across building, floor, and room levels while respecting privacy constraints and physical execution limits. This paper introduces a hierarchical Building-Floor-Room framework that decomposes the routing problem and models a building-aware extension of the capacitated vehicle routing problem (CVRP) to handle inter-floor connectivity and privacy-sensitive areas. The approach integrates hardware design for non-interactive delivery with closed-loop mapping, localization, and navigation systems. Validated on a real multi-sensor robotic platform, the framework demonstrates efficient multi-floor delivery and path rationality."
resource: "https://arxiv.org/abs/2610.21361"
tags:
  - "vehicle-routing-problem"
  - "machine-learning"
timestamp: "2026-10-19T10:27:56Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Xu Xiaoji"
  - literal: "Luo Rui"
  - literal: "Chen Jinhua"
  - literal: "Xiang Changying"
  - literal: "Zhang Leihan"
  - literal: "Zhongyuan Liao"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21361"
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
processed_at: "2026-10-19T10:27:56Z"
created_at: "2026-10-19T10:27:56Z"
---

# Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings

**Authors**: Xu Xiaoji, Luo Rui, Chen Jinhua, Xiang Changying, Zhang Leihan, Zhongyuan Liao
**Date**: 2026-10-15
**Paper ID**: [openalex:2610.21361](https://arxiv.org/abs/2610.21361)

## Summary

Autonomous indoor delivery in large-scale buildings requires coordinated planning across building, floor, and room levels while respecting privacy constraints and physical execution limits. This paper introduces a hierarchical Building-Floor-Room framework that decomposes the routing problem and models a building-aware extension of the capacitated vehicle routing problem (CVRP) to handle inter-floor connectivity and privacy-sensitive areas. The approach integrates hardware design for non-interactive delivery with closed-loop mapping, localization, and navigation systems. Validated on a real multi-sensor robotic platform, the framework demonstrates efficient multi-floor delivery and path rationality.

## Key Contributions

- Proposes a hierarchical Building-Floor-Room framework that decomposes multi-level indoor delivery into building, floor, and room abstractions to reduce optimization complexity.
- Formulates a building-aware extension of the capacitated vehicle routing problem (CVRP) modeling inter-building connectivity, room-level access constraints, and privacy-sensitive areas.
- Introduces a hardware design for non-interactive, privacy-preserving delivery supported by a closed-loop mapping, localization, and navigation system.
- Validates the framework on a real multi-sensor robotic platform, demonstrating reliable multi-floor delivery with improved path rationality and efficiency.

## Archivist Review

The submitted concept is a paper-local system framework for indoor delivery, and the open question heavily duplicates existing multi-robot routing and coordination challenges already tracked in the vault. Both candidates were consequently rejected to maintain vault selectivity and avoid redundancy.

### Rejected Candidates
- [concept] Building-Floor-Room Framework (`building-floor-room-framework`) - paper_local: This is a domain-specific system architecture and application-level routing abstraction for indoor delivery robots rather than a reusable core ML methodology or architectural pattern.
- [open_question] Multi-Robot Cooperative Hierarchical Routing (`multi-robot-hierarchical-cvrp-optimization`) - duplicate_existing: This is a standard application-level extension combining multi-robot coordination with hierarchical CVRP, overlapping significantly with existing routing and multi-robot open questions in the vault.

## Links

- [Abstract](https://arxiv.org/abs/2610.21361)
- [PDF](https://arxiv.org/pdf/2610.21361)

