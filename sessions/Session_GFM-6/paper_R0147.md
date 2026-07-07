---
title: "Spatio-Temporal Relevance Classification from Geographic Texts Using Deep Learning"
authors:
- "Miao Tian"
- "Qirui Wu"
- "Yuang Zhang"
- "Liufeng Tao"
- "Qinjun Qiu"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Spatio-Temporal Relevance Classification from Geographic Texts Using Deep Learning

**Author Information**  
Miao Tian<sup>1</sup>, Qirui Wu<sup>1</sup>, Yuang Zhang<sup>1</sup>, Liufeng Tao<sup>1</sup>, Qinjun Qiu<sup>1</sup>


<sup>1</sup> China University of Geosciences, Wuhan  



## Abstract

The growing proliferation of geographic information presents a substantial challenge to the traditional framework of a geographic information analysis and service. The dynamic integration and representation of geographic knowledge, such as triples, with spatio-temporal information play a crucial role in constructing a comprehensive spatio-temporal knowledge graph and facilitating the effective utilization of spatio-temporal big data for knowledge-driven service applications. The existing knowledge graph takes spatio-temporal as the attribute of entity, ignoring the role of spatio-temporal information for accurate retrieval of entity objects and adaptive expression of entity objects. This study approaches the correlation between geographic knowledge and spatio-temporal information as a text classification problem, with the aim of addressing the challenge of establishing meaningful connections among spatio-temporal data using advanced deep learning techniques. Specifically, we leverage Wikipedia as a valuable data source for collecting and filtering geographic texts. The Open Information Extraction (OpenIE) tool is employed to extract triples from each sentence, followed by manual annotation of the sentences’ spatio-temporal relevance. This process leads to the formation of quadruples (time relevance/space relevance) or quintuples (spatio-temporal relevance). Subsequently, a comprehensive spatio-temporal classification dataset is constructed for experiment verification. Ten prominent deep learning text classification models are then utilized to conduct experiments covering various aspects of time, space, and spatio-temporal relationships. The experimental results demonstrate that the Bidirectional Encoder Representations from Transformer-Region-based Convolutional Neural Network (BERT-RCNN) model exhibits the highest performance among the evaluated models. Overall, this study establishes a foundation for future knowledge extraction endeavors.



Keywords: Spatio-temporal text classification,  Geographical knowledge,  Spatio-temporal relevance




```{admonition} Presentation Information
:class: note

**Submission ID:** R0147  
**Session:** [Knowledge Graphs and Spatial Semantics](./Session_GFM-6/)  
**Theme:** GeoAI, Foundation Models \& Spatial ML    
**Date:** Day 2, 21 July (Tuesday)  
**Time:** 16:30 – 18:00  
**Venue:** Stephen Riady Centre-01-Lecture Theatre 50 (LT-50)  
```