---
title: "HistorySR: Reconstructing 10-m Landsat Imagery from 1990 to 2025 via Semantic-Guided Super-Resolution and Unsupervised Domain Adaptation"
authors:
- "Xiaoyu Zheng"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_S0002.pdf
---

# HistorySR: Reconstructing 10-m Landsat Imagery from 1990 to 2025 via Semantic-Guided Super-Resolution and Unsupervised Domain Adaptation

**Author Information**  
Xiaoyu Zheng<sup>1</sup>


<sup>1</sup> Wuhan University  



## Abstract

Long-term multispectral Satellite Image Time Series (SITS) are essential for applications such as urban monitoring, climate analysis, and agriculture. Landsat provides an unparalleled multi-decadal global record, serving as the foundation for continuous Earth observation. To meet the growing demand for fine-scale historical insights, enhancing the spatial resolution of this extensive archive is highly valuable. This study proposes a historical Landsat imagery super-resolution framework based on unsupervised domain adaptation (HistorySR). Specifically, we design a Low-Resolution Semantic-Guided Cross-Sensor Super-Resolution (SG-SR) network. By incorporating frequency decoupling and a low-resolution semantic modulation module (LSMM), SG-SR achieves class-specific spatial heterogeneity modulation and enhancement. To mitigate error accumulation during domain adaptation, a Texture-aware Feature Alignment (TFA) strategy is introduced to recover structural information from historical noise. Leveraging this framework, we construct a 10-m multi-band Landsat imagery dataset covering three major urban agglomerations from 1990 to 2025 in China (HiSR-Landsat10m-v1). Extensive comparative experiments on real historical Landsat archives demonstrate that HistorySR outperforms state-of-the-art methods, improving the Learned Perceptual Image Patch Similarity by 40.62% and Cross-Correlation by 11.03%. Downstream applications demonstrate that HiSR-Landsat10m-v1 improves the NDVI consistency with Sentinel-2, reducing the mean absolute error by 18.15% compared to the original Landsat and effectively captures the urban renewal trajectories.



Keywords: Satellite Image Time Series, Historical reconstruction, Landsat, Super resolution, Land cover guided, Unsupervised domain adaptation



Semantic Tags: satellite image time series; Landsat super-resolution; unsupervised domain adaptation; historical reconstruction; multispectral imagery; earth observation; HistorySR; semantic-guided


```{admonition} Presentation Information
:class: note

**Submission ID:** S0002  
**Session:** [Land Cover Mapping and Satellite Time-Series Analysis ](./Session_REE-7/)  
**Theme:** Remote Sensing, Earth Observation, and Environmental Monitoring    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 09:00 – 10:30  
**Venue:** SRC-Lv1-SR-B (Room-3/4)  
```