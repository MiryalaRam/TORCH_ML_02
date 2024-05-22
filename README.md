Customer Segmentation using KMeans Clustering:
In this project, we used K-means clustering algorithm to segment Customers of a Retail store based on their purchase history and aims to help the mall owner understand their customer base, identify potential target customers and develop marketing strategies accordingly.

The dataset contains information such as Customer ID, Age, Gender, Annual Income and Spending Score assigned to customers based on their behavior and purchasing data.

Key findings and actions taken:
Data Preprocessing: The dataset was first loaded and checked for missing values and duplicates. Fortunately, there were no missing values or duplicates, making it suitable for analysis.

Exploratory Data Analysis: Explored the data by visualizing the distribution of gender and numerical columns like Age, Annual Income and Spending Score. We also performed a pairplot and checked for outliers, which helped us understand the dataset better.

Data Encoding: The 'Gender' column was encoded to numeric values (0 for Female and 1 for Male) to make it compatible with the K-means algorithm.

Model Building: Applied the K-means clustering algorithm with various values of 'k' (number of clusters), used the Silhouette Score and the Elbow method to determine the optimal number of clusters. Ultimately, we settled on k=3 and k=5 for two different segmentations.

Visualizing Clusters: Visualized the clusters by plotting 2D and 3D representations, allowing us to observe how customers were grouped based on Age, Annual Income and Spending Score.

Ultimately, the project successfully segmented customers into distinct groups, helping the retail store to tailor marketing strategies and services to specific customer segments.

