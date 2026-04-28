---
title: "A 3D Model–Driven Framework for Semantic Recognition of Great Wall Elements"
authors:
- "Jiacheng Li"
- "Qingwu Hu"
- "Xujie Zhang"

---

# A 3D Model–Driven Framework for Semantic Recognition of Great Wall Elements

**Author Information**  
Jiacheng Li<sup>1</sup>, Qingwu Hu<sup>1</sup>, Xujie Zhang<sup>2</sup>


<sup>1</sup> School of Remote Sensing Information Engineering , Wuhan University, Wuhan, 430079, China  

<sup>2</sup> School of Remote Sensing and Information Engineering, Hubei Luojia Laboratory, Wuhan University, Wuhan, 430079, China  



## Abstract

Linear cultural heritage sites represented by the Great Wall hold significant value for cultural heritage protection and preservation condition assessment. However, due to the complex morphology of the sites, the diversity of structural components, and the pronounced differences in preservation conditions, the overall accuracy of existing automated recognition methods remains limited, making it difficult to meet the demands of fine-grained monitoring.To address these challenges, this paper proposes a three-dimensional model–driven automatic recognition framework for Great Wall elements. First, a semantic classification system for Great Wall elements is constructed to characterize both the structural component types and their preservation states. Based on this system, semantic annotation is performed on OSGB models to generate three-dimensional labeled data. Subsequently, the annotated models are converted into the 3D Tiles format and rendered from multiple viewpoints on the Cesium platform to automatically produce large-scale paired RGB images and label images. Finally, representative semantic segmentation networks, including UNet and UrbanSSF, are selected for training and evaluation to achieve automatic extraction of Great Wall structural elements.The proposed method effectively supports semantic understanding tasks in complex Great Wall scenarios. The best-performing model achieves a mean Intersection over Union (mIoU) of 0.8698, demonstrating high segmentation accuracy and strong robustness. The proposed framework provides a scalable technical paradigm for the intelligent interpretation and dynamic monitoring of linear cultural heritage.



Keywords: 3D geospatial modeling,  Semantic classification,  Cultural heritage monitoring,  Great Wall



```{admonition} Presentation Information
:class: note

**Submission ID:** 6188  
**Session:** [Heritage Landslide Segmentation Cultural](./Session_B9/) 
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 14:45 – 16:15
**Venue:** room 9
```