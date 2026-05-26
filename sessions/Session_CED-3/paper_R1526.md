---
title: "Perceiving the Street from Where People Stand: Pedestrian-Centered Multi-View-Factor Mapping via Street View Imagery and Monocular 3D Reconstruction"
authors:
- "Yuye Zhou"
- "Xuanyu Zhou"
- "Lu Liang"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R1526.pdf
---

# Perceiving the Street from Where People Stand: Pedestrian-Centered Multi-View-Factor Mapping via Street View Imagery and Monocular 3D Reconstruction

**Author Information**  
Yuye Zhou<sup>1</sup>, Xuanyu Zhou<sup>2</sup>, Lu Liang<sup>1</sup>


<sup>1</sup> University of California, Berkeley  

<sup>2</sup> Zhejiang University  



## Abstract

Accurate estimation of urban view factors, including Sky View Factor (SVF), Green View Index (GVI), and Building View Factor (BVF), is essential for modeling urban microclimate and pedestrian heat exposure. However, airborne LiDAR remains costly and unavailable in many cities, while street view image (SVI) segmentation approaches inherit systematic bias from vehicle-mounted cameras positioned above pedestrian eye level and offset laterally from sidewalks. This study introduces a pedestrian-centered framework for simultaneously estimating SVF, GVI, and BVF by combining monocular 3D reconstruction with semantic segmentation and sidewalk localization. Using 16,620 SVI panoramas in San Francisco, we apply a Vision Transformer-based monocular geometry model (MoGe) to generate dense, semantically labeled point clouds and reposition virtual viewpoints onto sidewalks through a barrier-detection and offset algorithm. From each repositioned viewpoint, hemispherical projection decomposes the pedestrian's overhead environment into sky, vegetation, and built-form components. SVF estimates show strong agreement with 1 m LiDAR-derived values (R² = 0.90), substantially outperforming segmentation-based baselines. Systematic comparison of driver-centerline and sidewalk viewpoints reveals that vehicle-mounted perspectives overestimate sky exposure by an average of 0.14 while misrepresenting the balance between green and built obstructions experienced by pedestrians. Cross-city validation in Dallas, Los Angeles, and Seattle demonstrates robust performance across diverse street morphologies and vegetation structures. By decomposing the pedestrian hemisphere into three complementary components, the framework supports more targeted applications than SVF alone, from shade-infrastructure planning and heat-equity analysis to walkability assessment and urban canopy monitoring. Our results demonstrate that reliable, multi-component pedestrian-level view factors can be generated at scale without LiDAR, supporting more equitable and climate-resilient street design.



Keywords: Pedestrian microclimate,  Sky View Factor,  Green View Index,  Street view imagery,  3D reconstruction



Semantic Tags: urban microclimate; sky view factor; green view index; street view imagery; monocular 3D reconstruction; pedestrian thermal comfort; urban morphology; heat exposure


```{admonition} Presentation Information
:class: note

**Submission ID:** R1526  
**Session:** [Urban Heat and Thermal Environment - Part 2 ](./Session_CED-3/)  
**Theme:** Climate, Environmental Hazards, and Disaster Risk    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 16:30 – 17:45  
**Venue:** TP-Lv2-SR-E (Room-3/4)  
```