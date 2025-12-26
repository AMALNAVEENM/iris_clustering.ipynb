# Iris Dataset Clustering Analysis

This assignment applies **KMeans** and **Hierarchical Clustering** to the classic Iris dataset to evaluate unsupervised learning techniques.

## Requirements Covered
- Loaded Iris dataset from `sklearn`
- Dropped species column (unsupervised setting)
- Applied **KMeans Clustering** with visualization and evaluation
- Applied **Hierarchical Clustering** with dendrogram and evaluation
- Compared both methods using **Adjusted Rand Index** and **Silhouette Score**
KMeans Results:
- Adjusted Rand Index (vs true labels): 0.7302
- Silhouette Score: 0.5522
Hierarchical Clustering Results:
- Adjusted Rand Index (vs true labels): 0.7615
- Silhouette Score: 0.5456
## Both KMeans and Hierarchical clustering successfully identified the natural grouping in the Iris dataset. KMeans achieved an Adjusted Rand Index of 0.73, while Hierarchical clustering (Ward linkage) reached 0.76, indicating slightly better alignment with the true species. The dendrogram confirmed that 3 is the optimal number of clusters, with a clear gap in merge distances.
