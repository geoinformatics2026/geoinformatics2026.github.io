---
title: "Enhancing Low-Resolution Satellite Imagery for Accurate PV Panel Mapping Using JEGAN-HRNet"
authors:
- "Shi He"
- "Yi Wang"
- "Xinwen Wang"
- "Shiye Zhang"
- "Shidong Wang"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Enhancing Low-Resolution Satellite Imagery for Accurate PV Panel Mapping Using JEGAN-HRNet

**Author Information**  
Shi He<sup>1</sup>, Yi Wang<sup>1</sup>, Xinwen Wang<sup>1</sup>, Shiye Zhang<sup>1</sup>, Shidong Wang<sup>1</sup>


<sup>1</sup> Henan Polytechnic University, School of Surveying and Land Information Engineering, Jiaozuo, China  



## Abstract

In practical monitoring, imagery is often limited to low spatial resolution due to sensor and acquisition constraints, which hampers detailed representation of photovoltaic (PV) array structures and poses a critical challenge for accurate detection and boundary delineation. In this study, JEGAN-HRNet is proposed as a PV array reconstruction and detection model specifically designed for low-resolution imagery. The model, given low-resolution remote sensing imagery as input, is designed to construct a spatial detail reconstruction mechanism that enables the learning of the mapping between low- and high-resolution features. Through the enhancement of texture representation and structural characterization capabilities, high-precision detection of PV arrays is achieved. Structurally, the generation subnetwork is responsible for reconstructing blurred PV patches from low-resolution images into high-resolution feature representations with well-defined geometric edges and structural details. The segmentation subnetwork is employed to perform pixel-level classification on the reconstructed super-resolved feature maps, thereby enabling precise extraction of PV arrays. By incorporating a semantic loss function into the backpropagation process, the reconstruction direction of the generation subnetwork is directly constrained and guided by the resulting segmentation accuracy. This approach ensures that the generated outputs not only exhibit enhanced visual resolution but also maintain improved semantic consistency and interpretability. Experimental validation carried out at the Taratan PV Power Plant indicated that the proposed model achieved an Intersection over Union (IoU) of 89.53% and an F1 score of 93.68% in PV array detection tasks, thereby significantly surpassing the comparative methods. The results indicate that the proposed "super-resolution generation + fine segmentation" synergistic mechanism effectively addresses challenges, including blurred array boundaries, missing details, and limited detection accuracy when operating on low-resolution imagery. The method is shown to provide reliable technical support for large-scale PV resource surveys and ecological impact assessments, thereby establishing a methodological foundation for subsequent dynamic monitoring studies that incorporate temporal information.



Keywords: spatio-temporal fusion, convolutional neural network, generative adversarial network, semantic segmentation




```{admonition} Presentation Information
:class: note

**Submission ID:** P8680  
**Session:** [Remote Sensing Object Detection and Image Enhancement](./Session_REE-1/)  
**Theme:** Remote Sensing, Earth Obs. \& Env. Monitoring    
**Date:** Day 1, 20 July (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** Stephen Riady Centre-01-Seminar Room 3 & 4 (SR-B)  
```