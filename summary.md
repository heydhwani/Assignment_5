# Customer Segmentation using K-Means Clustering

## Project Objective

The objective of this project was to segment mall customers into meaningful groups based on their purchasing behavior. By identifying customers with similar characteristics, businesses can design personalized marketing strategies, improve customer engagement, and make better business decisions.

---

## Dataset

- **Dataset:** Mall Customers Dataset
- **Total Records:** 200
- **Features Used:** Age, Annual Income (k$), Spending Score (1–100)

The `CustomerID` column was removed because it is only a unique identifier and does not contribute to customer segmentation. Although the `Gender` column was encoded during preprocessing, clustering was performed using **Age**, **Annual Income**, and **Spending Score** to focus on customer purchasing behavior.

---

## Methodology

The project followed the following workflow:

- Data Loading and Exploration
- Data Cleaning and Preprocessing
- Feature Selection
- Feature Scaling using StandardScaler
- Optimal Cluster Selection using the Elbow Method
- Customer Segmentation using K-Means Clustering
- Cluster Visualization
- Dimensionality Reduction using PCA
- Business Insight Generation

---

## Key Findings

The Elbow Method identified **K = 5** as the optimal number of customer segments.

The analysis revealed five distinct customer groups:

- Low Income – Low Spending Customers
- Young Customers with Active Spending Behavior
- High Income – High Spending Customers
- High Income – Low Spending Customers
- Moderate Income – Moderate Spending Customers

Among these, the **High Income–High Spending** segment represents the most valuable customers for the business, while the **High Income–Low Spending** segment offers the greatest opportunity for increasing future revenue through personalized marketing.

---

## Business Value Delivered

Rather than treating every customer the same, this segmentation enables businesses to make **data-driven marketing decisions**.

- Premium customers can be retained through loyalty programs and exclusive services.
- High-income customers with low spending can be converted into active buyers using personalized recommendations and targeted campaigns.
- Young customers can be engaged through digital marketing, referral programs, and limited-time offers.
- Price-sensitive customers are more likely to respond to affordable product bundles and seasonal discounts.

This approach helps businesses improve marketing efficiency, reduce unnecessary promotional spending, strengthen customer relationships, and maximize long-term revenue.

---

## Business Conclusion

The analysis clearly demonstrates that **different customer segments require different marketing strategies**.

Instead of spending more on marketing, businesses should focus on **spending smarter** by delivering the **right offer to the right customer at the right time**. A customer-centric and data-driven approach not only improves customer satisfaction but also increases conversion rates, strengthens customer loyalty, and supports sustainable business growth.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- K-Means Clustering
- Principal Component Analysis (PCA)