---
title: "A self-supervised foundation model for cognitively-plausible topographic eminence extraction"
authors:
- "Jun Xu"
- "Jiaqi Yang"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# A self-supervised foundation model for cognitively-plausible topographic eminence extraction

**Author Information**  
Jun Xu<sup>1</sup>, Jiaqi Yang<sup>2</sup>


<sup>1</sup> LREIS, Institute of Geographic Science and Natural Resources Research  

<sup>2</sup> Institute of Geographic Sciences and Natural Resources Research  



## Abstract

A fundamental challenge in terrain representation lies in reconciling the continuous elevation field model (DEM) with the discrete, object-based nature of human landscape cognition. People perceive and communicate about landscapes in terms of bounded entities—hills, mountains, and ridges—yet GIS databases lack explicit representations of these cognitively-salient landforms due to their inherently fuzzy and subjective boundaries. This paper introduces a self-supervised foundation model approach to extract topographic eminences—elevated landforms that perceptually dominate their surroundings—in a manner that aligns with human cognitive understanding. We build upon GeomorPM, a geomorphic pretrained model based on the VQMAE (Vector Quantised Masked Autoencoder) architecture, which integrates convolutional networks for local detail extraction with Transformers for capturing global terrain context. Trained on massive unlabeled DEM data via self-supervised learning, GeomorPM has demonstrated superior performance across multiple tasks: maintaining semantic coherence in void filling with 40-60% data missing, achieving 13.3-27.1% RMSE reduction in 8× super-resolution, and improving landform classification mIoU by 4.03% while requiring only 1-5% of labeled samples. These results suggest that the model's latent representations inherently encode topographic structures that correspond to cognitively meaningful landform patterns. We hypothesize that by fine-tuning GeomorPM with cognitive criteria the model can learn not just morphological patterns, but the very essence of what makes a landform a perceptually distinct "object." In this work, we fine-tune GeomorPM to guide the delineation of topographic eminence boundaries. This cognitively-infused fine-tuning enables the model to extract not merely morphological features, but landform objects that reflect how people conceptually organize landscapes. By bridging the field-object dichotomy through self-supervised learning, this work provides a practical and scalable pathway for integrating field and object views of terrain, paving the way for next-generation GIS that can reason about landscape in a manner akin to human cognition.



Keywords: topographic eminences,  foundation model,  self-supervised learning,  DEM,  cognitive ontology




```{admonition} Presentation Information
:class: note

**Submission ID:** R9142  
**Session:** [GeoAI, Foundation Models, and Spatial Learning](./Session_GFM-7/)  
**Theme:** GeoAI, Foundation Models \& Spatial ML    
**Date:** Day 3, 22 July (Wednesday)  
**Time:** 09:00 – 10:30  
**Venue:** Stephen Riady Centre-01-Lecture Theatre 50 (LT-50)  
```