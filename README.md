# Linear-Regression-Clustering
Here we will learn how to predict values by applyign linear regression algorithm and forming clusters from the given data set.
Name        : Garimella Suresh Babu
Student Id: 700741367
User Id      :SXG13670@ucmo.edu


3. Try feature scaling and then apply K-Means on the scaled features. Did that improve the Silhouette score? If Yes, can you justify why 

Feature Scaling is a technique to standardize the independent features present in the data in a fixed range. It is performed during the data pre-processing.
It basically helps to normalize the data within a particular range. Sometimes, it also helps in speeding up the calculations in an algorithm.
Here we are using standard scalar feature scaling technique to normalize the data.

After scaling we used the K-means clustering  algorithm to get the model.
Then we find the Silhoutte_score which gives us 0.24996085627555273

Silhouette score is the difference between the point and the nearest cluster that the point is not part of the cluster. 
1: Means clusters are well apart from each other and clearly distinguished. 
0: Means clusters are indifferent, or we can say that the distance between clusters is not significant.
 -1: Means clusters are assigned in the wrong way.

No , here the feature scaling the silhouette score value didn’t moved near 1 compared to before. That means the clusters formed are near to each other unlike before feature scaling.
