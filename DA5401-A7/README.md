# DA5401 A7:  Imputation via Regression for Missing Data

_Name:Garima Sikka_

_Roll no: DA25E052_

_Date: 18 Oct 2025_

This assignment tackles the complex task of land cover classification using the UCI Landsat Satellite dataset. The primary objective is to accurately identify one of six distinct land cover types based on multi-spectral satellite imagery data. Accurate classification is a cornerstone of environmental science and urban planning, aiding in applications such as monitoring deforestation, managing agricultural resources, and tracking urbanization. The dataset's high dimensionality and the potential for overlapping class characteristics make this a challenging and realistic machine learning problem, requiring more than simple accuracy metrics for a thorough evaluation.

Our core focus is on rigorous model selection by comparing a diverse set of classifiers, ranging from simple baselines to more complex algorithms. To move beyond single-score metrics, we will perform a deep analysis using Receiver Operating Characteristic (ROC) curves and Precision-Recall Curves (PRC), specifically adapted for the multi-class setting using a One-vs-Rest (OvR) approach. This method will allow us to visualize and quantify each model's performance across all possible decision thresholds, providing critical insights into their ability to balance true positives against false alarms. The final analysis will identify not only the best- and worst-performing models but also explain the reasons for their performance based on a careful interpretation of the evaluation curves.

**Dataset Link:** [UCI Machine Learning Repository -
Satimage](https://archive.ics.uci.edu/dataset/146/statlog+landsat+satellite)
