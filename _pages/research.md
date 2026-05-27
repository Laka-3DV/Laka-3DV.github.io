---
permalink: /research/
title: "Research"
author_profile: true
redirect_from:
  - /research.html
---

## Vision

I work toward **geometrically grounded world models** — 3D representations that machines can not only *recover* from raw observations, but *roll forward* in time and *condition on action*.

In the short term, this means tightening the foundations of 3D reconstruction (point cloud registration, scene representation, robust geometry). In the longer term, it means giving those representations **dynamics** — so a machine can not only see a scene, but predict how it evolves.

## Current Foundations

My published work centers on three building blocks of a usable 3D world:

- **Robust geometry & estimation.** Real sensors produce noisy, partial, contaminated data. [**TurboReg**](https://github.com/Laka-3DV/TurboReg) (ICCV 2025) and [**HeMoRa**](https://github.com/Laka-3DV/HeMoRa) (CVPR 2025) push robust estimators for point cloud registration onto a faster, more hardware-aware footing.
- **Structured matching.** Correspondences across views are the connective tissue of any 3D pipeline. [**ML-SemReg**](https://github.com/Laka-3DV/ML-SemReg) (ECCV 2024) shows that adding lightweight semantic structure can sharply lift match recall — without any learning.
- **Scene-grounded perception.** With [**ULF-Loc**](https://github.com/Cyril-gyd/ULF-Loc) (CVPR 2026 Highlight), I started moving from "geometry under registration" to "geometry under representation" — localizing cameras against 3D Gaussian Splatting scenes via unbiased landmark features.

## Where It's Going

Three threads I want to follow during my PhD:

1. **From static to dynamic** — recovering not just frozen scenes but how they move. Dynamic 3DGS, deformable scene representations, and 4D world models.
2. **From observation to prediction** — modeling temporal evolution and action-conditioned rollouts on top of geometric representations.
3. **From perception to use** — testing world models where they actually matter: robotic manipulation, autonomous driving, embodied agents.

The bet I am making: **strong geometric grounding will be a feature, not a constraint, for the next generation of world models** — especially in robotics and autonomous driving, where ungrounded generation cannot be trusted.

## Selected Papers

For the full list, see [publications on the home page](/#-publications). Highlights:

- **ULF-Loc** — *Unbiased Landmark Feature for Robust Visual Localization with 3D Gaussian Splatting* — CVPR 2026 **Highlight**.
- **TurboReg** — *TurboClique for Robust and Efficient Point Cloud Registration* — ICCV 2025.
- **HeMoRa** — *Unsupervised Heuristic Consensus Sampling for Robust Point Cloud Registration* — CVPR 2025.
- **ML-SemReg** — *Boosting Point Cloud Registration with Multi-level Semantic Consistency* — ECCV 2024.

---

*Always open to collaboration — [shaochengyan@whu.edu.cn](mailto:shaochengyan@whu.edu.cn).*
