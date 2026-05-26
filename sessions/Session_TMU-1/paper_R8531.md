---
title: "Are All Safe Streetscapes Alike? Convergence and Divergence in Perceived Street Safety Using Vision Foundation Models"
authors:
- "Kezhou Ren"
- "Xiao Li"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R8531.pdf
---

# Are All Safe Streetscapes Alike? Convergence and Divergence in Perceived Street Safety Using Vision Foundation Models

**Author Information**  
Kezhou Ren<sup>1</sup>, Xiao Li<sup>1</sup>


<sup>1</sup> The Hong Kong Polytechnic University  



## Abstract

The perception of street safety significantly shapes urban livability. While prior studies have linked perceived safety to visual characteristics of streetscapes, most studies rely on predefined factors extracted from street view images (SVIs), frequently overlooking subtle urban elements and failing to differentiate between diverse urban scenarios. Moreover, it remains unclear how visual features of streetscapes are associated with perceived safety and unsafety and their variation across different urban settings. To address these gaps, this study aims to discover the latent patterns underlying perceived street safety and unsafety using a vision foundation model–enhanced weakly supervised object detection framework. Leveraging the safe and unsafe groups of SVIs identified from the Place Pulse V2 dataset, we first evaluated multiple perception prediction backbones. Based on this evaluation, we selected DINOv2 for feature representation due to its superior transfer performance. We then analyzed the convergence and divergence of extracted feature patterns from safe and unsafe streetscapes both semantically and geographically. Finally, we integrated the Segment Anything Model (SAM) with Class Activation Mapping (CAM) to automatically identify influential streetscape features without using predefined factors. Results demonstrated that vision foundation model features substantially improve discrimination between safe and unsafe streetscapes, outperforming conventional semantic segmentation-based methods. While both perceived safe and unsafe SVIs are associated with multiple features, perceived safe SVIs exhibit a stronger convergence in visual features than unsafe SVIs. Meanwhile, features associated with perceived safety remain relatively consistent within the same geographic regions. We also found fine-grained elements such as road markings consistently contribute to perceived safety, while poorly maintained walls with graffiti are strongly associated with perceived unsafety. This study advances computational urban perception research by revealing asymmetries in street safety perception and introducing an automated framework for discovering nuanced environmental factors, facilitating targeted urban micro-environment renewal and safety-oriented design interventions.



Keywords: Street safety,  Streetscape perception,  Vision foundation models,  Weakly supervised object detection



Semantic Tags: street safety; streetscape perception; vision foundation model; weakly supervised object detection; street view imagery; urban livability; urban safety


```{admonition} Presentation Information
:class: note

**Submission ID:** R8531  
**Session:** [Geospatial Innovations for Sustainable Transportation and Urban Mobility](./Session_TMU-1/)  
**Theme:** Transportation, Mobility, and Urban Infrastructure    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** TP-Lv2-SR-F (Room-5/6)  
```