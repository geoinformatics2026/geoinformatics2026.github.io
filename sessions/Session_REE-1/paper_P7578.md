---
title: "LMDNet: A Lightweight Multi-scale Network for Remote Sensing Object Detection"
authors:
- "Shidong Wang"
- "Zhiyu Li"
- "Jun Yang"
- "Jingfan Wang"
- "Na Wang"
- "Haipeng Chen"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# LMDNet: A Lightweight Multi-scale Network for Remote Sensing Object Detection

**Author Information**  
Shidong Wang<sup>1</sup>, Zhiyu Li<sup>1</sup>, Jun Yang<sup>1</sup>, Jingfan Wang<sup>1</sup>, Na Wang<sup>1</sup>, Haipeng Chen<sup>1</sup>


<sup>1</sup> School of Surveying and Land Information Engineering, Henan Polytechnic University  



## Abstract

Remote sensing object detection holds significant value in fields such as urban planning. Conventional object detection networks heavily rely on fixed convolution and pooling operations, which struggle to adapt to the diverse scales of remote sensing objects. This issue is particularly prominent for remote sensing objects with a large scale variation, often leading to missed or false detections. Furthermore, high-resolution remote sensing data analysis requires models with large numbers of parameters, making it challenging to efficiently deploy on lightweight devices such as drones. To address this, this paper proposes a lightweight multi-scale remote sensing object detection network, LMDNet. First, a lightweight feature processing architecture is constructed to efficiently handle multi-scale remote sensing object features. Next, a PFusion module is used for feature fusion, enhancing the network's ability to capture contextual information and retain details across different scale remote sensing objects. Finally, through collaborative optimization of the feature processing architecture and feature fusion module, LMDNet effectively processes multi-scale remote sensing object features while maintaining low complexity and computational overhead. Experiments based on the DOTAv1.0 dataset demonstrate that this method can effectively detect multi-scale remote sensing objects and significantly outperforms current state- of-the-art methods in overall performance.



Keywords: object detection, remote sensing, lightweight design, multi-scale remote sensing object, feature fusion




```{admonition} Presentation Information
:class: note

**Submission ID:** P7578  
**Session:** [Remote Sensing Object Detection and Image Enhancement](./Session_REE-1/)  
**Theme:** Remote Sensing, Earth Obs. \& Env. Monitoring    
**Date:** Day 1, 20 July (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** Stephen Riady Centre-01-Seminar Room 3 & 4 (SR-B)  
```