---
title: "Multimodal Spatial Co-occurrence Knowledge Representation for Virtual Trajectory Classification"
authors:
- "Guangsheng Dong"
- "Hao Sha"
- "Tao Cheng"
- "Huayi Wu"
- "Rui Li"

---

# Multimodal Spatial Co-occurrence Knowledge Representation for Virtual Trajectory Classification

**Author Information**  
Guangsheng Dong<sup>1</sup>, Hao Sha<sup>1</sup>, Tao Cheng<sup>2</sup>, Huayi Wu<sup>1</sup>, Rui Li<sup>1</sup>


<sup>1</sup> Wuhan University  

<sup>2</sup> University College London  



## Abstract

Virtual trajectories record users' fine-grained spatio-temporal interactions with public map service platforms (PMSPs) and reflect domain-oriented access tendencies toward specific places and map content. Despite their potential for user profiling and personalized services, prior classification methods often remain POI-centric and struggle to represent line- and area-based map contexts, thereby limiting the exploitation of multimodal spatial dependencies. This study proposes a comprehensive virtual trajectory classification framework based on multimodal spatial co-occurrence knowledge representation to bridge this gap. We first address the lack of explicit tile-level semantics by developing an interpretable composite semantic taxonomy for vector tiles. By discretizing rendered map-feature compositions—including roads, buildings, water, and green land—into discrete content levels, we assign functional tile categories that reflect realistic land-use configurations. This process yields 117 valid composite categories, enabling map tiles to serve as semantic carriers alongside POIs. Subsequently, we construct a Multimodal Spatial Co-occurrence Knowledge Graph (MSCKG) that integrates POIs, tiles, and their category attributes. The MSCKG explicitly encodes heterogeneous spatial relations, including POI–tile containment, POI–POI proximity, and tile–tile adjacency. We employ knowledge graph embedding (DistMult) to learn representations of these elements, which are then aggregated to characterize trajectory sequences for domain classification. Experiments conducted on Tianditu access logs in Beijing across six domain-oriented applications demonstrate the framework's effectiveness. The results show that the best multimodal fusion configuration (POI + tile) achieves an accuracy of 0.680, a substantial improvement of 0.251 over the traditional Word2Vec baseline. Furthermore, we introduce intrinsic spatial indicators—POI hit rate, heterogeneous-neighbor proximity rate, and spatial concentration—to explain domain-dependent classification difficulty. These indicators link performance variation to the underlying spatial organization of domain-specific browsing targets, significantly enhancing the interpretability of the model's decision-making process.



Keywords: Virtual trajectories,  Vector tile taxonomy,  Spatial co-occurrence knowledge graph,  Knowledge graph embedding,  Public map service platforms



Semantic Tags: virtual trajectory; spatial co-occurrence; knowledge graph embedding; map service platform; user profiling; multimodal spatial data; POI classification


```{admonition} Presentation Information
:class: note

**Submission ID:** R0392  
**Session:** [Knowledge Graphs and Spatial Semantics ](./Session_GFM-6/)  
**Theme:** GeoAI, Foundation Models, and Spatial Machine Learning    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 16:30 – 17:45  
**Venue:** LT-1  
```