# customer_segmentation
1. ** Import Libraries**  
   The script begins by importing essential libraries for data manipulation (`pandas`), visualization (`matplotlib`), and machine learning (`StandardScaler`, `KMeans` from `sklearn`).

2. ** Create a Sample Dataset**  
   A small dataset of 10 customers is created with the following features:
   - `CustomerID`
   - `Age`
   - `Annual Income (k$)`
   - `Spending Score (1–100)`

3. ** Preview the Data**  
   The first few rows of the dataset are printed to inspect the structure.

4. ** Select Features for Clustering**  
   The features `Age`, `Annual Income`, and `Spending Score` are selected for clustering.

5. ** Standardize the Features**  
   A `StandardScaler` is used to normalize the feature values so that all features contribute equally to the clustering.

6. ** Apply K-Means Clustering**  
   - A `KMeans` model with 3 clusters is trained on the scaled data.
   - Each customer is assigned to one of the clusters, and the cluster label is added to the DataFrame.

7. ** View Clustered Data**  
   The updated DataFrame with cluster labels is printed to show how customers have been grouped.

8. ** Visualize the Clusters**  
   A scatter plot is generated to visualize customer segments based on `Annual Income` and `Spending Score`, with colors representing different clusters.
apply this to a larger dataset

