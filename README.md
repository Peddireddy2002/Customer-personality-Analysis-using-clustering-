# 🧠 Customer Personality Analysis Using Clustering

This project focuses on segmenting customers into distinct groups based on their purchasing behaviors and demographics using **unsupervised learning techniques**. By applying various clustering algorithms, we aim to uncover meaningful patterns that can support **targeted marketing strategies** and **personalized customer experiences**.

---

## 📊 Dataset
Data: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis

The dataset used is sourced from **Kaggle** and includes detailed information about customer demographics, purchasing habits, and marketing campaign responses.

### Key Features:

- **Demographics**: Age, education level, marital status, income, number of children and teenagers in the household.
- **Purchasing Behavior**: Spending amounts on categories like wine, fruits, meat, fish, sweets, and gold.
- **Marketing Interaction**: Purchases made with discounts and responses to five different marketing campaigns.

---

## 🧹 Data Preprocessing

- **Handling Missing Values**: Cleaned and imputed or removed missing data appropriately.
- **Feature Engineering**: Created new features such as `Days_As_Customer` to reflect customer relationship duration.
- **Encoding**: Applied one-hot encoding to categorical variables.
- **Normalization**: Standardized numerical features for uniform scale across variables.

---

## 📈 Exploratory Data Analysis (EDA)

- **Descriptive Statistics**: Summary of data distributions and central tendencies.
- **Correlation Analysis**: Studied relationships between numerical features.
- **Visualizations**: Histograms, box plots, and scatter plots used to detect distributions and outliers.

---

## 🔍 Clustering Techniques

We applied various clustering algorithms to analyze customer behavior and group similar profiles:

### ✅ K-Means Clustering
- Used **Elbow Method** and **Silhouette Score** to determine optimal clusters.
- Grouped customers based on purchasing behavior and demographics.

### ✅ K-Medoids (PAM)
- Chosen for its robustness to outliers and noise.
- Offers more stable centroids than K-Means in some scenarios.

### ✅ Agglomerative Hierarchical Clustering
- Bottom-up clustering method visualized using dendrograms.

### ✅ BIRCH (Balanced Iterative Reducing and Clustering using Hierarchies)
- Designed for large datasets.
- Built clusters efficiently with hierarchical structure.

### ✅ DBSCAN
- Identified clusters of high-density regions.
- Effectively handled outliers and noise.

### ✅ OPTICS
- Detected clusters of varying densities.
- Preserved hierarchical structure of clusters.

---

## 📌 Results and Insights

- **Customer Segments**: Distinct customer personas identified based on behavior.
- **Targeted Marketing**: Recognized segments more responsive to marketing.
- **Product Preferences**: Identified favorite categories for each cluster.
- **Income & Spending Patterns**: Discovered how income influences product choice.

---

## 🛠️ Tools and Technologies

- **Language**: Python
- **Libraries**: 
  - `Pandas`, `NumPy` – data manipulation
  - `Matplotlib`, `Seaborn` – data visualization
  - `Scikit-learn` – clustering and model evaluation
- **Algorithms Used**: K-Means, K-Medoids, Agglomerative Clustering, BIRCH, DBSCAN, OPTICS

---

## 📚 Conclusion

This project demonstrates the power of **unsupervised learning** in discovering valuable patterns in customer behavior. By segmenting customers based on their actions and demographics, businesses can build **highly personalized marketing strategies**, improve **customer engagement**, and increase **brand loyalty**.

---

## 📌 Future Enhancements

- Integrate with a dashboard for interactive visualization.
- Use advanced dimensionality reduction techniques (e.g., t-SNE, UMAP).
- Add prediction models for customer churn or campaign response.

---

