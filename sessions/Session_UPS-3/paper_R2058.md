---
title: "CityGaze: A Deep Learning Framework for Local Landmark Extraction and Cognitive Mapping from Street View Panoramas"
authors:
- "Yunlei Su"
- "Zhecheng Shi"
- "Minwei Zhao"
- "Cai Wu"

---

# CityGaze: A Deep Learning Framework for Local Landmark Extraction and Cognitive Mapping from Street View Panoramas

**Author Information**  
Yunlei Su<sup>1</sup>, Zhecheng Shi<sup>1</sup>, Minwei Zhao<sup>1</sup>, Cai Wu<sup>1</sup>


<sup>1</sup> The Hong Kong University of Science and Technology (Guangzhou)  



## Abstract

In human-centric urban perception, landmarks are central to how people form mental images of cities, consistent with Kevin Lynch’s elements of imageability. However, identifying local landmarks has traditionally relied on subjective surveys or eye-tracking experiments, which limits scalability for large-area spatial analysis. To address this gap, we introduce CityGaze, an open-source Python package that automatically extracts human-perceived local landmarks from street view panoramas by simulating visual attention. Methodologically, CityGaze integrates both Mapillary and custom street view data. It first employs the DeepGaze IIE model to simulate human eye-tracking hotspots, thereby identifying potential landmark candidates. To further contextualize these candidates, the framework uses OneFormer for panoramic semantic segmentation and Depth Anything V3, leveraging its superior zero-shot generalization capabilities to ensure consistent and robust absolute depth estimation across diverse and unseen urban environments globally. By combining the camera’s geographic metadata (longitude and latitude) with the depth estimates and pixel coordinates of the simulated hotspots, CityGaze computes the real-world locations of candidate landmarks. Finally, DBSCAN clustering is applied across multi-view observations to aggregate detections and pinpoint the geographic centers of true local landmarks. Overall, CityGaze translates subjective visual attention into mappable spatial features. By providing both semantic identity and precise coordinates for local landmarks, the tool supports the automated construction of urban cognitive maps. In turn, this capability enables downstream quantitative research in urban expansion, historical urban renewal, spatial equity analysis, and human-centric navigational design.



Keywords: Cognitive Mapping,  Local Landmarks,  Visual Attention Modeling



Semantic Tags: cognitive mapping; local landmark extraction; street view imagery; visual attention modeling; urban perception; deep learning; imageability; Kevin Lynch


```{admonition} Presentation Information
:class: note

**Submission ID:** R2058  
**Session:** [Street View Analytics and Urban Perception Modeling ](./Session_UPS-3/)  
**Theme:** Urban Analytics, Planning, and Socioeconomic Dynamics    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 16:30 – 17:45  
**Venue:** SR-A  
```