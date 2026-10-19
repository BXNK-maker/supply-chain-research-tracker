---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem"
description: "The paper introduces RELAGRAM, a recursive latent graph model that applies latent recursion via a compact transformer to the capacitated vehicle routing problem (CVRP). By recurrently updating edge token representations and employing an autoregressive decoder, RELAGRAM achieves competitive optimality gaps on CVRP-100 and demonstrates zero-shot generalization to larger CVRP-500 and CVRP-1000 instances."
resource: "https://arxiv.org/abs/2610.15106"
tags:
  - "vehicle-routing-problem"
  - "neural-routing-solver"
  - "combinatorial-optimization"
timestamp: "2026-10-19T10:26:58Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Vladimir Kirill Bickov"
  - literal: "Neil Yorke-Smith"
issued:
  date-parts:
    - [2026, 10, 10]

# Domain-specific custom fields
paper_id: "2610.15106"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "relagram"
    description: "A recursive latent graph model that repeatedly processes internal representations through a compact transformer for combinatorial optimization on graphs."
datasets:
  []
open_questions:
  - name: "reinforcement-learning-signal-shaping-for-latent-recursion"
    description: "Investigate and engineer more effective reinforcement learning training signals, such as dense or alternative reward formulations, to better support latent-recursive architectures in graph combinatorial optimization where intermediate latent states receive only indirect supervision."
skill: "GeneralMLSkill"
processed_at: "2026-10-19T10:26:58Z"
created_at: "2026-10-19T10:26:58Z"
---

# RELAGRAM: Recursive Latent Graph Model for the Capacitated Vehicle Routing Problem

**Authors**: Vladimir Kirill Bickov, Neil Yorke-Smith
**Date**: 2026-10-10
**Paper ID**: [openalex:2610.15106](https://arxiv.org/abs/2610.15106)

## Summary

The paper introduces RELAGRAM, a recursive latent graph model that applies latent recursion via a compact transformer to the capacitated vehicle routing problem (CVRP). By recurrently updating edge token representations and employing an autoregressive decoder, RELAGRAM achieves competitive optimality gaps on CVRP-100 and demonstrates zero-shot generalization to larger CVRP-500 and CVRP-1000 instances.

## Key Contributions

- Introduced RELAGRAM, bringing latent recursion via a compact recurrent transformer to graph combinatorial optimization.
- Achieved competitive performance on CVRP-100 instances with optimality gaps of 13.4% (greedy), 9.8% (symmetry augmentation), and 8.3% (256-candidate search) using a lightweight 0.53M-parameter model.
- Demonstrated zero-shot generalization from training solely on CVRP-100 to larger scale instances (CVRP-500 and CVRP-1000).

## Limitations

Evaluated primarily on CVRP instances; zero-shot generalization degrades as problem scale increases to 500 and 1000 nodes.

## Open Questions & Future Work

- [[reinforcement-learning-signal-shaping-for-latent-recursion]]

## Key Concepts

- [[relagram]]: A recursive latent graph model that repeatedly processes internal representations through a compact transformer for combinatorial optimization on graphs.

## Archivist Review

Approved the core RELAGRAM concept representing latent recursion applied to graph combinatorial optimization, and mapped the open question to the existing vault canonical slug for reinforcement learning signal shaping in latent recursion. Rejected the general CVRP benchmark family as a dataset note.

### Approved Concepts
- RELAGRAM: Central novel framework of the paper, introducing latent recursion to neural routing for the capacitated vehicle routing problem.

### Approved Open Questions
- Reinforcement Learning Signals for Latent Recursion: Latent recursion relies heavily on internal state updates, but standard sparse reinforcement learning signals make it difficult to effectively train the intermediate latent dynamics without explicit supervision.

### Rejected Candidates
- [dataset] CVRP (`cvpr`) - not_novel: Standard benchmark problem family rather than a novel standalone dataset entity.

## Links

- [Abstract](https://arxiv.org/abs/2610.15106)
- [PDF](https://arxiv.org/pdf/2610.15106)

