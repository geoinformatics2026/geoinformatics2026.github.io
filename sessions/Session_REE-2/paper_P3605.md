---
title: "MMCA-SAM: Multimodal Cross-Attention SAM for Landslide Segmentation with Topographic Guidance"
authors:
- "Jiaxin Shi"
- "Shaoming Pan"
- "Qingxiang Meng"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_P3605.pdf
---

# MMCA-SAM: Multimodal Cross-Attention SAM for Landslide Segmentation with Topographic Guidance

**Author Information**  
Jiaxin Shi<sup>1</sup>, Shaoming Pan<sup>1</sup>, Qingxiang Meng<sup>2</sup>


<sup>1</sup> State Key Laboratory of Information Engineering in Surveying, Mapping and Remote Sensing, Wuhan University  

<sup>2</sup> School of Remote Sensing and Information Engineering, Wuhan University  



## Abstract

Landslides are a common, destructive form of geological disaster that poses a threat to both infrastructure and human life. The Segment Anything Model (SAM) is a strong segmentation model, but it still has difficulty with the unclear boundaries and complex terrain that are typical of landslides. Most existing multimodal models also have difficulty in deeply fusing Digital Elevation Models (DEM) and optical images. To address these issues, we introduce MMCA-SAM, a terrain-aware multimodal segmentation model. MMCA-SAM incorporates a Cross-Attention Fusion Module (CAFM) to align RGB semantics with terrain geometry. It also incorporates Atrous Spatial Pyramid Pooling (ASPP) and a decoder with Coordinate Attention (CA) to improve the resolution of unclear boundaries. Experiments on the Bijie and Landslide4Sense datasets demonstrate that MMCA-SAM achieves better performance than existing semantic segmentation models and SOTA foundation models. Analysis also shows that topographic constraints lead to a significant improvement in landslide spatial localization accuracy. This method, aiming to obtain accurate boundary geometry, provides reliable spatial assistance for accurate earthwork estimation and damage assessment after a disaster.



Keywords: component, Semantic segmentation, landslide detection, multimodal fusion, Vision Foundation Models, cross-attention



Semantic Tags: landslide segmentation; multimodal fusion; Segment Anything Model; cross-attention; digital elevation model; optical imagery; terrain-aware deep learning; geological disaster; remote sensing


```{admonition} Presentation Information
:class: note

**Submission ID:** P3605  
**Session:** [InSAR and Geological Hazard Monitoring ](./Session_REE-2/)  
**Theme:** Remote Sensing, Earth Observation, and Environmental Monitoring    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 14:45 – 16:15  
**Venue:** SRC-Lv1-SR-B (Room-3/4)  
```