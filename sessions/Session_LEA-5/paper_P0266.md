---
title: "Research on Intelligent Building Extraction Models Based on High-Resolution Remote Sensing Imagery"
authors:
- "Shi He"
- "Shiye Zhang"
- "Xiujuan Liang"
- "Yi Wang"
- "Haitao Jing"

---

# Research on Intelligent Building Extraction Models Based on High-Resolution Remote Sensing Imagery

**Author Information**  
Shi He<sup>1</sup>, Shiye Zhang<sup>1</sup>, Xiujuan Liang<sup>1</sup>, Yi Wang<sup>1</sup>, Haitao Jing<sup>1</sup>


<sup>1</sup> Henan Polytechnic University, School of Surveying and Land Information Engineering, Jiaozuo, China  



## Abstract

Building extraction from high-resolution remote sensing imagery is critical for urban planning and smart city development, yet it faces challenges such as blurred boundaries, missing fine details and severe background interference. To address these issues, this study proposes an improved model named GSU-HRNet, which integrates attention mechanisms and boundary refinement strategies on the basis of UHRNet's high-resolution parallel backbone. An enhanced Pyramid Squeeze-and-Excitation (PSE) module is embedded in the lateral feature transmission paths of each hierarchical stage, capturing multi-scale contextual information via adaptive average pooling of multiple sizes to strengthen semantic responses for buildings and suppress background noise. A Gated Bottleneck Convolution (GBC) module is further introduced in the feature fusion stage, adopting a dual-branch structure with gating mechanisms and residual connections to selectively regulate fused features, alleviate redundant feature accumulation, and improve the stability of feature representation. Experiments were conducted on the aerial imagery subset of the WHU Building Dataset (covering 450 km^2 in Christchurch with 8, 189 512x512 image tiles), which was split into training, validation and test sets at a ratio of 6:1:3. Ablation experiments verify the effectiveness and complementarity of PSE and GBC modules, with the combined model achieving optimal performance. Quantitative comparisons show that GSU-HRNet outperforms classical models like U-Net and PSPNet, reaching an IoU of 89.93% and an F1-score of 94.50%. Qualitative analysis demonstrates that the proposed model yields clearer building boundaries, more complete structural preservation, and reduced false detections and omissions, even in challenging scenarios with complex building structures and shadow interference. The results confirm that GSU-HRNet effectively enhances feature representation and boundary delineation accuracy, providing a robust solution for automated building extrrom high-resolution remote sensing imagery.



Keywords: remote sensing imagery, spatial-spectral synergy, photovoltaic system, semantic segmentation model



Semantic Tags: building extraction; high-resolution remote sensing; semantic segmentation; deep learning; attention mechanism; boundary refinement; spatial-spectral fusion; urban mapping; smart city; photovoltaic detection


```{admonition} Presentation Information
:class: note

**Submission ID:** P0266  
**Session:** [Urban Building Extraction and Remote Sensing ](./Session_LEA-5/)  
**Theme:** Land, Ecology, Agriculture, and Sustainable Development    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 14:45 – 16:15  
**Venue:** SR-D  
```