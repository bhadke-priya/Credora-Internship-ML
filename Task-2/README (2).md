 **Customer Segmentation using K-means Clustering**
 
This project demonstrates how to apply **unsupervised machine learning** techniques to group customers based on their **shopping behavior**. Using the **K-Means clustering algorithm**, we identify distinct segments within a customer base to help businesses better understand and target their customers.
   
  **Problem Statement**
    Retail and e-commerce businesses often deal with diverse customer bases. Understanding different customer types helps tailor marketing strategies, improve customer satisfaction, and increase revenue.

**Step Followed**
1. Problem Understanding
-  The goal of Segment customers based on their shopping behavior.
-  Use clustering (unsupervised learning) to group similar customers.
  
2 . Data Loading & Exploration
-  Loaded the dataset from Kaggle.
-  Explored data types, null values, and statistical summaries.
  
3.  Data Preprocessing
-  Check for and remove/impute null values.
-  Choose numerical features relevant to behavior.
-  Normalize features using StandardScaler to ensure fair distance calculations in clustering.

4 .Finding Optimal Number of Clusters
-  Used the Elbow Method to determine the optimal value of k.
-  Plotted WCSS (Within-Cluster Sum of Squares) for values from 1 to 10.

5. Applying K-Means Clustering
-  Trained the K-Means model with optimal k (e.g., 5).
-  Predicted cluster labels for all customers.

6. Cluster Visualization
-  Visualized the clusters using scatter plots.
-  Plotted centroids for each cluster.

7 .Cluster Analysis
-  Calculate the average Age, Income, and Spending Score for each cluster.

**Key Results**

•  Clusters Visulization

   Cluster 0 – High Income, High Spending  
   Cluster 1 – Low Income, Low Spending  
   Cluster 2 – High Income, Low Spending  
   Cluster 3 – Average Income, High Spending  
   Cluster 4 – Young Customers with Medium Spending

 
**How to Run**

 1.	Download the dataset from Kaggle and place Mall_Customers.csv in this folder.
 2.	Run the notebook in Jupyter.
 3.	Review the output report and plots.
    
**Tools & Libraries**

 •	Python
 
 •	Scikit-learn
 
 •	Matplotlib
 
 •	Seaborn

