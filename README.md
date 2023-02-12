## Myopic Patient Data

Classify Myopia Patient Data using Unsupervised Machine Learning Models

## Objectives

### Step 1 - Prepare the Data

* Read myopia.csv into a Pandas DataFrame

![](images/df.png)

* Remove the "MYOPIC" column from the dataset

![](images/df2.png)

* Standardize the dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values

### Step 2 - Apply Dimensionality Reduction

* Perform dimensionality reduction with PCA

![](images/pca.png)

* Further reduce the dataset dimensions with t-SNE
* Create a scatter plot of the t-SNE output

![](images/tsne.png)

### Step 3 - Perform a Cluster Analysis with K-means

* Create a K-means model

![](images/kmean.png)

* Create an elbow plot to identify the best number of clusters

![](images/elbow.png)

### Step 4 - Make a Recommendation

* Recommendation: The elbow of the plot occurs at k = 3, indicating that the best number of clusters for the given data is 3. Therefore, it is recommended that the patients be grouped into three clusters.

---------------------------------------------------

<b>Contact:</b> bronwynmilne64@gmail.com
