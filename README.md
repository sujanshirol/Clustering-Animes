# Clustering Anime's

Anime's are largly watched by all age groups. This data set contains information on user preferences from 73,516 users on 12,294 anime. Each user is able to add anime to their completed list and give it a rating and this data set is a compilation of those ratings.

[Source](https://www.kaggle.com/CooperUnion/anime-recommendations-database)

![image (1)](https://user-images.githubusercontent.com/71747522/116199130-6778e600-a754-11eb-9972-0c0843f915ff.png)

## Contents
1. EDA with Plotly
2. KMeans clustering
3. Profiling
5. DBSCAN for outlier detection
6. PCA to clust based 'Genre' recommendation
7. KMeans clustering for the selected 3 PCA's
8. Analysing each cluster


## Techniques used
1. Elbow plot to detect optimal k-value
2. Silhouette score to detect optimal k-value

![image (2)](https://user-images.githubusercontent.com/71747522/116199826-2fbe6e00-a755-11eb-929e-44a7dffcb864.png)


## Conclusions
1. Since 'Action' genre has more number of instances in the dataset, it is a common genre in all the 3 clusters.
2. Cluster0, Comedy seems to be most recommended genre after Action.
3. Cluster1, Psychological seems to be least recommended genre.
4. Cluster2, Magic seems to be least recommended genre.<br>
