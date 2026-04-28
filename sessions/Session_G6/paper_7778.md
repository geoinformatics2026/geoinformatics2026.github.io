---
title: "Path Loss Prediction Model of 5G Signal Based on Fusing Data and XGBoost—SHAP Method"
authors:
- "Tingting Xu"
- "Nuo Xu"

---

# Path Loss Prediction Model of 5G Signal Based on Fusing Data and XGBoost—SHAP Method

**Author Information**  
Tingting Xu<sup>1</sup>, Nuo Xu<sup>1</sup>


<sup>1</sup> Chongqing University of Posts and Telecommunications  



## Abstract

The accurate prediction of path loss is essential for planning and optimizing communication networks, as it directly impacts the user experience. In 5G signal propagation, the mix of varied terrain and dense high-rise buildings poses significant challenges. For example, signals are more prone to multipath effects and occlusion and shadowing occur often, leading to high nonlinearities and uncertainties in the signal path. Traditional and shallow models often fail to accurately depict 5G signal characteristics in complex terrains, limiting the accuracy of path loss modeling. To address this issue, our research introduces innovative feature engineering and prediction models for 5G signals. By utilizing smartphones as signal receivers and creating a multimodal system that captures 3D structures and obstructions in the N1 and N78 bands in China, the study aimed to overcome the shortcomings of traditional linear models, especially in mountainous areas. It employed the XGBoost algorithm with Optuna for hyperparameter tuning, improving model performance. After training on real 5G data, the model achieved a breakthrough in 5G signal path loss prediction, with an R2 of 0.76 and an RMSE of 3.81 dBm. Additionally, SHAP values were employed to interpret the results, revealing the relative impact of various environmental features on 5G signal path loss. This research enhances the accuracy and stability of predictions and offers a technical framework and theoretical foundation for planning and optimizing wireless communication networks in complex environments and terrains.



Keywords: 5G signal path loss,  Multimodal data feature fusion,  XGBoost,  Machine learning,  Complex terrain data



```{admonition} Presentation Information
:class: note

**Submission ID:** 7778  
**Session:** [Perception Perceived Street Path](./Session_G6/) 
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 10:45 – 12:00
**Venue:** room 6
```