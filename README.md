# Customer Clustering on Credit Card Dataset

This project applies unsupervised machine learning techniques to segment customers based on their credit card usage patterns. The goal is to identify distinct customer groups for potential targeted marketing strategies, product recommendations, or risk profiling.

## 📊 Project Overview

The pipeline includes:

1. **Exploratory Data Analysis (EDA):**
   Performed a comprehensive EDA to understand the distribution, trends, and potential correlations in the dataset.
2. **Elbow Method for K Selection:**
   Utilized the Elbow Method to determine the optimal number of clusters (`k`) for K-Means.
3. **K-Means Clustering:**
   Applied the K-Means algorithm to cluster customers into `k` segments.
4. **Dimensionality Reduction via PCA:**
   Reduced the feature space using Principal Component Analysis (PCA) to visualize the customer segments in two dimensions.

## 🧰 Tools and Libraries

* **Python**
* **Pandas** for data manipulation
* **Seaborn** for visualization
* **Scikit-learn** for clustering, PCA, and preprocessing

## 📁 Project Structure

```bash
.
├── data/
│   └── credit_card_data.csv          # Input dataset
├── notebooks/
│   └── clustering_analysis.ipynb     # Full EDA and clustering notebook
├── src/
│   └── clustering_utils.py           # Optional: helper functions
├── outputs/
│   ├── pca_clusters_plot.png         # Final PCA cluster visualization
│   └── elbow_method_plot.png         # Plot to determine optimal k
└── README.md                         # Project documentation
```

## 📌 Key Results

* Identified optimal number of clusters using inertia and the Elbow technique.
* Visualized clear separation of customer segments after applying PCA.
* Provided actionable insights for segment-specific strategies.

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/credit-card-customer-clustering.git
   cd credit-card-customer-clustering
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook notebooks/clustering_analysis.ipynb
   ```

## 📌 Future Work

* Try DBSCAN or Hierarchical Clustering for comparison.
* Add cluster profiling based on domain-specific business KPIs.
* Deploy clustering as a REST API for integration with BI tools.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

