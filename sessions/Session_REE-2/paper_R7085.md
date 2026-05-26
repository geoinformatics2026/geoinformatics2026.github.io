---
title: "An Optimized Faster R-CNN-Based Approach for Automated Detection of Slow-Moving Landslides Using InSAR Surface Deformation Rates"
authors:
- "Chenglong Zhang"
- "Jingxiang Luo"
- "Zhenhong Li"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R7085.pdf
---

# An Optimized Faster R-CNN-Based Approach for Automated Detection of Slow-Moving Landslides Using InSAR Surface Deformation Rates

**Author Information**  
Chenglong Zhang<sup>1</sup>, Jingxiang Luo<sup>1</sup>, Zhenhong Li<sup>1</sup>


<sup>1</sup> Chang'an University  



## Abstract

Landslides represent a dominant class of geological hazards endangering human lives, property safety, and ecological stability, especially in tectonically active alpine canyon regions, making accurate and timely acquisition of their spatial location information of paramount importance for proactive disaster risk reduction. Interferometric Synthetic Aperture Radar (InSAR), which is unaffected by adverse weather and low illumination in high-altitude areas, has emerged as a robust technique for high-precision capture of subtle surface deformation, and is widely adopted for large-spatial-scale landslide identification. However, the prevailing workflow for landslide detection using InSAR-derived deformation rates still relies on manual visual interpretation, which is notoriously time-consuming, labor-demanding, and heavily reliant on expert experience, with high risks of missed or inconsistent detections in large-area mapping. While notable progress has been made via cluster analysis, hotspot analysis and deep learning, key bottlenecks including inadequate intelligent automation and limited generalization across complex geological settings remain unaddressed. In this work, we present an enhanced Faster R-CNN model to realize automated identification of slow-moving landslides, using InSAR Line of Sight (LOS) annual deformation rates covering the upper and middle reaches of the Jinsha River Basin. The model integrates a ResNet-34 backbone, Feature Pyramid Network (FPN) and Convolutional Block Attention Module (CBAM), enabling efficient multi-scale feature extraction and targeted attention to faint deformation zones while suppressing non-deformation background noise. This model yields 93.56% precision, 97.15% recall and 93.6% F1-score on the test set, exhibiting robust detection performance. Comparative analysis against conventional hotspot analysis and K-means clustering validates its strong generalization in typical landslide-susceptible areas of the Qinghai–Tibet Plateau. This approach facilitates dynamic updating of regional slow-moving landslide inventories, providing essential technical underpinnings for landslide hazard detection and risk mitigation.



Keywords: Jinsha River,  improved Faster R-CNN,  slow-moving landslides,  generalization capabilities



Semantic Tags: landslide detection; InSAR; slow-moving landslides; Faster R-CNN; deep learning; surface deformation; geological hazard; Jinsha River; China


```{admonition} Presentation Information
:class: note

**Submission ID:** R7085  
**Session:** [InSAR and Geological Hazard Monitoring ](./Session_REE-2/)  
**Theme:** Remote Sensing, Earth Observation, and Environmental Monitoring    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 14:45 – 16:15  
**Venue:** SRC-Lv1-SR-B (Room-3/4)  
```