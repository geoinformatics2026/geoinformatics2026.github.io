---
title: "LLM-based Disaster Event Network Monitoring Intelligent agent"
authors:
- "Xiaoguang Zhou"
- "Jiajin Xi"
- "Dongyang Hou"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# LLM-based Disaster Event Network Monitoring Intelligent agent

**Author Information**  
Xiaoguang Zhou<sup>1</sup>, Jiajin Xi<sup>1</sup>, Dongyang Hou<sup>1</sup>


<sup>1</sup> Central South University  



## Abstract

Currently, many Global South Countries have not established digital disaster emergency tracking and response systems. As a responsible major country, China is willing to provide natural disaster emergency rescue services to the countries in need. Efficiently and accurately obtaining the key natural disaster events information that occur globally at any time is a premise for providing natural disaster emergency services to the countries in need, including quickly collecting spatio-temporal data of disaster regions, aggregating emergency rescue personnel and supplies, etc. Therefore, the authors have developed a 24-hour on-duty intelligent agent for five kind of natural disaster events (i.e., earthquakes, volcanoes, floods, fires, and landslides) based on the Large Language Model (LLM). Firstly, to solve the problem of semantic recognition ambiguity in massive online disaster information streams, a multi-source dual track data collection strategy is proposed. By customizing monitoring of authoritative information sources (such as government websites) and wide-range long tail web data, the completeness and timeliness of obtained information on multiple disasters are guaranteed. Secondly, a two-stage disaster information filtering architecture is constructed, which combines keyword filtering roughly and LLM semantic refinement filtering to eliminate the non-disaster event noise. In order to solve the problem of the difficulty of determining the spatial location of disasters based on news reports, a Mixture-of-Agents (MOA) based positioning agent was constructed, and a POI aware Retrieval Augmented Generation (RAG) mechanism was introduced to improve the accuracy of disaster event location. Experimental test results show that the recognition accuracy of the intelligent agent reached 98.1%, and the F1 value improved by 31.9% compared to traditional methods; In terms of geographic positioning, the administrative matching rate at the county level reaches 87%. The intelligent agent has been worked for six months. It has captured a total of 3429 global disaster events successfully.



Keywords: Disaster event,  Network monitoring,  Intelligent agent,  LLM,  MOA,  RAG




```{admonition} Presentation Information
:class: note

**Submission ID:** R0855  
**Session:** [GeoAI and Data Science for Disaster Resilience](./Session_CED-1/)  
**Theme:** Climate, Env. Hazards \& Disaster Risk    
**Date:** Day 1, 20 July (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** Town Plaza-02-Seminar Room 3 & 4 (SR-E)  
```