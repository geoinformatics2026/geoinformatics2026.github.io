---
title: "Road-Level Urban Environmental Hazard Detection from Crowdsourced Reports Using Multimodal Geospatial Context"
authors:
- "Guangsheng Dong"
- "Xinyao Wang"
- "Tao Cheng"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Road-Level Urban Environmental Hazard Detection from Crowdsourced Reports Using Multimodal Geospatial Context

**Author Information**  
Guangsheng Dong<sup>1</sup>, Xinyao Wang<sup>2</sup>, Tao Cheng<sup>2</sup>


<sup>1</sup> Wuhan University  

<sup>2</sup> University College London  



## Abstract

Citizen-generated public reports provide a valuable crowdsourced source of urban hazard information, capturing environment-related problems such as pavement defects, damaged street assets, exposed utilities, and drainage failures. Unlike official inspection records, these reports are uploaded voluntarily by residents and often contain heterogeneous, noisy, and incomplete information, including short text, optional user images, and uneven spatial context. This makes reliable hazard identification both important and challenging for public safety, infrastructure maintenance, and resilient urban management. This study develops a multimodal fusion framework for urban environmental hazard detection using crowdsourced public repair reports and multi-source geospatial context. The framework is trained and evaluated on a manually labelled FixMyStreet dataset and then applied to a large unlabeled London dataset for city-scale analysis. It integrates six modalities: report text, user-uploaded images, nearby street-view imagery, POI semantic features, POI spatial features, and satellite embeddings. These heterogeneous inputs are encoded using pre-trained foundation models, including CLIP, DINO ViT-B/16, and AlphaEarth-based satellite representations, and fused through gated attention, a CLIP-Transformer-based module, and a stacking ensemble. The model classifies reports into five categories: Road Surface and Pavement Damage, Street Furniture and Lighting Damage, Exposed or Damaged Utilities, Drainage and Flooding Issues, and Non-hazard or Environmental Nuisance. Compared with a text-only baseline, the multimodal model improves Macro-F1 from 0.835 to 0.866 and accuracy from 0.838 to 0.872. The trained framework is further applied to approximately 139 thousands unlabeled London reports, and the predicted hazards are aggregated to fine-grained road segments to generate road-level risk maps. The results demonstrate the value of combining crowdsourced citizen reports with visual and spatial context for scalable urban hazard sensing.



Keywords: urban environmental hazards,  crowdsourced reports,  multimodal fusion,  geospatial context




```{admonition} Presentation Information
:class: note

**Submission ID:** R7829  
**Session:** [Urban Infrastructure Monitoring, Safety, and Resilience](./Session_TMU-4/)  
**Theme:** Transportation, Mobility \& Urban Infrastructure    
**Date:** Day 2, 21 July (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** Stephen Riady Centre-01-Seminar Room 6 (SR-D)  
```