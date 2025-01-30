📌 Customer Segmentation Using K-Means Clustering
Project Type: Data Analysis & Machine Learning
Tools Used: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

📖 Project Overview
Customer segmentation is a crucial task in business analytics, allowing companies to categorize customers into different groups based on behavior, spending habits, and income levels. This project applies K-Means clustering to segment customers based on their Annual Income and Spending Score, helping businesses optimize marketing strategies.

📂 Dataset
Dataset Name: Mall Customer Segmentation Dataset
Columns:
CustomerID: Unique customer identifier.
Gender: Male or Female.
Age: Customer's age.
Annual Income (k$): Customer's yearly income in $1000s.
Spending Score (1-100): Score assigned based on spending behavior.
🚀 Methodology
Data Preprocessing

Loaded and explored the dataset.
Checked for missing values and outliers.
Selected relevant features: Annual Income (k$) and Spending Score (1-100).
Standardized data using StandardScaler to ensure uniform scaling.
Finding Optimal Clusters

Used the Elbow Method to determine the ideal number of clusters.
Selected K=5 as the best cluster count.
Applying K-Means Clustering

Trained the K-Means algorithm on the dataset.
Assigned each customer to a segment.
Visualized the clusters using scatter plots.
📊 Results & Insights
The clustering analysis resulted in 5 distinct customer segments:

Segment	Customer Type	Annual Income	Spending Score	Business Strategy
1	Luxury Shoppers	High	High	Exclusive offers, loyalty programs
2	Careful Spenders	High	Low	Personalized discounts, premium services
3	Impulsive Buyers	Low	High	Trend-based marketing, limited-time offers
4	Budget-Conscious Customers	Low	Low	Budget-friendly products, discount strategies
5	Average Consumers	Middle	Moderate	Retargeting, customized marketing
Cluster Visualization
![Cluster Visualization](cluster_visualization.png)

🛠️ Tech Stack
Python: Data manipulation and modeling.
Pandas & NumPy: Data processing and transformation.
Matplotlib & Seaborn: Data visualization.
Scikit-learn: Machine learning (K-Means clustering).
