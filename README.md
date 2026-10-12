# Customer Segmentation Using K-Means Clustering

## Project Overview

This project applies unsupervised machine learning to segment customers based on their purchasing behavior using the Online Retail dataset.

The objective is to identify customer groups and translate their purchasing patterns into actionable business recommendations.

## Objectives

- Explore and clean retail transaction data.
- Perform Recency, Frequency, and Monetary (RFM) analysis.
- Engineer customer-level features.
- Apply log transformation and feature scaling.
- Use the Elbow Method and Silhouette Score to evaluate clustering options.
- Build a K-Means clustering model.
- Visualize customer segments and recommend business strategies.

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

1. Data understanding and exploratory data analysis.
2. Data cleaning and preparation.
3. RFM feature engineering.
4. Log transformation and standardization.
5. Cluster evaluation using inertia and silhouette scores.
6. K-Means model training.
7. Customer segment interpretation and visualization.

## Preliminary Results

The initial evaluation identified **K = 2** as the best-scoring option among the tested values, with a silhouette score of **0.433**.

This is a preliminary clustering result. The final segment profiles and business recommendations should be based on the actual cluster statistics.

## Dataset

The project uses the UCI Online Retail dataset.

Source: https://archive.ics.uci.edu/dataset/352/online+retail

The raw dataset is not included in this repository.

## Project Structure

```text
02_Customer_Segmentation/
├── customer_segmentation.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── data/
└── images/
```

## Conclusion

This project demonstrates a customer segmentation workflow, from data preparation and feature engineering to clustering evaluation and business interpretation.

The results can help inform customer engagement, retention, and marketing strategies.
