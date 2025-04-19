```markdown
# 🌸 Clustering Analysis on Iris Dataset

This project demonstrates and compares the performance of various clustering algorithms
(K-Means, Hierarchical, and Mean Shift) on the Iris dataset using different preprocessing strategies (Normalization and PCA).

## 📊 Algorithms Used

1. **K-Means Clustering**
2. **Hierarchical Clustering (Ward Linkage)**
3. **Mean Shift Clustering**

## 🧪 Preprocessing Strategies

- **Original**: Raw feature data from the Iris dataset.
- **Normalized**: Standardized data using `StandardScaler`.
- **PCA**: Principal Component Analysis applied directly to original data (2 components).
- **Normalized + PCA**: PCA applied after standardization.

## 📈 Evaluation Metrics

Each clustering output is evaluated using the following metrics:
- **Silhouette Score**: Measures cohesion and separation.
- **Calinski-Harabasz Index**: Ratio of between-cluster dispersion to within-cluster dispersion.
- **Davies-Bouldin Index**: Lower values indicate better clustering.

## 📁 Project Structure

```
.
├── clustering_analysis.py       # Main script to run clustering and evaluation
├── clustering_results.csv       # Exported results with scores
├── dendrogram.png               # Optional saved dendrogram visualization
└── README.md                    # This file
```

## 🧵 How to Run

1. Make sure you have Python 3.x installed.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib scikit-learn scipy
   ```
3. Run the analysis:
   ```bash
   python clustering_analysis.py
   ```

## 📌 Notes

- The script prints evaluation results for all combinations.
- A dendrogram is displayed for hierarchical clustering on original data.
- You can modify the number of clusters (`3, 4, 5`) or add DBSCAN/GMM for further comparison.

## 📚 Dataset Info

- **Source**: `sklearn.datasets.load_iris()`
- **Features**: Sepal length, Sepal width, Petal length, Petal width
- **Classes**: Setosa, Versicolor, Virginica

## 🤝 License

This project is open-source and available under the MIT License.
```
