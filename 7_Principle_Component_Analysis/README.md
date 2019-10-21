# Principle Component Analysis [x]



Dataset Description:
        Instances in this dataset contain audio features extracted from 1059 wave files. The data is labelled based on the geographical origin of music (33 classes/countries/areas).
Note: Use the class labels only to verify the performance of the clustering.
116 columns are audio features of the track, and the last one columns are the origin of
the music. Source: http://archive.ics.uci.edu/ml/datasets/geographical+original+of+music

Principle Component Analysis
        The task is to use PCA for dimensionality reduction and visualization. For a chosen k, do the following:
a)Projecting data into 2D plane using PCA and color code the clusters. Use scatter plot.
b) Choosing the following number of components for PCA: 2, 4, 8, 16, 32. Doing the clustering on the reduced dataset and compute the Rand index.

Libraries : Numpy, Pandas, Matplotlib, Sklearn
