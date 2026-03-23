# Gregory_Cooper_Advanced_Big_Data_and_Data_Mining_Lab_III



Analysis

Both Algorithms produced similar clusters. I would say that the K-Means Alorigthm produces better defined clusters. From the Scatter plot you can see less intersections between clusters than in the K-Memoids algorithm K-Means also has a slightly higher Silhouette score and Adjusted Rand Index.

Centroids in the K-Means cluster appear to converge at more central points in each cluster where as K-Memoids are not as central. In the Cluster 2 in K-memoids the cluster is more spreadout overlapping with where K-Means determins is actually cluster 0

In terms of what is best to use in which situation, K-means uses a Generated Mean value from the data while the Medoid uses an actual point. Depending on the data the mean may not exist or be best for defining clusters. I would say if the data has a mean that can articulate the true average of the data the K-Means would be best.



Issues:

This lab was more difficult than the previous, attempting to learn about K-Memoids and implementing proved challenging. Additionally K-Memoids required a different library than the regular sklearn which took some time to figure out. 
