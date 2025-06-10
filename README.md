# Customer-personality-Analysis-using-clustering-

Data: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis


WCSS (Within-Cluster Sum of Squares):
A lower WCSS indicates tighter clusters. It's a measure of how close the data points in a cluster are to the cluster centroid — the more compact the clusters, the lower the WCSS.

Silhouette Score:
This score evaluates how distinct and well-separated the clusters are. A higher silhouette value suggests that the objects are well matched to their own cluster and poorly matched to neighboring clusters — signaling effective clustering.

Elbow Method:
The “elbow point” is the spot on the WCSS vs. number of clusters plot where adding more clusters yields diminishing returns — the rate of improvement in WCSS slows noticeably.

PCA (Principal Component Analysis):
The goal is to retain most of the dataset's variability using fewer components. A common target is to select the number of components that collectively explain at least 80% of the total variance.

Eps in DBSCAN (Density-Based Spatial Clustering):
To determine the optimal eps, inspect the k-distance graph and look for the "knee" — the point where the curve shows a sharp increase. This marks the distance where points start becoming outliers rather than part of dense regions.

AIC/BIC (Akaike/Bayesian Information Criteria):
Both AIC and BIC penalize model complexity. Lower values indicate a better balance between model fit and complexity. The “optimal” model is typically found at the point where the curve flattens or shows an inflection.
