# Project Title: Customer Segmentation using Clustering

## Project Overview
This project applies clustering techniques to segment customers based on their demographic and behavioral attributes. The analysis includes data preprocessing, exploratory data analysis (EDA), dimensionality reduction with Principal Component Analysis (PCA), and clustering using K-Means and Agglomerative Clustering.

## Key Objectives
- Identify distinct customer segments using clustering algorithms.
- Analyze the characteristics of each cluster to uncover actionable business insights.

## Dataset
The dataset contains customer information, including:
- **Demographics**: Age, height, weight, etc.
- **Behavioral Attributes**: Rental purpose, ratings, etc.

### Data Cleaning and Preprocessing
- Handled missing values using median (numeric) and mode (categorical).
- Capped outliers in variables such as `age`.
- Converted inconsistent units (e.g., weight and height).
- Encoded categorical features using one-hot and label encoding.
- Standardized features to ensure optimal clustering performance.

### Exploratory Data Analysis (EDA)
- Identified variable distributions using boxplots, scatterplots, and bar charts.
- Analyzed relationships between key features.

### Principal Component Analysis (PCA)
- Reduced dimensionality to 80 components, capturing ~95% of variance.
- Ensured computational efficiency for clustering algorithms.

## Clustering Methods
### K-Means Clustering
- Used the elbow method and silhouette scores to determine the optimal number of clusters.
- Applied clustering to a sample dataset due to computational constraints.

### Agglomerative Clustering
- Used dendrograms and silhouette scores to identify the cluster count.

## Results
- Segmented customers into distinct groups based on their demographic and behavioral characteristics.
- Visualized clusters using bivariate plots and boxplots for better interpretability.

## Insights
- Clusters revealed key customer traits, such as:
  - Preferences for specific rental purposes (e.g., weddings or formal events).
  - Differences in age and height distributions among clusters.
  - Variations in fit preferences and ratings.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries Used**: pandas, numpy, matplotlib, seaborn, scikit-learn

## Potential Applications
- Tailored marketing campaigns targeting specific customer segments.
- Inventory management based on cluster preferences.
- Enhanced customer satisfaction by addressing distinct cluster needs.

## Future Work
- Validate clustering results using additional metrics (e.g., Davies-Bouldin Index).
- Extend analysis to include external datasets for better generalizability.
- Automate the clustering process for real-time segmentation.

## Instructions to Run
1. Run the notebook `Project_2_ML.ipynb` step by step.
2. Visualize and analyze the output to interpret the clusters.


