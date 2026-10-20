---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Supermarket Product Detection and Recognition: Utilizing Deep Learning with Rectified Imagery"
description: "This paper investigates the challenges of product detection and recognition in densely packed supermarket shelves affected by angle variations during image capture. To address this, the authors combine traditional Hough transform and homography estimation techniques to rectify angled shelf images before feeding them into object detection models. Extensive experiments show that image rectification improves detection accuracy, while also revealing performance boundaries related to capture angle and object density. Additionally, a new dataset is introduced to evaluate these rectification scenarios."
resource: "https://arxiv.org/abs/2610.08126"
tags:
  - "object-detection"
  - "retail-automation"
timestamp: "2026-10-20T09:46:05Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Mayank Sah"
  - literal: "Jimson Mathew"
issued:
  date-parts:
    - [2026, 10, 6]

# Domain-specific custom fields
paper_id: "2610.08126"
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
processed_at: "2026-10-20T09:46:05Z"
created_at: "2026-10-20T09:46:05Z"
---

# Supermarket Product Detection and Recognition: Utilizing Deep Learning with Rectified Imagery

**Authors**: Mayank Sah, Jimson Mathew
**Date**: 2026-10-06
**Paper ID**: [openalex:2610.08126](https://arxiv.org/abs/2610.08126)

## Summary

This paper investigates the challenges of product detection and recognition in densely packed supermarket shelves affected by angle variations during image capture. To address this, the authors combine traditional Hough transform and homography estimation techniques to rectify angled shelf images before feeding them into object detection models. Extensive experiments show that image rectification improves detection accuracy, while also revealing performance boundaries related to capture angle and object density. Additionally, a new dataset is introduced to evaluate these rectification scenarios.

## Key Contributions

- Supplements object detection models with traditional Hough transform and homography estimation for supermarket product recognition.
- Demonstrates that image rectification of angled shelf images improves grocery product detection accuracy under specific angle variations.
- Highlights critical limitations of image rectification with respect to capture angle thresholds and object density per image.
- Introduces a new dataset designed to test the effects of image rectification across varying angles and object densities.

## Limitations

Rectification effectiveness is limited by extreme capture angles and high object density within a single image.

## Archivist Review

Applied strict selection criteria, rejecting the application-specific open question about supermarket product rectification as having low cross-domain impact. No concepts or datasets were proposed or approved.

### Rejected Candidates
- [open_question] Rectification in Dense Scenes (`dense-scene-image-rectification`) - low_impact: Too application-specific to supermarket product detection and retail automation to warrant a permanent vault note.

## Links

- [Abstract](https://arxiv.org/abs/2610.08126)
- [PDF](https://arxiv.org/pdf/2610.08126)

