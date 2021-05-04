# Color-Identification-using-K-means-Clustering
Identify colors from the image.

## Steps Involved
Import Libraries: NumPy, Pandas, Matplotlib

Load Image, reshape

Implement Elbow Method to find the optimal value of k

Implement k-means clustering algorithm

Plotting

### Image data
images.app.goo.gl/9MGjLKGNfdi1KHV5A

### Elbow Method
Generally, k value is fixed manually, but there is a procedure to find the optimal value of 'k' by using **Elbow method**. In this method, the value of k is iterated within a range. here, the range is taken as 1-15 as the number of color pallettes in the image are 15. Then, inertia for each value of k is calculated. **Inertia is the sum of squared distances of samples to their closest cluster center.** Next, plot the inertia values for each value of k inorder to find the elbow point. Implement K-means algorithm for k = elbow point = number of clusters.
