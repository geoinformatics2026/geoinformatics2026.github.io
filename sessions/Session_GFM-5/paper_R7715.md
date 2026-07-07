---
title: "Bridging Urban Mobility Data and Human Semantics: A Geo-AI Framework for Explainable Tourism Recommendations Using Taipei Metro Flow Patterns and Llama 3"
authors:
- "Bing-Ru Wu"
- "Qi-You Lin"
- "Wei-Chen Lai"
- "Yi-Chung Chen"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Bridging Urban Mobility Data and Human Semantics: A Geo-AI Framework for Explainable Tourism Recommendations Using Taipei Metro Flow Patterns and Llama 3

**Author Information**  
Bing-Ru Wu<sup>1</sup>, Qi-You Lin<sup>2</sup>, Wei-Chen Lai<sup>3</sup>, Yi-Chung Chen<sup>4</sup>


<sup>1</sup> +886988360059  

<sup>2</sup> +886976963802  

<sup>3</sup> +886903219176  

<sup>4</sup> Department of Computer Science and Engineering,  National Chung Hsing University  



## Abstract

[Background] Traditional crowd prediction for urban scenic spots focuses on quantitative accuracy but lacks interpretability, making it difficult for stakeholders like law enforcement to understand decision rationales. In practical crowd control and police deployment, experts must manually interpret data to draft standard operating procedures, which increases labor costs and delays critical real-time responses essential for public safety. [Methodology] This study proposes an innovative framework integrating deep learning with Llama 3 to build an automated decision-support system. Using Taipei Metro data as an urban mobility proxy, the system features two parallel modules. The External Trend Identification Module utilizes a CNN-AutoEncoder to match flow patterns with historical urban events in a latent feature space, identifying external triggers for crowd accumulation. Simultaneously, the Internal Trend Identification Module employs LSTM networks and an AutoEncoder to compress internal mobility trends, matching them with pre-generated congestion reports for specific hotspots. [Integration and Contributions] Finally, the system synthesizes qualitative news and quantitative analytical texts as context for a fine-tuned Llama 3 model. Serving as an information fuser, Llama 3 produces comprehensive natural language reports encompassing situational analysis, crowd control strategies, and specific police deployment recommendations. This research bridges the gap between abstract quantitative features and human-understandable semantics, significantly enhancing the credibility and utility of smart policing systems. Experimental results confirm that the system produces logical, actionable duty analysis reports, providing a clear roadmap for AI-assisted municipal decision-making and robust public administration.



Keywords: Geo-AI,  Explainable AI (XAI),  Urban Mobility,  Taipei Metro,  Llama 3,  Crowd Control,  Decision Support System (DSS)




```{admonition} Presentation Information
:class: note

**Submission ID:** R7715  
**Session:** [Cyberinfrastructure and GeoAI for Intelligent Spatial Decision Support](./Session_GFM-5/)  
**Theme:** GeoAI, Foundation Models \& Spatial ML    
**Date:** Day 2, 21 July (Tuesday)  
**Time:** 14:45 – 16:15  
**Venue:** Stephen Riady Centre-01-Lecture Theatre 50 (LT-50)  
```