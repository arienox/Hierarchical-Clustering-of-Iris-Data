# Hierarchical-Clustering-of-Iris-Data

This code performs hierarchical clustering on the Iris dataset, which consists of 150 samples of flowers with four features: sepal length, sepal width, petal length, and petal width.

## Techniques Used
1. Dendrogram plot generation
2. Hierarchical clustering with Agglomerative Clustering
3. Running the Code

## To run the code, you will need to have the following packages installed:
```
sklearn
matplotlib
scipy
```
You can install these packages using pip.

## Once you have the necessary packages installed, you can run the code by using the following command:

> python iris_clustering.py

## Output
The code will output:

1. A dendrogram plot showing the relationships between the samples and helping to determine the optimal number of clusters
2. A scatter plot visualizing the clusters, with the x-axis representing the sepal length and the y-axis representing the sepal width. Each cluster is plotted in a different color.

## Sample Code
Here is an example of how you can access the Iris dataset and extract the sepal length and width values:
```
from sklearn.datasets import load_iris

iris = load_iris()
sepal_length = iris.data[:, 0]
sepal_width = iris.data[:, 1]

print(sepal_length)
print(sepal_width)
```
