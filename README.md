# Customer Segmentation in E-commerce Using Clustering Techniques - Machine Learning Module, Final Project

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Methodology](#methodology)
  - [Clustering Algorithms](#clustering-algorithms)
  - [Feature Sets](#feature-sets)
- [Evaluation Metrics](#evaluation-metrics)
- [Key Findings](#key-findings)
- [Limitations and Future Work](#limitations-and-future-work)

## Introduction

E-commerce is a rapidly expanding sector within the retail industry, with growth significantly accelerated by the COVID-19 pandemic. The global e-commerce market is expected to total $6.3 trillion in 2024, with 20.1% of retail purchases taking place online [https://www.forbes.com/advisor/business/ecommerce-statistics/]. For any retail company, understanding the purchasing behavior of their customers is crucial. This information can be used for stock optimization, service improvement, and marketing activity planning.

Customer segmentation involves dividing customers into distinct groups based on shared characteristics or behaviors. This process enhances understanding of customer profiles and preferences, aiding in the optimization of product offerings and marketing strategies. For instance, effective customer segmentation is essential for developing recommendation systems that suggest items favored by similar users.

## Project Overview

This study investigates the application of clustering techniques for customer segmentation in the e-commerce domain. It compares various clustering algorithms and feature selection methods to identify optimal approaches for detecting distinct customer segments. The study uses a combination of clustering algorithms—K-means, Agglomerative, MeanShift, and DBSCAN—with feature sets comprising all attributes, principal components, and RFM (Recency, Frequency, Monetary) metrics.

## Methodology

### Clustering Algorithms

The following clustering algorithms were explored in this study:

- **K-Means Clustering**
- **Agglomerative Clustering**
- **MeanShift Clustering**
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**

### Feature Sets

Three different feature sets were evaluated:

- **All Attributes:** Using the complete set of customer attributes.
- **Principal Components:** Reduced feature set using Principal Component Analysis (PCA).
- **RFM Metrics:** Recency, Frequency, and Monetary metrics, commonly used in retail for customer segmentation.

## Evaluation Metrics

The models are evaluated using the following metrics:

- **Silhouette Coefficient:** Measures the similarity of an object to its own cluster compared to other clusters.
- **Davies-Bouldin Index:** Evaluates clustering algorithms based on intra-cluster and inter-cluster distances.
- **Computational Efficiency:** Assesses time and resources required for model training and prediction.
- **Practical Business Implications:** Examines the real-world applicability and value of the customer segments for business decision-making.

## Key Findings

- **K-means clustering with principal component features** produced the best model performance in terms of silhouette coefficient and Davies-Bouldin index.
- **RFM-based segmentation** provided greater business value, offering actionable insights for targeted marketing strategies.

## Limitations and Future Work

- The study's results are based on synthetic data, which may not fully capture the complexity of real-world e-commerce datasets.
- Future research should focus on using real-world data and advanced clustering techniques, such as deep learning-based approaches, to enhance model robustness and accuracy.
- Expanding the analysis to include different e-commerce platforms and geographic regions would provide a more comprehensive understanding of customer segmentation.


Feel free to reach out if you have any questions or need further assistance!

Happy clustering!
