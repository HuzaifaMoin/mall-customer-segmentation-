# mall-customer-segmentation-
# Mall Customer Segmentation using KMeans

## Overview
This project applies **Exploratory Data Analysis (EDA)** and **KMeans clustering** to segment mall customers based on their:
- Age
- Annual Income
- Spending Score

The objective is to identify distinct customer groups that can help businesses design targeted marketing strategies.

---

## Dataset
The dataset contains 200 customers with the following attributes:
- CustomerID
- Genre
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## Steps
1. Data exploration and visualization (distributions, boxplots, scatterplots, grouping by age/income/spending)
2. Feature scaling using `StandardScaler`
3. KMeans clustering:
   - Using Annual Income & Spending Score (2D clustering)
   - Adding Age for 3D clustering
4. Elbow Method to determine the optimal number of clusters
5. Visualization of customer segments in 2D and 3D
6. Interpretation of clusters

---

## Results
- The **optimal number of clusters = 5**
- Identified distinct customer groups:
  - High income + high spending → Premium customers  
  - Low income + high spending → Bargain hunters  
  - High income + low spending → Conservative customers  
  - Low income + low spending → Careful customers  
  - Mid-range → Average customers  

---

## Tools & Libraries
- Python  
- Pandas, Numpy  
- Matplotlib, Seaborn, Plotly  
- Scikit-learn (StandardScaler, KMeans)
