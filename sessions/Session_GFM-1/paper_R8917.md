---
title: "CartoDirector: A geospatial storyteller that converts text into dynamic cartographic transformations using LLMs"
authors:
- "Pengbo Li"
- "Haowen Yan"
- "Jiannan Li"
- "Xiaomin Lu"
- "Binbin Lin"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R8917.pdf
---

# CartoDirector: A geospatial storyteller that converts text into dynamic cartographic transformations using LLMs

**Author Information**  
Pengbo Li<sup>1</sup>, Haowen Yan<sup>1</sup>, Jiannan Li<sup>2</sup>, Xiaomin Lu<sup>1</sup>, Binbin Lin<sup>1</sup>


<sup>1</sup> Faculty of Geomatics, Lanzhou Jiaotong University  

<sup>2</sup> School of Computing and Information Systems, Singapore Management University  



## Abstract

Maps serve as powerful tools for transcending cultural and linguistic barriers to communicate spatial and temporal information. While natural language is descriptive, it often lacks the intuitive spatial context that geovisualizations provide. This study presents CartoDirector, a novel autonomous mapping system designed to bridge the gap between textual storytelling and geographic visualization by leveraging large language models (LLMs). The primary purpose of CartoDirector is to transform descriptive narratives into dynamic, cartographically coherent mapping sequences, functioning analogously to a film director who interprets scripts through decisions about camera angles, perspective, and visual style. The methodology employs a fine-tuned LLM to perform a structured four-step workflow. First, the Content Enricher expands the input story by adding detailed cartographic metadata and contextual information. Second, the Storyboard Generator segments the enriched text into sequential scripts, establishing the temporal progression of the visual narrative. Third, the Geospatial Scene Parser converts each script into object-oriented scene files, specifying critical cartographic elements including geographic entities, scale, perspective, visual style, and output modality. Fourth, these scene files guide the autonomous selection of appropriate geospatial databases and cartographic tools to generate the corresponding maps. The fine-tuned LLM continuously coordinates these modules, ensuring narrative coherence throughout the pipeline. Unlike existing geospatial LLM applications that focus on individual map generation or tool execution, CartoDirector specializes in understanding a story's spatial and temporal context to execute complex cartographic transformations, including anchor translation, scaling, perspective changes, style transfer, and modality transfer. Experimental results demonstrate that the system effectively converts simple story texts into spatially and temporally coherent map narratives while preserving semantic meaning and geographic accuracy. This system exemplifies the potential of LLM-based generative AI to make geographic information more intuitive and accessible through automated visual storytelling, offering new possibilities for journalism, education, and spatial communication.



Keywords: Cartographic transformation,  Geovisualization,  Visual storytelling,  Large language model



Semantic Tags: cartographic transformation; geovisualization; visual storytelling; large language model; automated mapping; dynamic cartography; natural language to map; autonomous mapping


```{admonition} Presentation Information
:class: note

**Submission ID:** R8917  
**Session:** [Emerging LLM-based Methods for Geospatial Analysis - Part 1](./Session_GFM-1/)  
**Theme:** GeoAI, Foundation Models, and Spatial Machine Learning    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** SRC-Lv1-LT-50  
```