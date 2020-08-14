# TSNE
# t-distributed Stochastic Neighbor Embedding

1. An unsupervised, randomized algorithm, used only for visualization

2. Uses a non-linear dimensionality reduction technique where the focus is on keeping the very similar data points close together in lower-dimensional space.

3. Preserves the local structure of the data using student t-distribution to compute the similarity between two points in lower-dimensional space.
4. t-SNE uses a heavy-tailed Student-t distribution to compute the similarity between two points in the low-dimensional space rather than a Gaussian distribution which helps to address the crowding and optimization problems.
5. t-SNE is not impacted by outliers
