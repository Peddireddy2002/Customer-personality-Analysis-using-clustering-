# Customer-personality-Analysis-using-clustering-

Data: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis

## Project Overview
This project focuses on segmenting customers into distinct groups based on their purchasing behaviors and demographics using unsupervised learning techniques. By applying various clustering algorithms, the goal is to uncover meaningful patterns that can inform targeted marketing strategies and personalized customer experiences.

## Dataset
The dataset utilized in this project is sourced from Kaggle and contains detailed information about customers' demographics, purchasing habits, and responses to marketing campaigns. Key features include:

Demographics: Age, education level, marital status, income, number of children, and number of teenagers in the household.

Purchasing Behavior: Amount spent on various product categories (e.g., wine, fruits, meat, fish, sweets, gold).

Marketing Interaction: Number of purchases made with a discount, and responses to five different marketing campaigns.

## Data Preprocessing
### Handling Missing Values: Addressed missing data through appropriate imputation or removal strategies.

Feature Engineering: Created new features such as 'Days_As_Customer' to represent the duration of customer relationships.

Encoding Categorical Variables: Applied one-hot encoding to convert categorical variables into numerical format.

Normalization: Standardized numerical features to ensure uniformity in scale, facilitating effective clustering.

## Exploratory Data Analysis (EDA)
Statistical Summary: Generated descriptive statistics to understand the central tendencies and spread of the data.

Correlation Analysis: Examined relationships between numerical features to identify potential patterns.

Visualization: Utilized histograms, box plots, and scatter plots to visualize distributions and detect outliers.

## Clustering Techniques
The following clustering algorithms were applied to segment customers:

K-Means Clustering:

Utilized the Elbow Method and Silhouette Score to determine the optimal number of clusters.

Grouped customers into clusters based on purchasing behavior and demographics.

K-Medoids (Partitioning Around Medoids):

Employed for its robustness to noise and outliers, providing alternative cluster centers.

Agglomerative Hierarchical Clustering:

Built a hierarchy of clusters using a bottom-up approach, visualized through dendrograms.

BIRCH (Balanced Iterative Reducing and Clustering using Hierarchies):

Applied for large datasets to efficiently identify clusters with a hierarchical structure.

DBSCAN (Density-Based Spatial Clustering of Applications with Noise):

Identified clusters based on density, effectively handling noise and outliers.

OPTICS (Ordering Points To Identify the Clustering Structure):

Captured clusters of varying densities and maintained cluster hierarchy.

Results and Insights
Customer Segments: Identified distinct customer segments with unique characteristics and behaviors.

Targeted Marketing: Provided insights into which customer groups are more responsive to specific marketing campaigns.

Product Preferences: Highlighted product categories that are more popular among certain customer segments.

Income and Spending Patterns: Revealed correlations between income levels and spending habits across different product categories.

## Tools and Technologies
Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Clustering Algorithms: K-Means, K-Medoids, Agglomerative Clustering, BIRCH, DBSCAN, OPTICS

## Conclusion
This analysis demonstrates the power of unsupervised learning in uncovering hidden patterns within customer data. By segmenting customers based on their behaviors and demographics, businesses can tailor their marketing strategies to meet the specific needs of each group, ultimately enhancing customer satisfaction and loyalty.

