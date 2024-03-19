# Dynamic Classifier Selection in Imbalanced Data Scenarios

## Authors: 
Yusuf Yesilyurt and Raveen Ahmed\
Department of Systems and Computer Networks, Wroclaw University of Science and Technology, Wroclaw, Poland

### Abstract:
In many critical domains like medical diagnosis and fraud detection, dealing with imbalanced datasets presents significant hurdles. These datasets often lead to biased predictions that favor the majority class, making it challenging to achieve accurate results. Dynamic Classifier Selection (DCS) has emerged as a potent strategy to tackle this issue. It works by intelligently selecting the most appropriate classifier for each data instance based on local performance estimates.

This paper delves into the effectiveness of three key DCS techniques: Overall Local Accuracy (OLA), Local Class Accuracy (LCA), and META-DES (META-learner for Dynamic Ensemble Selection), specifically in the context of imbalanced datasets. To thoroughly assess these techniques, the study conducts a comprehensive evaluation using 20 real-world datasets with varying levels of class imbalance.

Before integrating these techniques into the DCS frameworks, the study incorporates rigorous validation and hyperparameter tuning of base classifiers. Evaluation metrics such as F1 scores and Matthews Correlation Coefficient (MCC) are employed, supplemented by visual representations like scatter plots and bar charts.

The findings reveal that LCA and META-DES consistently outperform OLA across different degrees of class imbalance. This underscores the critical role of DCS algorithms in enhancing classification accuracy in scenarios with imbalanced data.
