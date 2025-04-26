## Task Objective

The goal of this assignment is to perform **customer segmentation** using unsupervised machine learning techniques, specifically **K-Means Clustering**. This process involves grouping mall customers based on their characteristics to identify distinct customer segments. These segments can then be used for targeted marketing, product recommendations, or customer behavior analysis.

## K-Means Clustering

### What is K-Means?
**K-Means Clustering** is an unsupervised machine learning algorithm used to partition a dataset into **K distinct clusters**. The algorithm works by:
1. Selecting **K centroids** randomly.
2. Assigning each data point to the nearest centroid.
3. Recalculating the centroids based on the mean of the points in each cluster.
4. Repeating the process until the centroids do not change significantly.

The goal of K-Means is to minimize the **within-cluster variance**, making the clusters as homogeneous as possible.

### Why K-Means for Customer Segmentation?
In customer segmentation, we use K-Means to identify different customer groups based on features like age, income, and spending score. These clusters represent distinct groups of customers with similar behaviors, allowing businesses to:
- Identify high-spending customers.
- Segment customers based on demographic characteristics.
- Tailor marketing strategies to different customer segments.

### Steps Involved in K-Means:
1. **Initialization**: Randomly select K centroids.
2. **Assignment**: Assign each customer to the nearest centroid based on their features (e.g., age, income).
3. **Update**: Recompute the centroids of the clusters.
4. **Repeat**: Repeat the assignment and update steps until the centroids stabilize (no significant change).

### Choosing K:
The number of clusters (**K**) needs to be chosen carefully. One common method to determine the best K is the **Elbow Method**, where the sum of squared distances from points to their assigned centroids is plotted for different values of K. The "elbow" point on the plot suggests the optimal number of clusters.
