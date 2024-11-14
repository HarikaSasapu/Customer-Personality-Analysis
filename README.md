# Customer-Personality-Analysis
Personality Analysis of Grocery Store Customers using K-means, Agglomerative, Mean shift, and DBSCAN clustering techniques.
Customer Personality Analysis with K-Means, Agglomerative, Mean Shift, and Density-based Spatial Clustering 🧐

In this project, I perform unsupervised clustering on customer records from a grocery store's database. Customer segmentation is the practice of dividing customers into groups based on similarities, enabling businesses to optimize engagement and cater to diverse customer needs and behaviors effectively.
Table of Contents

What is Customer Personality Analysis?
Clustering Techniques
Data Workflow
Observations
Setup
Todos
Acknowledgements
Citation
Connect with Me
What is Customer Personality Analysis?

Customer Personality Analysis (or profiling) helps businesses understand customer preferences, needs, and motivations by categorizing them into distinct groups. Clustering methods like K-means, Hierarchical Clustering, and DBSCAN group customers with similar traits, uncovering hidden patterns and trends. The benefits of customer personality analysis include:
Improved marketing strategies
Enhanced customer engagement
Better product and service development
Effective segmentation and targeting
Clustering Techniques

1. K-means Clustering
K-means is a centroid-based clustering algorithm. It partitions data into K clusters, each represented by its centroid (mean of the cluster points). K-means assumes clusters are spherical and requires K to be defined in advance. It is computationally efficient and widely used in practice.
2. DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
DBSCAN is density-based, identifying dense regions as clusters. It does not require K and is robust to noise and outliers. DBSCAN is effective for datasets with irregularly shaped clusters.
3. Agglomerative Clustering
Agglomerative Clustering builds a hierarchical cluster structure by iteratively merging data points or clusters based on proximity. It can form clusters of varying sizes and shapes and does not require K in advance, but can be computationally intensive for large datasets.
4. Mean Shift
Mean Shift is a mode-seeking algorithm that identifies dense regions in data by iteratively shifting points toward the mode (densest region) of their local distribution. It does not require K and can identify clusters of various shapes, though it may be computationally expensive for high-dimensional data.
Data Workflow

Data Cleaning and Feature Engineering: Data preprocessing to refine the dataset.
Dimensionality Reduction: Principal Component Analysis (PCA) for improved insight and visualization.
Visualization and Elbow Method: Determine the optimal number of clusters.
Clustering Application: Implemented K-means, DBSCAN, Mean Shift, and Agglomerative clustering.
Customer Profiling: Segment customers based on behavior and preferences, providing insights for targeted marketing, personalized experiences, and enhanced customer engagement.


Sample Visualizations
Correlation Matrix
Elbow Method: Used to identify the optimal number of clusters.
PCA 3D Visualization: Display data in reduced dimensionality.
Clustering Visualizations: Visualize clusters for each method (e.g., K-means, Agglomerative, etc.).
Observations

From the clustering, I derived the following insights:
Cluster 0: Parents with 2-4 family members, typically older, including some single parents.
Cluster 1: Non-parents, high-income, smaller families (up to 2 members), spanning all ages.
Cluster 2: Younger parents with one child, family size up to 3 members.
Cluster 3: Lower-income parents with larger families (3-5 members).
Setup

Clone the repository:
git clone https://github.com/yourusername/Customer-Personality-Analysis.git
Navigate into the project directory:
cd path_to_repo
Create a virtual environment and install dependencies:
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
pip install -r requirements.txt
Run the analysis:
Open and run Clustering.ipynb in a Jupyter Notebook environment.
Todos

Experiment with these clustering models on larger datasets.
Productionize the models to generate weekly customer insights and reports.
Acknowledgements

Useful resources:
Clustering: Introduction, Different Methods, and Applications
Understanding Mean Shift Clustering and Implementation with Python

