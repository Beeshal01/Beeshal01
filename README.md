# Customer Churn Analysis (Stage 2)

This repository contains the deliverables for Stage 2 of the Customer Churn Analysis project. The goal is to prepare the dataset for analysis and perform clustering to identify customer segments.

## Repository Structure

- **/Data_Preparation/**: Contains the preprocessed dataset, training/testing sets, and scaling techniques documentation.
- **/Clustering_Analysis/**: Includes the results of clustering analysis, such as the optimal number of clusters, the trained K-Means model, and cluster visualizations.

## Deliverables

1. **Data Preparation**:
   - Preprocessed dataset with missing values addressed and categorical variables encoded.
   - Training and testing sets with an 80/20 split.
   - Documentation of scaling techniques applied to the data.
   
2. **Clustering Analysis**:
   - Elbow method used to determine the optimal number of clusters (k = 4).
   - Trained K-Means clustering model saved as `KMeans_Model.pkl`.
   - Visualizations of clusters and detailed insights about each segment.

## Instructions

- To view the preprocessed data, check the `Preprocessed_Dataset.csv` file.
- To reproduce the K-Means clustering model, use the provided code and model file in the `/Clustering_Analysis/` folder.
- For a detailed explanation of the insights derived from the clustering analysis, refer to `Cluster_Interpretation.pdf`.
