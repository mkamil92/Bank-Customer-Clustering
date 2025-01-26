# Bank Customer Clustering using K-Prototypes

## Overview

This repository contains a machine learning project for clustering bank customers using the K-Prototypes algorithm. The dataset used is from a direct marketing campaign by a Portuguese bank, and the goal is to group customers based on various demographic and behavioral features. The project demonstrates how to apply the K-Prototypes algorithm to a dataset containing both categorical and numerical data.

## Dataset

The data is collected from a direct marketing campaign by a Portuguese bank. The target variable (`deposit`) indicates whether a customer subscribed to a term deposit. The dataset contains various features, including:

- **age**: Age of the client
- **job**: Type of job
- **marital**: Marital status
- **education**: Level of education
- **default**: Whether the client has credit in default
- **balance**: Average yearly balance
- **housing**: Whether the client has a housing loan
- **loan**: Whether the client has a personal loan
- **contact**: Contact communication type
- **day**: Last contact day of the month
- **month**: Last contact month of the year
- **duration**: Duration of the last contact
- **campaign**: Number of contacts performed during this campaign
- **pdays**: Number of days since the client was last contacted
- **previous**: Number of contacts performed before this campaign
- **poutcome**: Outcome of the previous marketing campaign
- **deposit**: Whether the client subscribed to a term deposit (target variable)

## K-Prototypes Algorithm

The K-Prototypes algorithm is an extension of the K-Means clustering algorithm that can handle both categorical and numerical data. In this project, we use K-Prototypes to identify distinct customer segments based on the features provided.

### Key Steps:

1. **Data Preprocessing**:
   - Handle missing values (imputation).
   - Perform one-hot encoding on categorical features.

2. **Feature Selection**:
   - Feature selection using techniques like RandomForest and Recursive Feature Elimination (RFE).

3. **Clustering with K-Prototypes**:
   - Apply K-Prototypes clustering to group customers into distinct clusters.

4. **Model Evaluation**:
   - Evaluate clustering performance using Adjusted Rand Index (ARI) and Normalized Mutual Information (NMI).
   - Visualize clusters using PCA, t-SNE, and other plotting techniques.

5. **Visualization**:
   - Cluster visualization using PCA, t-SNE, and bar charts.

## Results

The clustering results are visualized using various methods to better understand the customer segments. Performance metrics such as ARI and NMI are used to evaluate the clustering quality. K-Prototypes ARI: 0.015579553283915899
K-Prototypes NMI: 0.014285838425723948
