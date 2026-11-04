---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Carbon-Aware Electric Vehicle Routing Problem with Decision-Focused Learning"
description: "This paper studies a Carbon-Aware Electric Vehicle Routing Problem that accounts for time-varying grid carbon intensity during vehicle routing, charging, and waiting. To address the dependence of these decisions on carbon forecasts, the authors propose a decision-focused learning approach that trains a linear carbon intensity predictor using approximate SPO+ directions with a Large Neighborhood Search solver. Experiments on realistic Germany-based instances show that the approach substantially reduces realized emissions and total costs compared to conventional prediction-focused learning and carbon-blind optimization."
resource: "https://arxiv.org/abs/2610.39645"
tags:
  - "decarbonization"
  - "fleet-scheduling"
  - "vehicle-routing-problem"
  - "time-series"
timestamp: "2026-11-04T12:46:52Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jaume Reixach"
  - literal: "Wanru Chen"
  - literal: "Jiaming Wu"
  - literal: "Balaźs Kulcsár"
issued:
  date-parts:
    - [2026, 10, 29]

# Domain-specific custom fields
paper_id: "2610.39645"
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
processed_at: "2026-11-04T12:46:52Z"
created_at: "2026-11-04T12:46:52Z"
---

# Carbon-Aware Electric Vehicle Routing Problem with Decision-Focused Learning

**Authors**: Jaume Reixach, Wanru Chen, Jiaming Wu, Balaźs Kulcsár
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.39645](https://arxiv.org/abs/2610.39645)

## Summary

This paper studies a Carbon-Aware Electric Vehicle Routing Problem that accounts for time-varying grid carbon intensity during vehicle routing, charging, and waiting. To address the dependence of these decisions on carbon forecasts, the authors propose a decision-focused learning approach that trains a linear carbon intensity predictor using approximate SPO+ directions with a Large Neighborhood Search solver. Experiments on realistic Germany-based instances show that the approach substantially reduces realized emissions and total costs compared to conventional prediction-focused learning and carbon-blind optimization.

## Key Contributions

- Formulated a Carbon-Aware Electric Vehicle Routing Problem that integrates time-varying grid carbon intensity into routing, charging, and waiting decisions.
- Proposed a decision-focused learning approach using approximate SPO+ directions to train a linear carbon intensity predictor solver-aware.
- Demonstrated that explicitly accounting for charging emissions reduces realized emissions by 28.76% on average compared to carbon-blind optimization.
- Showed that decision-focused training reduces realized total cost by 2.30% compared to prediction-focused learning while improving performance on 75.5% of test instances.

## Limitations

Higher non-carbon operating costs incurred when prioritizing lower carbon intensity charging periods.

## Archivist Review

Applied strict evaluation criteria: no concepts or datasets were proposed, and the single open question regarding decision-focused training computational cost is a known broader challenge overlapping with existing optimization bottlenecks in the vault.

### Rejected Candidates
- [open_question] Scaling Decision-Focused Training for Routing (`computational-cost-decision-focused-training`) - not_novel: While practical compute limits are discussed, scaling decision-focused training is a broad existing theme rather than a distinct new unresolved bottleneck unique enough for a permanent standalone note.

## Links

- [Abstract](https://arxiv.org/abs/2610.39645)
- [PDF](https://arxiv.org/pdf/2610.39645)

