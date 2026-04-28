---
title: "An Enhanced Spatiotemporal Fusion Model toward Reliable Global-Scale Seamless Remote Sensing Data Reconstruction"
authors:
- "Dizhou Guo"

---

# An Enhanced Spatiotemporal Fusion Model toward Reliable Global-Scale Seamless Remote Sensing Data Reconstruction

**Author Information**  
Dizhou Guo<sup>1</sup>


<sup>1</sup> Chang’an University  



## Abstract

Generating seamless, high-resolution global data cubes is a cornerstone of remote sensing big data analytics. While the recently proposed ROBust OpTimization-based (ROBOT) fusion model has attracted wide attention for its efficiency, accuracy, and simple parameterization, and has been successfully utilized for the reconstruction of seamless global remote sensing big data cubes, it still suffers from notable limitations. Specifically, its sliding-window strategy tends to induce block artifacts, while cloud contamination in auxiliary images further impairs the quality and reliability of reconstructed results. To address these limitations, this study presents an enhanced variant of the ROBOT model, namely EROBOT. Through the replacement of fixed rectangular patches with spectrally and spatially homogeneous segments, EROBOT significantly mitigates block artifacts and achieves superior preservation of spatial structural details. Furthermore, prior to the fusion process, an adaptive gap-filling strategy is applied to the temporally closest auxiliary images, and a low-quality information detection module is integrated to filter out unreliable cloud-contaminated data during the regression and residual allocation phases, thereby boosting the model’s reliability under cloud-contaminated conditions. Experimental results across diverse landscapes reveal that EROBOT consistently outperforms ROBOT, OL-HSTFM, and FSDAF under both cloud-free and cloud-contaminated scenarios. Its efficiency is 21.2 times and 2.3 times that of FSDAF and OL-HSTFM, respectively. Notably, the accuracy gap widens in favor of EROBOT as auxiliary data volume increases, making it a highly scalable and reliable solution for large-scale geospatial big data processing and application.



Keywords: Spatiotemporal fusion,  Seamless data cube,  Remote sensing data reconstruction



```{admonition} Presentation Information
:class: note

**Submission ID:** 5112  
**Session:** [Remote Sensing for Detection Remote Sensing Object](./Session_D7/) 
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30
**Venue:** room 7
```