# Customer Personality Analysis 🧐

Personality analysis of grocery store customers using **K-Means**, **Agglomerative Clustering**, **Mean Shift**, and **DBSCAN** clustering techniques. This project applies unsupervised clustering to segment customers based on their traits and behaviors, helping businesses optimize engagement and improve marketing strategies.

---

## Table of Contents
- [What is Customer Personality Analysis?](#what-is-customer-personality-analysis)
- [Clustering Techniques](#clustering-techniques)
- [Data Workflow](#data-workflow)
- [Observations](#observations)
- [Sample Visualizations](#sample-visualizations)
- [Setup](#setup)
- [Todos](#todos)
- [Acknowledgements](#acknowledgements)
- [Citation](#citation)
- [Connect with Me](#connect-with-me)

---

## What is Customer Personality Analysis?

Customer Personality Analysis (or profiling) helps businesses understand customer preferences, needs, and motivations by categorizing them into distinct groups. Clustering methods like **K-means**, **Agglomerative Clustering**, and **DBSCAN** uncover hidden patterns and trends, enabling businesses to:
- Develop improved marketing strategies
- Enhance customer engagement
- Build better products and services
- Enable effective segmentation and targeting

---

## Clustering Techniques

### 1. **K-Means Clustering**
- **Type**: Centroid-based
- **Description**: Partitions data into `K` clusters represented by their centroid (mean of cluster points).
- **Key Points**: 
  - Requires `K` to be defined in advance.
  - Assumes clusters are spherical.
  - Computationally efficient.

### 2. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
- **Type**: Density-based
- **Description**: Identifies dense regions as clusters, robust to noise and outliers.
- **Key Points**: 
  - Does not require `K`.
  - Effective for irregularly shaped clusters.

### 3. **Agglomerative Clustering**
- **Type**: Hierarchical
- **Description**: Iteratively merges data points or clusters based on proximity.
- **Key Points**: 
  - Does not require `K` in advance.
  - Can form clusters of varying shapes and sizes.
  - Computationally intensive for large datasets.

### 4. **Mean Shift**
- **Type**: Mode-seeking
- **Description**: Identifies dense regions by shifting points toward the mode of their local distribution.
- **Key Points**: 
  - Does not require `K`.
  - Suitable for clusters of various shapes.
  - Computationally expensive for high-dimensional data.

---

## Data Workflow

1. **Data Cleaning and Feature Engineering**: Preprocessed and refined the dataset.
2. **Dimensionality Reduction**: Applied **PCA** for improved insights and visualization.
3. **Visualization and Elbow Method**: Determined the optimal number of clusters.
4. **Clustering Application**: Implemented **K-Means**, **DBSCAN**, **Mean Shift**, and **Agglomerative Clustering**.
5. **Customer Profiling**: Segmented customers to enable:
   - Targeted marketing
   - Personalized experiences
   - Enhanced engagement

---

## Observations

Key insights derived from the clustering process:
- **Cluster 0**: Older parents (2-4 family members), including single parents.
- **Cluster 1**: High-income non-parents with smaller families (up to 2 members), spanning all ages.
- **Cluster 2**: Younger parents with one child, family size up to 3 members.
- **Cluster 3**: Lower-income parents with larger families (3-5 members).

---

## Sample Visualizations
- **Correlation Matrix**: Analyzed feature correlations.
- **Elbow Method**: Identified the optimal number of clusters.
- **PCA 3D Visualization**: Visualized data in reduced dimensions.
- **Clustering Visualizations**: Showed cluster distribution for each method.

---


