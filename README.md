
#  Customer Segmentation Using RFM Analysis and Clustering

##  Overview

This project focuses on segmenting customers based on their **Recency**, **Frequency**, and **Monetary** (RFM) behavior using unsupervised learning techniques. The goal is to help businesses understand different customer types and tailor strategies for acquisition, retention, and re-engagement.

---

## Objectives

- Clean and preprocess real-world retail transaction data
- Derive meaningful RFM features from the dataset
- Visualize relationships and correlations within the RFM metrics
- Apply **hierarchical clustering** to group similar customers
- Gain business insights to help guide customer engagement strategies

---

##  Technologies Used

- **Python**
- **Pandas** – data manipulation
- **Seaborn / Matplotlib** – data visualization
- **Scikit-learn** – scaling and clustering
- **Scipy** – hierarchical clustering (dendrogram)

---

##  Data Cleaning Steps

- Removed null or missing values
- Handled outliers using **IQR** method and **log transformation**
- Filtered invalid entries (e.g., negative quantities)
- Created new variable `Revenue = Quantity * UnitPrice`

---

## Feature Engineering

- **Recency**: Days since the customer last purchased
- **Frequency**: Number of unique transactions
- **Monetary**: Total spend of each customer
- Calculated using `groupby` operations on `CustomerID`

---

## EDA Highlights

- Correlation heatmaps to identify relationships between RFM values
- Boxplots to understand data distribution and detect outliers
- Pair plots for visualizing feature interactions

---

##  Clustering Approach

- **Hierarchical Clustering** (Ward’s method)
- Visualized using **dendrograms** to choose optimal clusters
- Scaled RFM values using `StandardScaler` before clustering

---

##  Key Insights

- Some customers purchase frequently but spend less—potential for upselling
- High-revenue customers show moderate frequency but low recency—target for retention
- Recency is inversely correlated with monetary value—recent buyers often spend more

---

##  Business Impact

- Helps identify **loyal customers**, **potential churners**, and **big spenders**
- Enables tailored marketing strategies per customer group
- Drives improved customer experience and retention through data-driven insights

---

##  Contact Me

<p align="left">
  <a href="mailto:diyasingh9081@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-Diya_Singh-red?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  
  <a href="https://www.linkedin.com/in/diyasingh555/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Diya_Singh-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  
  <a href="https://github.com/Diyasingh555" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Diyasingh555-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</p>

