---
title: "Pretraining, Adaptation, and Refinement: Mapping Nationwide Urban Villages in China Using Multimodal Geospatial Data"
authors:
- "Lubin Bai"
- "Shihong Du"
- "Xiuyuan Zhang"

---

# Pretraining, Adaptation, and Refinement: Mapping Nationwide Urban Villages in China Using Multimodal Geospatial Data

**Author Information**  
Lubin Bai<sup>1</sup>, Shihong Du<sup>1</sup>, Xiuyuan Zhang<sup>1</sup>


<sup>1</sup> College of Urban and Environmental Sciences, Peking University  



## Abstract

Urban Villages (UVs) represent a distinctive form of high-density informal settlement embedded within China’s rapidly urbanizing cities. Accurate identification of UVs is critical for urban governance, renewal, and sustainable development. But due to the pronounced heterogeneity and diversity of UVs across China’s vast territory, a consistent and reliable nationwide dataset has been lacking. To address this, we propose a novel three-stage mapping framework that integrates multimodal geospatial data and foundation models. First, we design GeoLink, a multimodal geospatial foundation model pretrained on paired remote sensing (RS) imagery and OpenStreetMap (OSM) data. GeoLink can fuse RS and OSM embeddings at object-pixel level, providing fine-grained fusion embeddings capable of capturing both the morphological and functional semantics of urban environments. Second, we adapt GeoLink to the UV segmentation task by integrating it with an UperNet decoder, trained on high-quality samples from representative cities. Finally, we employ the Segment Anything Model (SAM) in a prompt-based refinement stage to enhance boundary precision, correcting initial segmentation inaccuracies. This framework produces GeoLink-UV, the first high-resolution nationwide dataset delineating the boundaries of UVs across 342 Chinese cities circa 2023. A geographically stratified accuracy assessment using independent samples from 28 cities confirms the product's reliability, achieving an overall F1-score of 0.77 and IoU of 0.60. Leveraging this dataset, we reveal substantial interregional disparities: UVs occupy an average of 8% of urban built-up land, with marked clustering in central and south China. Building-level analysis further quantifies the consistent low-rise, high-density morphology of UVs, while also highlighting regionally differentiated characteristics. This work contributes a systematic, transferable paradigm for large-scale urban mapping and demonstrates the power of multimodal geospatial foundation models. The GeoLink-UV dataset provides an open and validated geospatial foundation for supporting informal settlement monitoring and urban renewal planning, directly contributing to the UN Sustainable Development Goal 11.



Keywords: Urban Village,  Foundation Model,  Multi-modal Learning,  Remote Sensing,  OpenStreetMap



Semantic Tags: urban village mapping; foundation model; multimodal learning; remote sensing; OpenStreetMap; informal settlement; nationwide mapping; China


```{admonition} Presentation Information
:class: note

**Submission ID:** R2473  
**Session:** [Urban Building Extraction and Remote Sensing ](./Session_LEA-5/)  
**Theme:** Land, Ecology, Agriculture, and Sustainable Development    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 14:45 – 16:15  
**Venue:** SR-D  
```