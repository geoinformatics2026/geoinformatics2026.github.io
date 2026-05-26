---
title: "Quantifying geographic domain shift to decouple the geographic transferability of human mobility flow generations"
authors:
- "Zhiyong Zhou"
- "Song Gao"
- "Qianheng Zhang"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R3508.pdf
---

# Quantifying geographic domain shift to decouple the geographic transferability of human mobility flow generations

**Author Information**  
Zhiyong Zhou<sup>1</sup>, Song Gao<sup>1</sup>, Qianheng Zhang<sup>1</sup>


<sup>1</sup> University of Wisconsin-Madison  



## Abstract

Human mobility serves as an essential proxy for understanding social, economic, and environmental dynamics in urban systems. However, since human mobility data are often scarce due to high collection costs and privacy concerns, their generation from limited mobility observations and auxiliary data sources is highly needed. Although geographic transferability is a critical dimension to compare different human mobility generation models, few studies have paid attention to the intrinsic characteristics of geographic transferability. To this end, this study systematically investigates the geographic transferability of a classical human mobility generation model, DeepGravity, using a large-scale benchmark dataset of census tract–level commuting flows across 2,265 counties in the United States. Inspired by domain adaptation theory in machine learning, we propose two geographic domain shift metrics, mutual information shift and Moran spatial shift, to quantify intrinsic differences in geographic feature distributions and spatial structures between source and target regions. To examine their associations with geographic transferability, we employ linear mixed-effects regression to analyze the associations between geographic domain shifts and transferability. Our results reveal substantial heterogeneity and asymmetry in geographic transferability across regions. Both information shift and spatial shift exhibit statistically significant and complementary explanatory power. It indicates that transferability depends not only on model design but also on intrinsic geographic differences. These findings provide a novel framework for evaluating and improving the geographic transferability of human mobility generation models and support more robust and fair mobility data synthesis across diverse regions.



Keywords: Geographic transferability,  covariate shift,  human mobility flow generation,  transfer learning



Semantic Tags: geographic transferability; human mobility flow generation; transfer learning; covariate shift; domain adaptation; spatial generalization; mobility modeling; data-scarce regions


```{admonition} Presentation Information
:class: note

**Submission ID:** R3508  
**Session:** [Spatial Statistics, Geostatistics, and GIScience Theory](./Session_GSC-7/)  
**Theme:** GIScience Theory, Spatial Statistics, and Computational Methods    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 09:00 – 10:30  
**Venue:** TP-Lv2-SR-F (Room-5/6)  
```