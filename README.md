
# Customer Segmentation Report for Arvato Financial Services
## BLOG POST: https://fahadalaraik.medium.com/customer-segmentation-report-for-arvato-financial-services-12b9f1ee0bfe
## Table of Contents
 * [Project Overview](#project-overview)
 * [Problem Statement](#problem-statement)
 * [Objective](#objective)
 * [Metrics](#metrics)

### Libraries Used:
 *  numpy==1.23.5
 *  pandas==1.5.2
 *  matplotlib==3.7.2
 *  seaborn==0.12.2
 *  sklearn==1.2.0
 *  kmodes==0.12.2
 *  xgboost==2.0.3

### to install dependencies
`pip install -r requirements.txt`

 
### Project Overview
The project entails analyzing demographics data for customers of a mail-order sales company in Germany and comparing it with demographics information for the general population. The aim is to utilize unsupervised learning techniques for customer segmentation, identifying segments that best represent the core customer base of the company. Subsequently, this segmentation model will be applied to a third dataset containing demographics information for targets of a marketing campaign for the company. The goal is to predict which individuals are most likely to convert into customers. The datasets used are provided by Bertelsmann Arvato Analytics, offering a real-life data science task.

### Problem Statement:
The primary objective is to understand the customer base of the mail-order sales company by segmenting the population based on demographics data. This involves identifying similarities and differences between the customer demographics and the general population. Furthermore, the project aims to predict potential customers from a marketing campaign target dataset. By achieving this, the company can enhance its marketing strategies, tailor its products/services, and optimize customer acquisition efforts.

### Objective:
The objective of this project is to analyze demographics data for customers of a mail-order sales company in Germany and compare it against demographics information for the general population. Using unsupervised learning techniques, the aim is to perform customer segmentation, identifying segments that best describe the core customer base of the company. Subsequently, this segmentation will be applied to a third dataset containing demographics information for targets of a marketing campaign, enabling the prediction of individuals most likely to convert into customers for the company. The ultimate goal is to provide actionable insights to optimize marketing strategies and target potential customers more effectively.

### Metrics
1. **Inertia (for Unsupervised Learning)**:
   - Inertia, also known as within-cluster sum of squares, gauges the tightness of clusters by computing the sum of squared    distances of samples to their nearest cluster center.
   - A lower inertia indicates that the clusters are more tightly packed, suggesting a better segmentation.

2. **ROC (Receiver Operating Characteristic) Curve (for Predictive Modeling)**:
   - The ROC curve illustrates the trade-off between true positive rate (sensitivity) and false positive rate (1-specificity) across different threshold values.
   - A higher area under the ROC curve (AUC) indicates better model performance in distinguishing between positive and negative instances.

3. **AUC (Area Under the ROC Curve) (for Predictive Modeling)**:
    - AUC quantifies the overall performance of a classification model by computing the area under the ROC curve.
    - A higher AUC value signifies better discrimination ability of the model across various threshold values.

### Acknowledgments
Thanks to Udacity and Arvato for this challenging project
