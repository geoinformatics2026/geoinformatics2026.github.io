---
title: "Efficient High-Resolution Remote Sensing Land-Cover Segmentation: Achieving Optimal Speed-Accuracy Balance With A Lightweight Hybrid Network Approach"
authors:
- "Minmin Yu"

---

# Efficient High-Resolution Remote Sensing Land-Cover Segmentation: Achieving Optimal Speed-Accuracy Balance With A Lightweight Hybrid Network Approach

**Author Information**  
Minmin Yu<sup>1</sup>


<sup>1</sup> henu  



## Abstract

With the continuous advancement of remote sensing image land-cover semantic segmentation models, their ability to learn semantic features and segmentation performance have both improved significantly. However, the increasing model scale has led to a gradual decline in inference efficiency and a notable rise in computational costs. How to effectively leverage the strengths of different approaches while avoiding excessive parameterization for land-cover semantic segmentation remains a significant challenge. In response, this paper introduces a lightweight hybrid model, FastRSNet, designed to balance the accuracy and speed of land-cover semantic segmentation. FastRSNet combines the advantages of CNN, Transformer, and Mamba models within an encoder-decoder framework, incorporating a Multi-scale Vision Mamba (MSVMamba) Block and a Light Attention Module (LAM). The MSVMamba Block uses a dilation strategy for scanning and sampling, while integrating features from multiple branches to enhance multi-scale feature capture. LAM optimizes the downsampled features and aligns them with upsampled features. Additionally, structural re-parameterization and wavelet transform are employed to further enhance the model's inference speed and performance. Structural re-parameterization removes certain residual connections during inference, improving speed, while the wavelet transform utilizes a larger receptive field to capture features without increasing parameter count, thus enhancing model performance. Experimental results show that FastRSNet achieved mean Intersection over Union (MIoU) scores of 72.97% and 71.95% on the Potsdam and Vaihingen datasets, respectively, with only 6.42M parameters and 5.16 GFLOPs. Compared to most existing methods, FastRSNet provides a remarkable balance between model size and performance.



Keywords: Mamba,  CNN,  semantic segmentation,  Transformer,  lightweight,  land cover classification



```{admonition} Presentation Information
:class: note

**Submission ID:** 4816  
**Session:** [Heritage Landslide Segmentation Cultural](./Session_B9/) 
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 14:45 – 16:15
**Venue:** room 9
```