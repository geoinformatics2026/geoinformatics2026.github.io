---
title: "A lightweight Prior-Guided Dual-branch Network for building extraction from optical imagery"
authors:
- "Yuqi Chen"
- "Yilan Liao"
- "Hongyan Ren"
- "An Zhang"

---

# A lightweight Prior-Guided Dual-branch Network for building extraction from optical imagery

**Author Information**  
Yuqi Chen<sup>1</sup>, Yilan Liao<sup>1</sup>, Hongyan Ren<sup>1</sup>, An Zhang<sup>1</sup>


<sup>1</sup> Institute of Geographic Sciences and Natural Resources Research, Chinese Academy of Sciences  



## Abstract

Accurate building extraction from high-resolution optical remote sensing imagery is a fundamental prerequisite for rapid disaster assessment, urban planning, and emergency response. However, robust interpretation from single-source optical data remains a significant challenge. This is primarily due to complex background interference, spectral confusion between building roofs and impervious surfaces, varying illumination conditions, and severe building shadows that obscure boundary delineations. While current mainstream approaches frequently employ dense multi-modal fusion pipelines to mitigate these issues, they are severely hindered by strict cross-modal registration requirements, heterogeneous data misalignment, and immense computational redundancy. These drawbacks heavily restrict their deployment in time-sensitive scenarios.  To address these critical bottlenecks, we propose a lightweight Prior-Guided Dual-branch Network(PGDnet) framework designed for highly efficient building footprint extraction. Instead of relying on conventional heavy data fusion, PGDnet uniquely integrates explicit topographic priors. Specifically, it leverages elevation information derived from a Digital Surface Model (DSM), alongside corresponding slope and curvature features. By injecting these targeted geometric constraints, the network effectively compensates for optical occlusions and shadow-induced artifacts. The PGDnet architecture explicitly decouples the feature extraction of the raw optical imagery and the topographic priors using two parallel, computationally lightweight encoding branches. Experimental evaluations on the high-resolution Potsdam dataset demonstrate the outstanding performance of our approach, yielding a Mean Pixel Accuracy (MPA) of 92.0% and a Mean Intersection over Union (mIoU) of 79.0%. These results confirm that PGDnet not only delivers highly competitive segmentation precision but also significantly reduces the computational burden, highlighting its immense practical potential for rapid, large-scale urban monitoring and edge-computing-based disaster relief applications.



Keywords: Optical imagery,  Building extraction,  Prior knowledge



```{admonition} Presentation Information
:class: note

**Submission ID:** 4861  
**Session:** [Spectral Extraction Features Branch](./Session_C9/) 
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 16:30 – 17:45
**Venue:** room 9
```