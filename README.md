# Customer Segmentation Using K-Means Clustering
## About Project

In this project, I worked on understanding different types of mall customers using data. Since not all customers behave the same way, the idea was to group them based on how much they earn and how much they spend. This helps businesses move away from generic marketing and focus on more personalized strategies.

## Problem Statement

Mall customers have different income levels and spending habits, but marketing campaigns are often designed in a one-size-fits-all manner.
The goal of this project is to segment customers based on income and spending behavior so that marketing teams can design more targeted, relevant, and effective campaigns.

## Dataset

I used the Mall Customers dataset from Kaggle.
For clustering, I focused on:

Annual Income (k$)

Spending Score (1–100)

These features are useful for understanding purchasing power and customer behavior.

## Approach

To solve this problem, I followed these steps:

Selected relevant features for clustering

Applied feature scaling to ensure fair distance calculation

Used the Elbow Method to get an initial idea of the number of clusters

Used the Silhouette Score to confirm the optimal number of clusters

Applied K-Means clustering with 5 clusters

Visualized and interpreted each customer segment

## Cluster Interpretation

The model divided customers into five meaningful groups:

Regular customers with moderate income and spending

High-income, high-spending premium customers

Price-sensitive customers with high spending

High-income customers who spend less than expected

Low-income, low-spending customers

Each group represents a different customer behavior pattern.

## Key Insights

This segmentation makes it easier to:

Identify high-value customers for loyalty programs

Target discount-driven customers with promotions

Recognize customers with upselling potential

Optimize marketing efforts instead of treating all customers the same

## Tools Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

## Conclusion

This project shows how unsupervised machine learning can be used to turn raw customer data into useful business insights. By identifying clear customer segments, businesses can make better marketing decisions and improve customer engagement.

### Thanks for checking out this project!
Feel free to explore the code or share feedback.

### Project link (Google Colab): https://colab.research.google.com/drive/1MfSwzr2CCrjcBcB1cDb5tnmRXXb97PLX#scrollTo=Xf35ascf9u7B
