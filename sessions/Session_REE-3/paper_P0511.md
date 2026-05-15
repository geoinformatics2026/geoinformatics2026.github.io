---
title: "Adaptive Multi-Scale Spatial Context via Spectral Conditioning for Library-Guided Hyperspectral Unmixing"
authors:
- "Zhixin Zhao"
- "Ruyi Feng"
- "Kaijun Yang"
- "Banxiao Ruan"
- "Nosir Shukurov"

---

# Adaptive Multi-Scale Spatial Context via Spectral Conditioning for Library-Guided Hyperspectral Unmixing

**Author Information**  
Zhixin Zhao<sup>1</sup>, Ruyi Feng<sup>1</sup>, Kaijun Yang<sup>1</sup>, Banxiao Ruan<sup>2</sup>, Nosir Shukurov<sup>3</sup>


<sup>1</sup> China University of Geosciences(Wuhan)  

<sup>2</sup> China University of Geoscience (Wuhan)  

<sup>3</sup> Uzbekistan University of Geological Sciences  



## Abstract

Hyperspectral unmixing is a fundamental tool for quantitative material analysis, yet accurate abundance estimation remains challenging in real scenes with complex spatial mixing and heterogeneous backgrounds. Pixel-wise sparse regression with large spectral libraries often ignores spatial correlation and yields noisy abundance maps. In contrast, simply aggregating neighborhood information can introduce spatial leakage and blur material boundaries. A central difficulty is that the appropriate scale of spatial context varies across an image. Homogeneous regions benefit from broader support for denoising, whereas boundary-adjacent or locally heterogeneous areas require tighter context to avoid cross-material interference. To address this scale mismatch, we propose a lightweight library-guided unmixing network composed of a spectral branch, a spatial branch, and a spectral-conditioned multi-scale fusion module. The spectral branch encodes the center-pixel spectrum, while the spatial branch extracts patch features at multiple receptive-field scales. The fusion module predicts scale weights from compact spectral statistics of the center pixel and applies soft weighting to combine multi-scale spatial features. This design enables adaptive context aggregation that improves spatial coherence while preserving sharp boundaries. To retain interpretability, reconstruction is performed with a fixed spectral dictionary from a predefined library, and the network learns sparse coefficients for each pixel under physical constraints. Experiments on a synthetic dataset and the Urban benchmark show that the proposed network improves reconstruction accuracy and produces cleaner, more boundary-preserving abundance maps compared with representative sparse-regression and deep learning based baselines.



Keywords: Hyperspectral unmixing, spectral library, deep learning, multi-scale fusion



Semantic Tags: hyperspectral unmixing; spectral library; deep learning; multi-scale fusion; abundance estimation; spectral variability; spatial context modeling; remote sensing image analysis


```{admonition} Presentation Information
:class: note

**Submission ID:** P0511  
**Session:** [Hyperspectral Remote Sensing and Spectral Analysis ](./Session_REE-3/)  
**Theme:** Remote Sensing, Earth Observation, and Environmental Monitoring    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 16:30 – 17:45  
**Venue:** SR-B  
```