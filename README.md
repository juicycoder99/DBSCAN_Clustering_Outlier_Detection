# DBSCAN Clustering and Outlier Detection

Density-based clustering with DBSCAN: synthetic concentric-ring separation, epsilon tuning from the
k-distance graph, and robust outlier detection on the Iris dataset.

The full implementation and analysis, covering eleven exercises, is in
[`dbscan_clustering_outliers.ipynb`](dbscan_clustering_outliers.ipynb).

## Topics covered

- `make_circles` data and why k-means cannot separate concentric rings.
- DBSCAN defaults (`eps=0.5`, `min_samples=5`) and the role of `eps`.
- The sorted k-distance graph and reading `eps` from its knee.
- Recovering the two circles with DBSCAN and the meaning of the `-1` (noise) label.
- DBSCAN on the Iris dataset with 20 injected uniform outliers, compared to k-means.
- Outlier-detection rate (recall/precision) and how robustness degrades as contamination grows.

## Running it

```bash
pip install numpy matplotlib scikit-learn
jupyter notebook dbscan_clustering_outliers.ipynb
```

## Files

| File | Description |
|------|-------------|
| `dbscan_clustering_outliers.ipynb` | Full implementation and analysis covering all 11 exercises |
| `PROJECT_BRIEF.pdf` | Project brief (goals, objectives, outcomes) |
