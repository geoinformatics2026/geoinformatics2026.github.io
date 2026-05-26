---
title: "Reconstructing 10-m Surface Reflectance Dataset from 1990 to 2025 via Semantic-Guided Super-Resolution and Unsupervised Domain Adaption"
authors:
- "Xiaoyu Zheng"
- "Bowen Cai"
- "Siyuan Wang"
- "Yuankun Wang"
- "Zhenfeng Shao"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R2198.pdf
---

# Reconstructing 10-m Surface Reflectance Dataset from 1990 to 2025 via Semantic-Guided Super-Resolution and Unsupervised Domain Adaption

**Author Information**  
Xiaoyu Zheng<sup>1</sup>, Bowen Cai<sup>1</sup>, Siyuan Wang<sup>1</sup>, Yuankun Wang<sup>2</sup>, Zhenfeng Shao<sup>1</sup>


<sup>1</sup> Wuhan University  

<sup>2</sup> University of Illinois Urbana-Champaign  



## Abstract

High-resolution and long-term satellite image time series are essential for applications such as urban monitoring, climate analysis, and agriculture. Landsat provides an unparalleled multi-decadal record at coarse spatial resolution, while Sentinel-2 offers finer spatial detail over a much shorter time span. However, no existing archival dataset simultaneously delivers high spatial resolution, long temporal coverage, and consistent multispectral fidelity. To bridge this gap, we propose a historical Landsat super-resolution framework based on unsupervised domain adaptation, named HistorySR. Specifically, we design a Low-Resolution Semantic-Guided Cross-Sensor Super-Resolution network (SG-SR). By incorporating frequency decoupling and low-resolution semantic modulation module (LSMM), SG-SR achieves the class-specific spatial heterogeneity modulation and enhancement. To address the lack of historical high-resolution ground truth, we introduce a Texture-aware Feature Alignment (TFA) strategy during the unsupervised domain adaptation. This mechanism effectively mitigates error accumulation and forces the recovery of structural information from historical noise. Leveraging this framework, we construct a 10-m multi-band surface reflectance dataset covering China's three major urban agglomerations from 1990 to 2025. Extensive comparative experiments demonstrate that our framework outperforms state-of-the-art approaches, achieving improvements in the Learned Perceptual Image Patch Similarity (LPIPS) metric ranging from 28.42% to 59.77%. The reconstructed imagery maintains superior radiometric fidelity and structural consistency, holding substantial potential for ecological utility and fine-grained urban renewal monitoring.



Keywords: Satellite Image Time Series,  Historical reconstruction,  Landsat,  Super resolution,  Land cover guided,  Unsupervised domain adaptation



Semantic Tags: satellite image time series; historical reconstruction; Landsat; super-resolution; land cover guided; unsupervised domain adaptation; earth observation; multispectral imagery


```{admonition} Presentation Information
:class: note

**Submission ID:** R2198  
**Session:** [Land Cover Mapping and Satellite Time-Series Analysis ](./Session_REE-7/)  
**Theme:** Remote Sensing, Earth Observation, and Environmental Monitoring    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 09:00 – 10:30  
**Venue:** SRC-Lv1-SR-B (Room-3/4)  
```