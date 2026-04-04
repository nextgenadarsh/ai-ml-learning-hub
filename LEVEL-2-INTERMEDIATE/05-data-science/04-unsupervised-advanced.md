# Advanced Unsupervised Learning

## Overview
Covers advanced clustering algorithms, dimensionality reduction, manifold learning, topic modeling, and representation learning.

## Learning Objectives
- Implement DBSCAN, hierarchical clustering, and spectral clustering
- Use t-SNE and UMAP for visualization and representation
- Apply topic models (LDA) and evaluate coherence
- Learn unsupervised representation learning (autoencoders, contrastive learning)

## Example: UMAP visualization
```python
import umap
import matplotlib.pyplot as plt
from sklearn.datasets import load_digits

X, y = load_digits(return_X_y=True)
reducer = umap.UMAP(n_components=2)
X_reduced = reducer.fit_transform(X)
plt.scatter(X_reduced[:,0], X_reduced[:,1], c=y, cmap='Spectral', s=5)
plt.show()
```

## Exercises
- Cluster high-dimensional data with DBSCAN and analyze results
- Build an autoencoder for dimensionality reduction and compare with PCA
- Use contrastive learning (SimCLR) for representation learning
