---
title: "Non-destructive extraction of vertical leaf base and inclination angles distribution in field maize"
authors:
- "Lei Lei"
- "Zhenhong Li"
- "Guijun Yang"
- "Hao Yang"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R2389.pdf
---

# Non-destructive extraction of vertical leaf base and inclination angles distribution in field maize

**Author Information**  
Lei Lei<sup>1</sup>, Zhenhong Li<sup>1</sup>, Guijun Yang<sup>1</sup>, Hao Yang<sup>2</sup>


<sup>1</sup> Chang’an University  

<sup>2</sup> Beijing Academy of Agriculture and Forestry Sciences  



## Abstract

Vertical distributions of leaf base and inclination angles are important maize phenotypic traits, influencing light interception and productivity. LiDAR provide unprecedented detail of the 3D structure of the crop canopy. Recent research mainly focuses on the leaf base and inclination angles of maize at the individual level or at lower planting density. It is difficult to extract the distributions of leaf base and inclination angles of maize in the field due to the interlocked and overlapped nature of leaves. In this study, we have proposed a high-throughput method to extract the distributions of leaf base and inclination angles of maize in the field. Firstly, a novel two-stage leaf-stem separation model encompassing the initial separation of leaves and stems and optimization is presented. The model is based on the different geometric features of maize plants defined by neighborhood points, and a cylinder is used to find the neighborhood points by considering the elongated characteristic of maize stems. After that, another elongated cylinder is used to traverse the stem points to optimize the initially separated results. Following the separation of the leaf and stem of maize, hollow cylinders with different thicknesses were used to extract the local leaf points from the separated leaf points based on each stem fitted line, and the DBSCAN algorithm and singular value decomposition were used to calculate the leaf base and inclination angles. The performance of the proposed method was validated through different experimental conditions involving two primary categories of validation scenarios: (1) field-grown maize with diverse cultivars, planting densities, and growth stages; and (2) point cloud data acquired from two representative LiDAR platforms, namely TLS and UAV LiDAR. Notably, the method demonstrated good consistency with the validation data across all tested scenarios, thus verifying its robustness and generalizability in practical applications.



Keywords: Vertical leaf angle distribution,  Field maize,  Light Detection and Ranging (LiDAR),  Different experimental conditions



Semantic Tags: crop phenotyping; leaf angle distribution; field maize; LiDAR; 3D canopy structure; plant biophysics; light interception; high-throughput sensing


```{admonition} Presentation Information
:class: note

**Submission ID:** R2389  
**Session:** [Vegetation and Forest Monitoring with UAV and LiDAR ](./Session_REE-6/)  
**Theme:** Remote Sensing, Earth Observation, and Environmental Monitoring    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 16:30 – 17:45  
**Venue:** SRC-Lv1-SR-B (Room-3/4)  
```