---
title: "Low-Cost Urban Road Mapping via Dual-View Fusion of Panoramic Images"
authors:
- "Zhebin Zhao"
- "Yaxin Li"
- "Hongsheng Huang"
- "Jiawei Wan"
- "Mahmoud Adham"
- "Mostafa Mahmoud"
- "Wu Chen"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_P3273.pdf
---

# Low-Cost Urban Road Mapping via Dual-View Fusion of Panoramic Images

**Author Information**  
Zhebin Zhao<sup>1</sup>, Yaxin Li<sup>1</sup>, Hongsheng Huang<sup>1</sup>, Jiawei Wan<sup>1</sup>, Mahmoud Adham<sup>1</sup>, Mostafa Mahmoud<sup>1</sup>, Wu Chen<sup>1</sup>


<sup>1</sup> The Hong Kong Polytechnic University  



## Abstract

High-definition (HD) road maps are critical for autonomous navigation and intelligent transportation systems, yet single front-view pipelines suffer from unilateral occlusions and narrow field of view (FoV), while multi-camera bird's eyes view (BEV) systems improve coverage at the cost of hardware, calibration complexity, and computation. This work addresses the open problem of achieving robust, wide-coverage HD mapping under urban occlusions using a single, low-cost panoramic camera. We propose a lightweight dual-view fusion framework for incremental road mapping from panoramic images. The method introduces three technical contributions: (1) a cost- effective single-sensor dual-view construction that extracts front and rear perspective views from one panoramic camera via FoV- aware projection; to the best of our knowledge, this is the first single panoramic sensor-based framework for HD road mapping that removes the need for multi-camera systems; (2) a geometry- consistent BEV fusion module that integrates inverse perspective spective mapping (IPM), pose-stabilized BEV stitching, and patch-level merging to suppress parallax and motion jitters and to recover markings occluded in one view but visible in the other; and (3) a lightweight incremental pipeline that simplifies deployment and reduces calibration and compute overhead compared to ring-camera systems. On 80 panoramic images with five road- element classes under unilateral or moderate occlusion, our dual-view fusion improves marking completeness by 33.3%, reduces geometric deviation (PSC) by 26.7%, and enhances shape regularity (RARC) by 7.7% over a front-view-only baseline, while maintaining comparable precision. These results demonstrate that a single panoramic sensor can close much of the occlusion gap to multi-camera solutions.



Keywords: Geo-spatial data processing, Intelligent transportation systems, Road mapping



Semantic Tags: road mapping; panoramic imagery; autonomous navigation; dual-view fusion; urban road detection; intelligent transportation; low-cost sensing; high-definition map


```{admonition} Presentation Information
:class: note

**Submission ID:** P3273  
**Session:** [Intelligent Transportation Systems and Autonomous Driving ](./Session_TMU-8/)  
**Theme:** Transportation, Mobility, and Urban Infrastructure    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 10:45 – 12:00  
**Venue:** SRC-Lv2-SR-F (Room-8)  
```