# Progress

## 2026-11-07

### Added
- Created `kmeans clustering/` with:
  - `mall_customers.csv` - a synthetic dataset of 150 mall customers (`CustomerID`, `Annual_Income_k`, `Spending_Score`) with 3 hidden groups.
  - `kmeans clustering.ipynb` - a beginner-friendly K-Means notebook covering:
    - what clustering and K-Means are
    - loading and exploring the CSV
    - feature scaling with `StandardScaler`
    - choosing `k` with the elbow method
    - training and visualizing K-Means with scikit-learn
    - interpreting and naming customer segments
    - predicting the segment of a new customer
    - implementing K-Means from scratch with NumPy
- Added the K-Means notebook to the practices table in `README.md`.

### Verification
- Executed the notebook end-to-end with `nbclient`; all cells ran without errors and plots are embedded in the saved notebook.

### Next steps
- Experiment with different values of `k` and compare the results.
- Try K-Means on a real dataset such as the classic Mall Customers dataset.
- Explore other clustering algorithms such as hierarchical clustering and DBSCAN.
