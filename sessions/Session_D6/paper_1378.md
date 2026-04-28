---
title: "A Synergistic Approach for High-Precision Lake Turbidity Retrieval Using ICESat-2 and Sentinel-2 Data"
authors:
- "Rong He"
- "Heng Chen"
- "Guanghui Zhu"

---

# A Synergistic Approach for High-Precision Lake Turbidity Retrieval Using ICESat-2 and Sentinel-2 Data

**Author Information**  
Rong He<sup>1</sup>, Heng Chen<sup>1</sup>, Guanghui Zhu<sup>1</sup>


<sup>1</sup> Henan Polytechnic University  



## Abstract

Abstract Accurate monitoring of lake turbidity is challenging using single-sensor remote sensing. This study proposes a high-precision framework by synergistically using ICESat-2 LiDAR and Sentinel-2 imagery, using Lake Erie as a case study. Surface water signal photons were extracted from ICESat-2 ATL03 data using an adaptive pruned quadtree denoising algorithm and Otsu thresholding. Photon distribution features-penetration depth, density, and attenuation metrics were quantified along 500-meter segments. A machine learning model inverted turbidity from these features with an RMSE of 2.67 NTU. To overcome ICESat-2' linear sampling limitation, temporally matched Sentinel-2 reflectance data were integrated. ICESat-2-derived turbidity acted as "virtual buoy" observations to calibrate Sentinel-2 spectral features. A feature-level fusion model with Bayesian optimization transferred vertical photon-profile information into two-dimensional spatial fields. The fused model achieved an RMSE of 2.95 NTU, a 39% improvement over the Sentinel-2-only model (RMSE = 4.87 NTU), and significantly outperformed traditional optical empirical algorithms. This research demonstrates the potential of combining spaceborne LiDAR with multispectral data for enhanced large- scale water quality monitoring.



Keywords: ICESat-2,  Sentinel-2,  Turbidity Retrieval,  Random Forest,  Water Quality



```{admonition} Presentation Information
:class: note

**Submission ID:** 1378  
**Session:** [Cropland Agricultural Sentinel Stress](./Session_D6/) 
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30
**Venue:** room 6
```