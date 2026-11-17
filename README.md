A collection of my Machine Learning learning notes, experiments, and practice notebooks.

I'm a student learning **Machine Learning**, and this repository is where I document my progress by writing code, experimenting with concepts, and practicing along the way.

## About This Repository

This repository will grow as I continue learning. I'll add new notebooks, implementations, and experiments as I explore different topics in Machine Learning and Data Science.

## Practices

| # | Topic | Notebook |
|---|---|---|
| 01 | Pandas Basics | [`pandas_in_short.ipynb`](pandas_in_short.ipynb) |
| 02 | K-Means Clustering | [`Unsupervised learning/k-means/kmeans clustering.ipynb`](Unsupervised%20learning/k-means/kmeans%20clustering.ipynb) |
| 03 | DBSCAN Clustering | [`Unsupervised learning/DBSCAN/DBSCAN.ipynb`](Unsupervised%20learning/DBSCAN/DBSCAN.ipynb) |
| 04 | Hierarchical Clustering | [`Unsupervised learning/Hierarchical/Hierarchical clustering.ipynb`](Unsupervised%20learning/Hierarchical/Hierarchical%20clustering.ipynb) |

### Unsupervised Learning Notebooks

All three clustering notebooks follow the same learning path: a plain-English explanation, real
Python code, a synthetic dataset, charts for every idea, an interactive playground, and a
from-scratch implementation checked against scikit-learn or SciPy.

| Notebook | Dataset | What it covers |
|---|---|---|
| **K-Means** | [`mall_customers.csv`](Unsupervised%20learning/k-means/mall_customers.csv) (150 customers) | Elbow method, feature scaling, centroids, predicting the group of a new point |
| **DBSCAN** | [`dbscan_points.csv`](Unsupervised%20learning/DBSCAN/dbscan_points.csv) (278 points) | Density, core/border/noise points, `eps` and `min_samples`, k-distance graph, outlier detection |
| **Hierarchical** | [`hierarchical_points.csv`](Unsupervised%20learning/Hierarchical/hierarchical_points.csv) (282 points) | Dendrograms, single/complete/average/Ward linkage, cutting the tree, cophenetic correlation |

Each folder contains the notebook **and** the CSV it uses, so the notebooks run without any
external downloads. The datasets are synthetic and include a `true_group` column (where present)
only for comparing the discovered clusters against the known truth.

## Goals

- Learn ML concepts step by step.
- Practice with Python and relevant libraries.
- Understand algorithms through code and experiments.
- Keep track of my learning progress.
- Share my work and learning journey publicly.

## Tech Stack

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- SciPy
- Scikit-learn
- ipywidgets *(for interactive sliders and plots)*

## Progress

This is just the beginning. More practices and topics will be added over time.

---

**Learning in public, one practice at a time.**
