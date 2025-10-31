# project summary
The Iris dataset was clustered using the K-Means++ algorithm to group flowers without labels. After scaling the numeric features and applying the elbow and silhouette methods, four clusters (k=4) were chosen. PCA was used to visualize the clusters in 2D space.

Comparing clusters to the real species showed that Setosa, Versicolor, and Virginica were well separated, with a fourth “Cloned” group emerging as a Setosa sub-cluster. The summary of averages confirmed Setosa had the smallest petals, Virginica the largest, and Versicolor was intermediate.

Overall, K-Means++ effectively reproduced the natural Iris groupings while revealing an additional subtle pattern within Setosa.
