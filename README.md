Prediction-using-Unsupervised-ML

OBJECTIVE-Clustering of Iris Dataset
From the given ‘Iris’ dataset, predict the optimum number of clusters and represent it visually.

![image](https://github.com/Athira2103/Spark-Internship_task2/assets/31879762/c584f2eb-16b8-49e1-8971-100d2732bfc0)


ALGORITHM USED - K-Means

K-means is a centroid-based algorithm, or a distance-based algorithm, where we calculate the distances to assign a point to a cluster. In K-Means, each cluster is associated with a centroid.

Workflow behind Implemention of K-Means Clustering

Choose the number of clusters k

Select k random points from the data as centroids

Assign all the points to the closest cluster centroid

Recompute the centroids of newly formed clusters

Repeat steps 3 and 4
