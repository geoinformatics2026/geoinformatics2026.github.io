---
title: "SSDFNet: State Space-Driven Multi-Level Feature Interaction and Frequency-Domain Enhancement for Optical-SAR Building Extraction"
authors:
- "Yonghui Tan"
- "Yumin Chen"
- "Rui Zhu"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# SSDFNet: State Space-Driven Multi-Level Feature Interaction and Frequency-Domain Enhancement for Optical-SAR Building Extraction

**Author Information**  
Yonghui Tan<sup>1</sup>, Yumin Chen<sup>1</sup>, Rui Zhu<sup>2</sup>


<sup>1</sup> Wuhan University  

<sup>2</sup> Nanjing Normal University  



## Abstract

Building extraction (BE) is a critical task in remote sensing image interpretation. Utilizing multi-modal image data (optical and SAR) enables data fusion from different modalities, providing more comprehensive building information. Nowadays, most researchers build numerous networks using convolutional neural networks or Transformer. However, these two approaches meet challenges in achieving high-precision detection in large-scale scenarios while preserving computational efficiency because of intrinsic limits in their architectural designs. To tackle challenge, we introduced VMamba for the first time in optical-SAR BE tasks, and proposed a State-Space-Driven multi-lever Feature interaction and frequency-domain enhancement Network (SSDFNet), consisting of three modules. We developed the Semantic Detail Fusion Module (SDFM) that integrates rich semantic information from low-resolution features with fine-grained geometric texture information from high-resolution features in the encoder. To efficiently fuse optical and SAR features, the Dual Stream Fusion Module (DSFM) was designed to achieve adaptive cross-modal alignment tailored to the structural differences between SAR and optical images. Finally, we designed the Frequency-Domain Enhancement Fusion Module (FDEFM) in the decoder. It decomposes features into high-frequency and low-frequency components to enable directional frequency-domain enhancement for building’s everall structure. Experimental results on two multimodal BE datasets (DFC23 Track2 and MSAW) and the unimodal BE dataset INRIA demonstrate that SSDFNet achieves optimal performance compared to other SOTA methods in both quantitative evaluation metrics and qualitative visualization with IoU values of 85.31%, 80.70%, and 84.38%, respectively. Finally, we constructed an 0.5m resolution Optical-SAR based building rooftop dataset for entire Singapore, achieving IoU and F1 scores of 80.41% and 89.14%, respectively. Based on these extraction results and elevation data, we estimated the monthly solar radiation for Singapore in 2024.



Keywords: Synthetic aperture radar (SAR),  Optical images,  Building extraction,  Remote sensing,  Solar irradiation




```{admonition} Presentation Information
:class: note

**Submission ID:** R9116  
**Session:** [GeoAI-Facilitated Energy Geographies](./Session_LEA-2/)  
**Theme:** Land, Ecology, Agriculture \& Sustainable Dev.    
**Date:** Day 1, 20 July (Monday)  
**Time:** 14:45 – 16:15  
**Venue:** Stephen Riady Centre-01-Lecture Theatre 51 (LT-51)  
```