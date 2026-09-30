# J1 — Supervised & Unsupervised Learning

**Gate Track J — AI/ML Modeling**

## Project Structure

```
Supervised_and_unsupervised_learning/
├── notebooks/
│   ├── J1_supervised_random_forest.ipynb   ← Part A: Ensemble + Baseline comparison
│   └── J1_unsupervised_kmeans_pca.ipynb    ← Part B: Clustering + 2D PCA plot
├── data/                                   ← (empty — datasets loaded via scikit-learn)
├── .gitignore
└── README.md
```

## Part A — Supervised Learning
- **Dataset**: Breast Cancer Wisconsin (via `sklearn.datasets`)
- **Models**: Dummy Classifier (naive baseline) → Logistic Regression → Random Forest
- **Metrics**: Accuracy, Precision, Recall, F1, ROC-AUC
- **Goal**: Show ensemble outperforms simpler baselines

## Part B — Unsupervised Learning
- **Dataset**: Iris features only (labels dropped — treated as unlabeled)
- **Method**: K-Means with elbow + silhouette to choose K
- **Viz**: PCA → 2D scatter plot with cluster labels
- **Goal**: Identify and interpret natural groupings in the data
