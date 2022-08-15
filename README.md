###Project Name
CapstoneProject2 - Unsupervised Machine Learning

###Project Description
This project looks into the USArrests.csv dataset (included in this repository). It begins by cleaning the data, performing PCA to remove redundancies, and then finally creates kmeans and agglomerative clustering models. It was found that the kmeans model created had severe issues with overlapping clusters, which negatively impacts the silhouette score, resulting in a score of -0.04. The agglomerative clustering model rectified this issue, cutting down the number of clusters and achieved a silhouette score of 0.42, much higher than the kmeans model and gives greater confidence in the accuracy of prediced groupings.
