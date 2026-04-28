---
title: "An Optimized Faster R-CNN-Based Approach for Automated Detection of Slow-Moving Landslides Using InSAR Surface Deformation Rates"
authors:
- "Chenglong Zhang"
- "Jingxiang Luo"
- "Zhenhong Li"

---

# An Optimized Faster R-CNN-Based Approach for Automated Detection of Slow-Moving Landslides Using InSAR Surface Deformation Rates

**Author Information**  
Chenglong Zhang<sup>1</sup>, Jingxiang Luo<sup>1</sup>, Zhenhong Li<sup>1</sup>


<sup>1</sup> Chang'an University  



## Abstract

Landslides represent a dominant class of geological hazards endangering human lives, property safety, and ecological stability, especially in tectonically active alpine canyon regions, making accurate and timely acquisition of their spatial location information of paramount importance for proactive disaster risk reduction. Interferometric Synthetic Aperture Radar (InSAR), which is unaffected by adverse weather and low illumination in high-altitude areas, has emerged as a robust technique for high-precision capture of subtle surface deformation, and is widely adopted for large-spatial-scale landslide identification. However, the prevailing workflow for landslide detection using InSAR-derived deformation rates still relies on manual visual interpretation, which is notoriously time-consuming, labor-demanding, and heavily reliant on expert experience, with high risks of missed or inconsistent detections in large-area mapping. While notable progress has been made via cluster analysis, hotspot analysis and deep learning, key bottlenecks including inadequate intelligent automation and limited generalization across complex geological settings remain unaddressed. In this work, we present an enhanced Faster R-CNN model to realize automated identification of slow-moving landslides, using InSAR Line of Sight (LOS) annual deformation rates covering the upper and middle reaches of the Jinsha River Basin. The model integrates a ResNet-34 backbone, Feature Pyramid Network (FPN) and Convolutional Block Attention Module (CBAM), enabling efficient multi-scale feature extraction and targeted attention to faint deformation zones while suppressing non-deformation background noise. This model yields 93.56% precision, 97.15% recall and 93.6% F1-score on the test set, exhibiting robust detection performance. Comparative analysis against conventional hotspot analysis and K-means clustering validates its strong generalization in typical landslide-susceptible areas of the Qinghai–Tibet Plateau. This approach facilitates dynamic updating of regional slow-moving landslide inventories, providing essential technical underpinnings for landslide hazard detection and risk mitigation.



Keywords: Jinsha River,  improved Faster R-CNN,  slow-moving landslides,  generalization capabilities



```{admonition} Presentation Information
:class: note

**Submission ID:** 7085  
**Session:** [Deformation Extreme Risk Insar](./Session_G3/) 
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 10:45 – 12:00
**Venue:** room 3
```