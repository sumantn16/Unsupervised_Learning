Here I have considered the Wine dataset.
The objective of this mini project is: Dimensionality Reduction through Principal Component Analysis(PCA) on the Wine data set.
Data Set -  https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data Links to an external site.
Data details : https://archive.ics.uci.edu/ml/machine-learning-databases/wine/ Links to an external site.
Steps –
PCA involves following broad level steps –
1.	Standardize the d-dimensional dataset.
2.	Construct the covariance matrix.
3.	Decompose the covariance matrix into its eigenvectors and eigenvalues.
4.	Select k eigenvectors that correspond to the k largest eigenvalues,  where k is the dimensionality of the new feature subspace ( k≤d ).
5.	Construct a projection matrix W from the "top" k eigenvectors.
6.	Transform the d-dimensional input dataset x using the projection matrix W to obtain the new k-dimensional feature subspace
