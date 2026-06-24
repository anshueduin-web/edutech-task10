# Task 10: Clustering (K-Means)

## Internship Details
- **Organization:** Edutech Solution
- **Program:** Data Science Internship
- **Task:** Task 10 — Clustering (K-Means)

## Objective
Apply K-Means clustering on Mall Customers dataset to segment
customers based on income and spending score.

## Dataset Used
- **Name:** Mall Customer Segmentation Data
- **Source:** Kaggle (by Vijay Choudhary)
- **Rows:** 200 | **Columns:** 5

## Tools & Libraries
- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Steps Performed
1. Loaded Mall Customers dataset
2. Explored data using describe() and checked missing values
3. Selected Annual Income and Spending Score features
4. Scaled features using StandardScaler
5. Used Elbow Method to find optimal K
6. Trained K-Means with best K (K=5)
7. Assigned cluster labels to customers
8. Visualized clusters with centroids
9. Analyzed cluster profiles (avg income & spending per cluster)

## Key Findings
- Optimal K found using Elbow Method = 5
- 5 distinct customer segments identified:
  - High income, high spending (target customers)
  - High income, low spending
  - Low income, high spending
  - Low income, low spending
  - Average income, average spending
- Centroids represent average income/spending of each segment

## Files in This Repository
| File | Description |
|------|-------------|
| task10_kmeans.ipynb | Jupyter Notebook with full code |
| Mall_Customers.csv | Original dataset |
| clustered_customers.csv | Customers with cluster labels |
| elbow_plot.png | Elbow method graph |
| cluster_visualization.png | Cluster + centroid scatter plot |
| README.md | Project documentation |

## Learning Outcome
Understood unsupervised learning, how K-Means groups data
using centroids, and how the Elbow Method selects the optimal
number of clusters (K).
