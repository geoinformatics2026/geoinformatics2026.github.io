---
title: "A Graph Database-Driven City Information Modeling (CIM) Framework for Urban Renewal Scenarios"
authors:
- "Ziyu Tong"
- "Changxi Li"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# A Graph Database-Driven City Information Modeling (CIM) Framework for Urban Renewal Scenarios

**Author Information**  
Ziyu Tong<sup>1</sup>, Changxi Li<sup>1</sup>


<sup>1</sup> Nanjing University  



## Abstract

Urban complexity demands innovative tools for spatial design, planning, and management. Consequently, the concept of City Information Modeling (CIM) has garnered significant attention from global scholars. The backbone of a CIM system's functionality lies in its database, which is pivotal for data storage and service provision. However, current CIM databases predominantly serve generalized platforms and lack specialized configurations for the renewal of old residential areas. Furthermore, traditional relational databases struggle to express and manage the intricate socio-spatial relationships between "human-house-land". To address this gap, this study proposes a novel CIM framework grounded in graph databases, identifying the specific data requirements and functionalities necessary for urban renewal. The framework systematically categorizes data into subjects, entities, and relationships. Subjects and entities are represented as nodes, while relationships function as interconnecting edges. The entity database utilizes JSON formatting to capture geometric B-Rep information and feature attributes, while the relationship database explicitly maps spatial and social topologies. Using the Yinhong Garden block in Nanjing, China, as a case study, original CAD and Excel data were processed to construct a Neo4j graph database. To facilitate practical use by architects and urban designers, data extraction, storage, and query functionalities were developed on the Rhino and Grasshopper platforms. The framework's efficacy was successfully tested through spatial distribution queries of property rights and topological entity queries based on relationships.



Keywords: City Information Modeling (CIM), Graph Database, Neo4j, Urban Renewal




```{admonition} Presentation Information
:class: note

**Submission ID:** P7800  
**Session:** [Urban and Geospatial Digital Twins for Scenario Modeling](./Session_UPS-8/)  
**Theme:** Urban Analytics, Planning \& Socioeconomics    
**Date:** Day 3, 22 July (Wednesday)  
**Time:** 10:45 – 12:00  
**Venue:** Stephen Riady Centre-01-Seminar Room 1 & 2 (SR-A)  
```