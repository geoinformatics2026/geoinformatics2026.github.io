---
title: "Heterogeneous Parallel Spatial-Temporal Savitzky-Golay (HP-STSG) Method: Reconstructing NDVI and EVI2 Time Series with High Performance"
authors:
- "Xue Yang"
- "Qingfeng Guan"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R4421.pdf
---

# Heterogeneous Parallel Spatial-Temporal Savitzky-Golay (HP-STSG) Method: Reconstructing NDVI and EVI2 Time Series with High Performance

**Author Information**  
Xue Yang<sup>1</sup>, Qingfeng Guan<sup>2</sup>


<sup>1</sup> China University of Petroleum  

<sup>2</sup> China University of Geosciences  



## Abstract

High-quality vegetation index time series is crucial for a lot of ecological applications. However, satellite-acquired vegetation index time series products are contaminated by clouds and snow cover. The proposed reconstruction methods still have three deficiencies: First, most of proposed reconstruction algorithms are based on the assumption that there is no continuous missing data, and reconstruct poor products in the high-resolution images. Second, the proposed algorithms largely depend on the quality flags of the NDVI time-series data, and inaccurate quality flags yield misleading final results. Third, the proposed algorithms usually ignore the inter-annual differences of vegetation in the process of reconstructing, making it hard to recover the real climatic changes of vegetation when dealing with long time-series data. Fourth, existing algorithms are seriously time-consuming and cannot handle large-scale long time-series reconstruction. To address the aforementioned issues, we proposes a heterogeneous parallel Spatial-Temporal Savitzky-Golay (HP-STSG) method for reconstructing the NDVI and EVI2 data with both low and high spatial-temporal resolutions. First, HP-STSG employs the similarity of time series itself to ascertain the data quality. Then, HP-STSG uses the shift-offset method to complete the time series and estimates the spatial-temporal similarity, integrating vegetation spatial-temporal characteristics and annual difference, facilitating the high-precision reconstruction of high-resolution vegetation index data. And HP-STSG accelerates the reconstruction of vegetation indexes time-series data for a heterogeneous environment of CPU/GPUs. The experiments demonstrate that the removal of VI pollution values and the fusion of annual difference, effectively solve the problem of poor reconstruction accuracy. And heterogeneous parallel computing making HP-STSG able to reconstruct vegetation index with high-efficiency. HP-STSG is capable of automatically assessing data quality and finely integrating the spatial-temporal attributes and annual difference of vegetation. And HP-STSG is highly scalable and adaptable to a multiple of VI datasets.



Keywords: time series data reconstruction,  vegetation index,  heterogeneous parallelism



Semantic Tags: vegetation index time series reconstruction; NDVI; EVI2; heterogeneous parallelism; cloud contamination; satellite data quality; temporal reconstruction


```{admonition} Presentation Information
:class: note

**Submission ID:** R4421  
**Session:** [Land Cover Mapping and Satellite Time-Series Analysis ](./Session_REE-7/)  
**Theme:** Remote Sensing, Earth Observation, and Environmental Monitoring    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 09:00 – 10:30  
**Venue:** SRC-Lv1-SR-B (Room-3/4)  
```