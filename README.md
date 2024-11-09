# Mall Customer Segmentation
The Goal is to segment customers based in their behaviors and attributes, providing valuable insights for marketing strategies. Although customer segmentation is a typical application clustering, the data set chosen here offers a  fresh perspective beyond the standard academic dataset.

# Features
. CustomerID : Unique identifier for the customer
. Gender : Customer's gender
. Age : Customer's age
. Annual Income (k$) : Customer's annual income in thousand dollars
. Spending Score (1-100) : Score assigned by the mall based on customer behavior and spending nature

# Task 1: Data Loading and Preprocessing
. Load the dataset. The dataset can be sourced from Kaggle: Mall Customer Segmentation Data Link:
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python.
. Conduct necessary preprocessing steps, including handling missing values if any and encoding categorical variables.

# Task 2: Exploratory Data Analysis (EDA)

. Perform an EDA to understand the dataset's characteristics, focusing on the distribution of key features like Age , Annual Income (k$) ,
and Spending Score .
. Visualize the relationships between Annual Income (k$) and Spending Score, as these are crucial for understanding customer behavior.

# Task 3: Preparing Data for Clustering
. Decide which features to use for clustering. While CustomerID should be excluded, consider whether Gender should be included and how it
might affect the clustering process.
. Normalize the data if necessary to ensure that the scale of the features does not unduly influence the clustering.

# Task 4: Applying K-Means Clustering
. Apply K-Means clustering to the dataset. Start with a range of cluster numbers (e.g., 1 to 10) and use the elbow method to determine the optimal
number of clusters.
· Analyze the characteristics of each cluster. What does each cluster represent in terms of customer segmentation?

# Task 5: Evaluation and Interpretation

. Evaluate the clustering result. Discuss how well the segmentation aligns with your expectations and any insights gained from this exercise.
. Visualize the clusters in a 2D plot, using Annual Income (k$) and Spending Score for the axes, to illustrate the customer segments.

.
