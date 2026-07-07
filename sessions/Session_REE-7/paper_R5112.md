---
title: "An Enhanced Spatiotemporal Fusion Model toward Reliable Global-Scale Seamless Remote Sensing Data Reconstruction"
authors:
- "Dizhou Guo"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
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

**Submission ID:** R5112  
**Session:** [Land Cover Mapping and Satellite Time-Series Analysis](./Session_REE-7/)  
**Theme:** Remote Sensing, Earth Obs. \& Env. Monitoring    
**Date:** Day 3, 22 July (Wednesday)  
**Time:** 09:00 – 10:30  
**Venue:** Stephen Riady Centre-01-Seminar Room 3 & 4 (SR-B)  
```