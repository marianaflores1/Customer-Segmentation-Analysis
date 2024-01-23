# Customer-Segmentation-Analysis

This study examines data from Kaggle on customer demographics for the purpose of conducting a segmentation analysis to guide personalization strategy. Segmentation analysis is derived in Python by applying an unstructured learning technique called K-Means Clustering with Principal Component Analysis (PCA) to identify and segment customers into three subgroups. Key findings and recommendations are derived through a combination of SQL, Excel, and PowerPoint and both provide context into the analysis as well as executive summary of business insights.

## Business Objective
To maximize the value of customers to the business through a personalization strategy tailored to each segment.

## Summary of Analysis
I.   Import data

II.  Explore data

III. Identify Outliers

IV.  Feature Engineering

V.   Correlation Estimate

VI.  Hierchical Clustering

VI.  K-Means

VII. K-Means with Principal Component Analysis (PCA)

VIII. Results


## Key Findings & Recommendations
K-Means is a traditional clustering technique commonly used for segmentation data. Three clusters are identified based on the Dendrogram chart. Due to the number of clusters we run ten iterations using K-Means and identify three subgroups: 

- Segment 0 (32.31%) - 100% Male and 0% Female Gender, average age of 32.05 years, and income of $64.39K (highest earning subgroup)

- Segment 1 (22.72%) - 53.34% Male and 46.66% Female Gender (almost equal), average age of 58.87 years (oldest subgroup), and Income of $48.93K.

- Segment 2 (45.95%) - 0% Male and 100% Female Gender, average age of 33.76 years, and income of $62.02K.


To gain more clarity, we combine K-Means with Principal Component Analysis (PCA). Each of our Components explains for about a third of the variability in the data and as a rule of thumb we keep between 70% to 80% of the explained variance so we choose 2 Components. Then decide on a number of clusters based on K-Means with PCA model using the elbow method:

- Segment 0 (36.7%) - 16.43% Male and 83.56% Female Gender, average age of 33.08 years, income of $39.68K, and spending score of 53.32.

- Segment 1 (25.3%) - 84.00% Male and 16.00% Female Gender, average age of 54.62 years (oldest subgroup), income of $53.64K, and spending score of 42.18.

- Segment 2 (37.9%) - 42.66% Male and 57.33% Female Gender, average age of 34.16 years, income of $83.45K (highest earning subgroup), and spending score of 52.49.


Based on K-Means Clustering with PCA analysis - recommendations include: to tailor personalization strategy to each segment, prioritize customers with highest spending scores, and identify methods to upsell or cross sell across lower spending scores to maxime the value to the business.
