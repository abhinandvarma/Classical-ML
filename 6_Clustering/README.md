# Clustering [x]



Dataset Description:
        Instances in this dataset contain audio features extracted from 1059 wave files. The data is labelled based on the geographical origin of music (33 classes/countries/areas).
Note: Use the class labels only to verify the performance of the clustering.
116 columns are audio features of the track, and the last one columns are the origin of
the music. Source: http://archive.ics.uci.edu/ml/datasets/geographical+original+of+music

K-means Clustering
        The task is to perform clustering on the given dataset using k-means algorithm and experiment with the following specifications.
Initialization: Random
Distance measure: Euclidean Distance
Evaluation metrics: Rand Index, SSE (same as WCSS)
Stopping Criteria: Your choice (simple loop with maximum 200 iterations is enough)
Plotted the Rand Index and SSE with the 8 different k values.

Libraries : Numpy, Pandas, Matplotlib, Sklearn
