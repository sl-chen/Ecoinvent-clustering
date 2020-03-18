# Ecoinvent-clustering
Trying to apply machine learning to explore the data structure or hidden information in ecoinvent database

The input features are inventories of activities or lca scores from different lcia methods

Dimensionality reduction technique is PCA, engineering solutions like combining similar bioflows and removal of less important elementary flows are also applied

Applied clustering algorithms are DBSCAN, Agglomerative Clustering, Birch, OPTICS and MeanShift from scikit-learn library, HDBSCAN and self-organizing map are also used

Unfortunately, no useful information has been founded yet, as the whole database seems more like one cluster with some outliers
