# Classical ML
##############################################################################################################################

1. Bayes Classifier [x]



Bayes Classifier :
        A program to learn a naïve Bayes classifier and used to predict class labels of test data. Laplacian smoothing with α = 1 has been implemented. The learned classifier is tested on test instances with unknown class labels, and the predicted class labels for the test instances is printed as output. 

Libraries : Numpy
##############################################################################################################################

2. KNN [x]



KNN :
        A program to use a K-nearest neighbor to predict class labels of test data. Euclidean distance is used as the distance metric. (K=5). The learned classifier is tested on test instances with unknown class labels, and the predicted class labels for the test instances is printed as output.

Libraries : Numpy
##############################################################################################################################

3. Classifier Evaluation [x]



Decision Tree vs Naive Bayes :
        A program to implement Decision Tree and Naive Bayes Classifier and perform a classification task. 
A template to generate data : as: Ɗ(x,y) where x is a 2 dimensional input → x =[x1, x2] ~ U(-1,1) x U(-1,1) and y = sign (x12 + x22 - 0.5) where U denotes Uniform Distribution.
I have generated an appropriate number of samples such that I was able to learn the classifier.
For each of the above classifiers, I have performed k-fold cross validation and plotted the train and test accuracy (y-axis) with varying ‘k’ (1<=k<=10) (x-axis). 

Libraries : Numpy, Matplotlib, Sklearn
##############################################################################################################################

4. SVM [x]



SVM :
       A program to implement SVM classifier on UCI breast cancer dataset to perform the classification task.  The dataset is split into 70:30 as train and test dataset. 
a. svm_models() : to implement SVM models with different kernels and bar plot the test accuracy.
b. ploy_kernel_var_deg() : to implement SVM with polynomial kernel and plot the execution time w.r.t. the degree of the polynomial ranging from 1 to 3.
c. custom_kernel() : to implement a custom kernel which is of the form K(X,Y)= k*XYT+θ, where k and θ, are constants.
d. svm_custom_kernel() : to implement SVM classifier with the above defined custom kernel and report the test accuracy.  

Libraries : Numpy, Matplotlib, Seaborn, Sklearn
##############################################################################################################################

5. Fraud Detection [x]



Data taken from the UCI data repository (Taiwan Dataset)

Decision Tree :
        This research aimed at the case of customers default payments in Taiwan and compares the predictive accuracy of probability of default among six data mining methods. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. Because the real probability of default is unknown, this study presented the novel alpha Smoothing Method to estimate the real probability of default. With the real probability of default as the response variable (Y), and the predictive probability of default as the independent variable (X), the simple linear regression result (Y = A + BX) shows that the forecasting model produced by artificial neural network has the highest coefficient of determination; its regression intercept (A) is close to zero, and regression coefficient (B) to one. 
Therefore, among the six data mining techniques, I have compared various classical algorithms and concluded Decision Tree Model to be best.
Customer default payment prediction using an optimized Decision Tree Model with the top 15 features selected among 22 for best results. F1-Score achieved: 0.5 on test set. Concluded that a Neural Network can learn more complex patterns.

Libraries : Numpy, Pandas, Sklearn, Imblearn
##############################################################################################################################

6. Clustering [x]



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
##############################################################################################################################

7. Principle Component Analysis [x]



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
##############################################################################################################################

8. SVD and Low Rank Approximation for Movie Recommender system[x]

A project to predict the rating of unrated movies from a dataset containing large  samples of ratings from users for different movies. The project uses dimensionality reduction to reduce the number of redudant features and understand an underlying pattern.

I've used Spectral Value Decomposition to reduce the high dimensional matrix into its components and Low Rank Approximation to extract important features of 20. 

Libraries : Numpy, Pandas, SciPy
##############################################################################################################################
