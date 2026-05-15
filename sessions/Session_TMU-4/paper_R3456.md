---
title: "PJM: An out-of-distribution data augmentation method based on pipe joint masking for efficient multi-label sewer defect classification"
authors:
- "Jianghai He"
- "Zegen Wang"

---

# PJM: An out-of-distribution data augmentation method based on pipe joint masking for efficient multi-label sewer defect classification

**Author Information**  
Jianghai He<sup>1</sup>, Zegen Wang<sup>1</sup>


<sup>1</sup> Southwest Petroleum University, School of Geoscience and Technology  



## Abstract

Sewer pipes are critical urban infrastructure for wastewater transportation and public safety, yet they are persistently plagued by frequent defects. Deep Convolutional neural networks (DCNNs) have emerged a powerhouse for sewer defect recognition which is prerequisite for pipe repair and maintenance. Data augmentation methods can enhance DCNNs performance. However, existing methods are suboptimal, which fail to leverage the intrinsic features of sewer images to transform sewer image but rather employ generic techniques like translation and rotation. In this paper, we propose pipe joint masking (PJM), a novel out-of-distribution data augmentation method to enhance the model performance. PJM occludes a circular region in an image and assigns a set of fixed value to its pixel. Specifically, pipe joint parameters are detected by an optimized model, where these parameters represent the circular occlusion, named pipe joint mask. Then, the mask is placed in original image with fixed values, while the defect information is still retained. Finally, the augmented images are utilized for DCNNs training and fine-tuning. The results on a subset of Sewer-ML demonstrates that our method enhances recall by 16.03% and F2-CIW by 9.11% for DCNN architectures. Furthermore, we validate the capability of pipe joint used to image augmentation. These results help to further understand of intrinsic features of sewer image and promote the utilization of these features in the automatic classification of sewer defect.



Keywords: Sewer inspection,  multi-label defect classification,  data augmentation,  out-of-distribution augmentation



Semantic Tags: sewer inspection; defect classification; data augmentation; deep learning; convolutional neural network; multi-label classification; urban infrastructure


```{admonition} Presentation Information
:class: note

**Submission ID:** R3456  
**Session:** [Urban Infrastructure Monitoring, Safety, and Resilience](./Session_TMU-4/)  
**Theme:** Transportation, Mobility, and Urban Infrastructure    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** SR-F  
```