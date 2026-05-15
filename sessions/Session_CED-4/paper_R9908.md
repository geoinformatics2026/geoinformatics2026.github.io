---
title: "GConvAttnLSTM: A Graph-Based Attention LSTM for Multi-Source Satellite Precipitation Fusion over the Yangtze River Basin"
authors:
- "Gaoyun Shen"
- "Lin Fu"
- "Lei Wang"

---

# GConvAttnLSTM: A Graph-Based Attention LSTM for Multi-Source Satellite Precipitation Fusion over the Yangtze River Basin

**Author Information**  
Gaoyun Shen<sup>1</sup>, Lin Fu<sup>1</sup>, Lei Wang<sup>1</sup>


<sup>1</sup> Southwest Petroleum University  



## Abstract

Accurate high-resolution precipitation estimates are essential for flood forecasting, water-resources management, and climate-risk assessment, yet remain challenging in large, topographically complex basins due to sparse gauges and satellite product biases. This study presents a topography-aware deep spatiotemporal fusion framework, GConvAttnLSTM, for integrating multiple satellite precipitation products in the Yangtze River Basin (YRB). The framework fuses three widely used datasets—PERSIANN-CDR, MSWEP, and CHIRPS—whose distinct retrieval principles help reduce shared error modes. Ground-based observations from 198 rain gauge stations were used as reference over March 1983 to February 2017. To ensure spatial consistency, all products were resampled from their native resolutions (0.25°, 0.1°, and 0.05°) to a common 0.1° grid. GConvAttnLSTM captures complex spatiotemporal rainfall dependencies by combining (i) a topography-aware channel attention module that adaptively reweights the three precipitation sources using static terrain information, (ii) a graph convolutional encoder built on a geo-topographic adjacency matrix to model spatial connectivity and orographic controls, and (iii) a node-wise two-layer LSTM decoder to learn temporal rainfall dynamics. By leveraging complementary satellite strengths and explicitly embedding terrain constraints, the proposed framework aims to produce more reliable daily precipitation fields and to improve performance in gauge-sparse sub-regions of the YRB, thereby supporting robust hydrologic analysis and long-term climate applications.



Keywords: GConvAttnLSTM,  Topography-aware channel attention,  Geo-topographic adjacency matrix,  Multi-source satellite precipitation products,  Yangtze River Basin



Semantic Tags: satellite precipitation fusion; spatiotemporal deep learning; topography-aware; Yangtze River Basin; GConvAttnLSTM; precipitation estimation; flood forecasting


```{admonition} Presentation Information
:class: note

**Submission ID:** R9908  
**Session:** [Hydrometeorological Forecasting and Precipitation Modeling ](./Session_CED-4/)  
**Theme:** Climate, Environmental Hazards, and Disaster Risk    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** SR-C  
```