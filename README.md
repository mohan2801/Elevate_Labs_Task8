K-Means Clustering – Mall Customer Segmentation
Overview
This project demonstrates unsupervised learning using K-Means clustering to segment mall customers based on demographic and spending behavior. The objective is to identify meaningful clusters that can guide marketing strategies and business decisions.

Objective
Use the Elbow Method to determine the optimal number of clusters.

Apply K-Means clustering to discover natural groupings in the data.

Evaluate clustering performance using the Silhouette Score.

Visualize clusters in two dimensions using PCA (Principal Component Analysis).

Dataset
The dataset used is the Mall Customer Segmentation Data from Kaggle. It includes the following features:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1-100)

Technologies Used
Python 3

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Workflow
Load and explore the dataset

Convert categorical variables (e.g., Gender) to numerical format

Scale features using StandardScaler

Apply K-Means with different values of k

Use the Elbow Method to identify the optimal number of clusters

Evaluate clustering with Silhouette Score

Visualize clusters using PCA-reduced components

Results
Optimal number of clusters identified: k = 5

Silhouette Score indicates well-separated clusters

PCA-based visualization shows distinct customer segments

Sample Output
Elbow Curve
Displays the reduction in inertia as the number of clusters increases, helping to locate the “elbow point”.

Cluster Visualization
Shows the clustered data in a 2D PCA-reduced plot, with color-coded segments representing different customer groups.

Key Learnings
K-Means is effective for finding patterns in unlabeled data

The Elbow Method and Silhouette Score provide insight into cluster quality

Dimensionality reduction with PCA makes clustering easier to interpret

