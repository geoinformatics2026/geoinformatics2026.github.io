---
title: "ECHF-YOLO: a remote sensing object detection network integrating efficient convolution and high-low frequency features"
authors:
- "Shuhe Zhao"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R2515.pdf
---

# ECHF-YOLO: a remote sensing object detection network integrating efficient convolution and high-low frequency features

**Author Information**  
Shuhe Zhao<sup>1</sup>


<sup>1</sup> Nanjing University  



## Abstract

In recent years, object detection in remote sensing imagery has faced significant challenges, including scale variation, large interclass differences, complex backgrounds, and confusion between objects and their surroundings. To tackle these issues, we propose ECHF-YOLO, a novel optical remote sensing detection framework built upon the YOLO architecture. ECHF-YOLO incorporates efficient convolution and high-low frequency feature fusion to enhance detection performance. Specifically, we introduce Dynamic Convolution, which enriches feature representation without increasing computational cost. Furthermore, we design a High-Low Frequency Adaptive Fusion Neck (HFAF-Neck) that improves the quality of upsampled features and restores detailed information through an enhanced Adaptive Fusion Dynamic Sample (AFDS) module and lightweight Group Shuffle Convolution (GSConv), balancing accuracy and efficiency. To better integrate shallow texture features with deep semantic cues, we propose the Context and Multi-Scale Convolution Guided Frequency Fusion (CMGFF) module for multi-scale adaptive feature fusion. Finally, a Dual-Task Branch Alignment Detector (DTBAD) is introduced to strengthen interaction between classification and localization tasks via task alignment, boosting overall detection accuracy. Experimental results on the DIOR, NWPUVHR-10, and RSOD datasets demonstrate the superiority of ECHF-YOLO, respectively, surpassing some advanced detectors.



Keywords: Deep learning,  Object detection,  ECHF-YOLO



Semantic Tags: remote sensing object detection; YOLO; dynamic convolution; high-low frequency feature fusion; deep learning; aerial imagery; feature representation; optical remote sensing


```{admonition} Presentation Information
:class: note

**Submission ID:** R2515  
**Session:** [Remote Sensing Object Detection and Image Enhancement ](./Session_REE-1/)  
**Theme:** Remote Sensing, Earth Observation, and Environmental Monitoring    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** SRC-Lv1-SR-B (Room-3/4)  
```