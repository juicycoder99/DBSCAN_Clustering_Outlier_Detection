# Data Mining (CS405/CS505) — Assignment 4: DBSCAN

Coursework for **Data Mining (CS405/CS505)**, Bishop's University.

Density-based clustering with DBSCAN: a synthetic two-circles case where k-means fails, choosing
`eps` from the k-distance graph (Schubert's heuristic), and using DBSCAN for outlier detection on
the Iris dataset. The full solution, answering all eleven questions, is in
[`Assignment4_DBSCAN_Outliers.ipynb`](Assignment4_DBSCAN_Outliers.ipynb).

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
jupyter notebook Assignment4_DBSCAN_Outliers.ipynb
```

## Files

| File | Description |
|------|-------------|
| `Assignment4_DBSCAN_Outliers.ipynb` | Full solution with answers to all 11 questions |
| `Assignment 4.pdf` | Assignment description |
