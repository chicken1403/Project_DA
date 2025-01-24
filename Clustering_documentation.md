# Customer Segmentation Analysis Documentation

This document provides a comprehensive description of the customer segmentation analysis performed using clustering techniques. The goal was to segment customers based on their purchase behavior, represented by features such as Total Spend (TotalValue), Product Diversity, and Recency.

---

## Libraries and Dependencies

The following Python libraries were used for the analysis and visualization:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib** and **Seaborn**: For creating plots and visualizations.
- **Sklearn (Scikit-learn)**: For clustering algorithms and evaluation metrics.

---

## Data Preprocessing

The dataset was preprocessed to standardize the features:

1. **StandardScaler** was applied to scale the features (TotalValue, ProductDiversity, Recency) so that all variables were on the same scale.
2. Missing values were handled, and outliers were treated appropriately.

---

## Clustering Approach

### DBSCAN Clustering

DBSCAN (Density-Based Spatial Clustering of Applications with Noise) was used to segment the customers:

- **Features Used**: TotalValue and ProductDiversity.
- **Parameters**: Epsilon (`eps`) and Minimum Samples (`min_samples`) were optimized to identify meaningful clusters.

### Optimal Cluster Selection

- The **Davies-Bouldin Index (DBI)** was used to determine the optimal number of clusters.
- The number of clusters that minimized the DBI was chosen.

---

## Results and Visualizations

### 1. **2D Cluster Visualization**

- **Axes**: Total Spend (X-axis) vs. Product Diversity (Y-axis).
- Each point represents a customer, and the color indicates the cluster assignment.
- Two clusters were identified (Cluster 0 and Cluster 1). Cluster 0 represents high spenders with diverse purchases, while Cluster 1 represents low spenders with focused purchases.

### 2. **DB Index Plot**

- The Davies-Bouldin Index was plotted for different cluster sizes.
- The optimal cluster size was identified where the DBI was minimized.

### 3. **3D Cluster Visualization**

- **Axes**: Total Spend (X-axis), Product Diversity (Y-axis), and Recency (Z-axis).
- Clusters were visualized in a 3D space, providing a deeper understanding of customer segmentation.
- A color gradient was used to differentiate clusters.

---

## Key Observations

1. **Cluster 0** (Blue Points)

   - Higher Total Spend and Product Diversity.
   - Represents high-value customers with diverse shopping habits.

2. **Cluster 1** (Green Points)

   - Lower Total Spend and Product Diversity.
   - Represents budget-conscious customers with specific purchasing preferences.

3. The 3D visualization highlighted the interplay between Recency, Total Spend, and Product Diversity, revealing deeper insights into customer behavior.

4. The DBI plot confirmed the stability of the identified clusters, ensuring meaningful segmentation.

---

## Conclusion

The customer segmentation analysis successfully identified two distinct customer groups based on their spending behavior and product diversity. This segmentation can be used to:

- Develop targeted marketing strategies.
- Enhance customer loyalty programs.
- Identify potential areas for upselling and cross-selling.

---

## Attachments

The following visualizations support the analysis:

1. **2D Cluster Visualization**: Segments customers based on Total Spend and Product Diversity.
2. **DB Index Plot**: Indicates the optimal number of clusters.
3. **3D Cluster Visualization**: Highlights Recency's role in customer segmentation.
