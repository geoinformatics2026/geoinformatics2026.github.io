---
title: "Blind Geo-Localization of Optical Images Based on Multi-Stage Intelligent Matching"
authors:
- "Qiang Wang"
- "Xiying Wang"
- "Hongzhi Huang"
- "Chunlong Huang"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Blind Geo-Localization of Optical Images Based on Multi-Stage Intelligent Matching

**Author Information**  
Qiang Wang<sup>1</sup>, Xiying Wang<sup>1</sup>, Hongzhi Huang<sup>1</sup>, Chunlong Huang<sup>1</sup>


<sup>1</sup> TuZhiZhi (Beijing) Technology Co., Ltd.  



## Abstract

In complex environments such as disasters, severe weather, rugged terrain, and satellite signal occlusion, rapid localization of optical imagery over arbitrary regions without relying on numerous ground control points has become a key research direction in geospatial information science. Combining deep learning and image registration techniques, this paper proposes a control-point-free rapid geo-localization method for multi-source optical imagery over arbitrary regions. Firstly, a remote sensing image feature extraction framework based on the DINOV2 SALAD model is proposed, which integrates self- supervised learning and optimal transport theory to achieve hierarchical representation of global and local features. A two- stage strategy is adopted. In the coarse matching stage, DINOV2 SALAD features combined with the HNSW-PQ index in FAISS are used for fast retrieval of millions of image tiles. Spatial consistency verification of neighboring features is applied to filter mismatches, narrowing the candidate regions down to the Top- 100.In the fine matching stage, the TopicFM model is introduced to model images as a polynomial distribution of topics. The topic distribution is inferred via Transformer, dynamically fusing global semantic and local fine-grained features. A probabilistic matching matrix and RANSAC-based robust optimization are designed, combined with multi-scale pyramid refinement, to achieve coarse-to-fine coordinate recovery. Experimental results demonstrate that the proposed method still achieves competitive performance even without any fine-tuning, which fully verifies its effectiveness and superiority in improving the visual geo- localization ability of images.



Keywords: Optical Image, Geo-Localization, DINOv2, Topic FM




```{admonition} Presentation Information
:class: note

**Submission ID:** P8695  
**Session:** [Remote Sensing Object Detection and Image Enhancement](./Session_REE-1/)  
**Theme:** Remote Sensing, Earth Obs. \& Env. Monitoring    
**Date:** Day 1, 20 July (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** Stephen Riady Centre-01-Seminar Room 3 & 4 (SR-B)  
```