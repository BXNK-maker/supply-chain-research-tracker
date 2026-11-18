---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Matrix-Based Ant Colony Search with Batched Decoding for Hierarchical Replenishment Routing: A Stylized Case Study Based on Korean City Data"
description: "The authors study a single-vehicle replenishment-routing problem on a 100-node hierarchical network derived from Korean city data, where cities act as both demand and supply points under capacity and stop constraints. They propose a matrix-based ant colony search with batched local search decoding, showing competitive performance against genetic algorithms and MAX-MIN ant systems. Ablation studies reveal that batched local search is the dominant factor in solution quality, while load-aware transition factors yield negligible gains."
resource: "https://arxiv.org/abs/2611.15338"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-11-18T13:39:32Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jun Zhang"
  - literal: "Weijie Yu"
  - literal: "Qian Tong"
  - literal: "Eui Jeong Kwak"
  - literal: "Sang-Woon Jeon"
  - literal: "Hua Ding"
  - literal: "Qijia Jiang"
  - literal: "Hu Jin"
  - literal: "Haewoon Nam"
  - literal: "Changjun Zhou"
issued:
  date-parts:
    - [2026, 11, 11]

# Domain-specific custom fields
paper_id: "2611.15338"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "matrix-based-ant-colony-search"
    description: "An ant colony optimization variant that maintains colony states in arrays and evaluates local search candidate moves in batches."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-18T13:39:32Z"
created_at: "2026-11-18T13:39:32Z"
---

# Matrix-Based Ant Colony Search with Batched Decoding for Hierarchical Replenishment Routing: A Stylized Case Study Based on Korean City Data

**Authors**: Jun Zhang, Weijie Yu, Qian Tong, Eui Jeong Kwak, Sang-Woon Jeon, Hua Ding, Qijia Jiang, Hu Jin, Haewoon Nam, Changjun Zhou
**Date**: 2026-11-11
**Paper ID**: [openalex:2611.15338](https://arxiv.org/abs/2611.15338)

## Summary

The authors study a single-vehicle replenishment-routing problem on a 100-node hierarchical network derived from Korean city data, where cities act as both demand and supply points under capacity and stop constraints. They propose a matrix-based ant colony search with batched local search decoding, showing competitive performance against genetic algorithms and MAX-MIN ant systems. Ablation studies reveal that batched local search is the dominant factor in solution quality, while load-aware transition factors yield negligible gains.

## Key Contributions

- Introduces a matrix-based ant colony search with batched decoding for hierarchical replenishment routing.
- Constructs a 100-node benchmark based on Korean population and geographic data spanning 10 hierarchical levels.
- Demonstrates through ablation that batch local search is the primary contributor to solution quality, performing comparably to a genetic algorithm and outperforming MAX-MIN ant system.

## Limitations

Evaluated on a stylized 100-node single-vehicle replenishment-routing benchmark with fixed parameters and heuristics.

## Key Concepts

- [[matrix-based-ant-colony-search]]: An ant colony optimization variant that maintains colony states in arrays and evaluates local search candidate moves in batches.

## Archivist Review

Approved the matrix-based ant colony search concept as a reusable combinatorial optimization technique involving array-based colony states and batched local search decoding. No datasets or open questions met the strict standalone criteria.

### Approved Concepts
- Matrix-Based Ant Colony Search: Core optimization methodology proposed and evaluated for the hierarchical replenishment routing problem.

## Links

- [Abstract](https://arxiv.org/abs/2611.15338)
- [PDF](https://arxiv.org/pdf/2611.15338)

