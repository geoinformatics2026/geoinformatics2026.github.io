---
title: "Interactive Thematic Map Style Intelligent Recommendation"
authors:
- "An Zhang"
- "Yi Cao"
- "Weiyao Guo"
- "Lili Jiang"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R5689.pdf
---

# Interactive Thematic Map Style Intelligent Recommendation

**Author Information**  
An Zhang<sup>1</sup>, Yi Cao<sup>1</sup>, Weiyao Guo<sup>1</sup>, Lili Jiang<sup>1</sup>


<sup>1</sup> Institute of Geographic Sciences and Natural Resources Research, Chinese Academy of Sciences  



## Abstract

The breakthrough progress in GeoAI technology is driving cartography from digitized map-making to intelligent map-making. Due to the wide range of content involved in thematic maps and the diversity of mapping objects, the styles of thematic maps are also varied. It is quite challenging to standardize and normalize the stylistic design of thematic maps.An interactive intelligent recommendation scheme for thematic map styles has been proposed in our research. Through step-by-step interaction, user cartographic requirements are incorporated into the intelligent cartographic workflow. The PageRank ranking strategy is applied to style recommendations, and an intelligent recommendation platform has been developed to realize the interactive intelligent recommendation of thematic map styles. Considering user cartographic requirements, two strategies are proposed: a prompt-guided text-to-image strategy and a reference map-guided image-to-image strategy. The text-to-image strategy targets natural language descriptions of cartographic requirements. Through three steps of interactive guided dialogue, the user's map-making needs are understood, and structured prompts that machines can comprehend are generated. The image-to-image strategy targets cases where reference thematic maps are directly uploaded. Based on a style intelligent recognition algorithm, the map theme, representation method, and visual variables are identified, collectively forming the style features of the reference thematic map. Subsequently, thematic maps and their style features are constructed as an interconnected network structure. The PageRank algorithm is improved and combined with user needs to calculate the importance weights of reference styles, ultimately generating a thematic map style recommendation plan. Finally, driven by cartographic data, the style recommendation plan is structured as style statements, enabling real-time online rendering of thematic maps and supporting the output of style files, ensuring the transferability of recommended styles.



Keywords: GeoAI,  Thematic Map Style,  Intelligent Recommendation,  PageRank



Semantic Tags: thematic map style; intelligent recommendation; GeoAI; cartography; intelligent map-making; PageRank; map design; style normalization


```{admonition} Presentation Information
:class: note

**Submission ID:** R5689  
**Session:** [Cartography, Geovisualization, and Geospatial Services ](./Session_GFM-8/)  
**Theme:** GeoAI, Foundation Models, and Spatial Machine Learning    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 10:45 – 12:00  
**Venue:** SRC-Lv1-LT-50  
```