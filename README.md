# K-Means Clustering Algorithm

## 1. Applications
k-means can be applied to data that has a smaller number of dimensions, is numeric, and is continuous. such as document clustering, identifying crime-prone areas, customer segmentation, insurance fraud detection, public transport data analysis, clustering of IT alerts…etc.

## 2. Algorithmic steps for k-means clustering

Let  X = {x1,x2,x3,……..,xn} be the set of data points and V = {v1,v2,…….,vc} be the set of centers.

1. Randomly select ‘c’ cluster centers.

2. Calculate the distance between each data point and cluster centers.

3. Assign the data point to the cluster center whose distance from the cluster center is minimum of all the cluster centers..

4. Recalculate the new cluster center.

5. Recalculate the distance between each data point and new obtained cluster centers.

6. If no data point was reassigned then stop, otherwise repeat from step 3).
