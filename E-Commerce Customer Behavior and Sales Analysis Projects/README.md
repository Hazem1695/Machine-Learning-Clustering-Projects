# E-Commerce Customer Behavior and Sales Analysis TR

## Project Overview

This project focuses on advanced customer segmentation and behavioral analysis using the **E-Commerce Customer Behavior and Sales Analysis TR** dataset. The main objective is to transform raw e-commerce transactional and engagement data into actionable business intelligence using unsupervised machine learning techniques.

The project explores customer purchasing behavior, spending patterns, engagement activity, browsing behavior, and customer interaction metrics to identify meaningful customer segments that can support data-driven business decisions.

Unlike traditional clustering projects that rely only on a single model or evaluation metric, this project performs extensive experimentation using multiple preprocessing strategies, feature engineering approaches, scaling techniques, and clustering algorithms to build a robust and interpretable customer segmentation framework.

---
## Model Release Schedule
To maintain consistency and focus on understanding each model deeply, this project is structured as a daily release series, where each model is implemented, analyzed, and published separately.

| Day    | Model Name                   | Publish Date    | Status      |
| ------ | ---------------------------  | --------------- | ----------- |
| 1      | KMeans Clustering            | 2026-05-25      | Completed   |
| 2      | Hierarchical Clustering      | 2026-05-29      | Completed   |


- In Progress – Currently being worked on
- Planned – Not uploaded yet
- Completed – Uploaded and documented
- TBD – To Be Determined

---

## Project Goals

The primary goals of this project are:

* Analyze customer purchasing behavior
* Discover hidden customer patterns
* Build meaningful customer segments
* Compare clustering strategies and preprocessing techniques
* Evaluate clustering quality using multiple evaluation metrics
* Separate customer value behavior from customer engagement behavior
* Generate actionable business insights for marketing and retention strategies

---

## Machine Learning Techniques Used

This project applies multiple unsupervised machine learning approaches, including:

### K-Means Clustering

Used for:

* Customer segmentation
* Revenue-based clustering
* Engagement analysis
* Customer cohort creation

### Agglomerative Clustering

Used for:

* Hierarchical customer segmentation
* Cluster relationship analysis
* Customer similarity discovery
* Hierarchical clustering evaluation

---

## Project Workflow

The project follows a complete machine learning and customer analytics pipeline:

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis
3. Feature Engineering
4. Customer-Level Aggregation
5. Scaling and Transformation
6. Clustering Model Development
7. Cluster Evaluation
8. Customer Segment Analysis
9. Business Insight Generation

---

## Feature Engineering

Several customer-level features were engineered to improve segmentation quality, including:

* Total Amount
* Number of Orders
* Average Order Value
* Basket Size
* Product Diversity
* Session Duration
* Pages Viewed
* Pages Per Minute
* Customer Rating
* Recency Days

The dataset was transformed from transaction-level behavior into customer-level behavioral profiles by grouping data using `Customer_ID`.

---

## Clustering Experiments

Multiple experiments were conducted using:

* K-Means Clustering
* Agglomerative Clustering
* StandardScaler
* RobustScaler
* Different feature combinations
* Multiple cluster sizes
* Value-based segmentation
* Engagement-based segmentation

The project compares all experiments using:

* Silhouette Score
* Davies-Bouldin Score
* Calinski-Harabasz Score

---

## Final Selected Approach

After extensive experimentation, the final selected framework was based on:

* Customer-level aggregation
* Separate value and engagement segmentation
* Agglomerative Clustering
* RobustScaler preprocessing

The final model separates customers into:

### Customer Value Segments

Based on:

* Spending behavior
* Purchase frequency
* Average order value

### Customer Engagement Segments

Based on:

* Website interaction
* Browsing activity
* Customer satisfaction

This produced meaningful customer quadrants that support real-world business analysis and marketing strategies.

---

## Business Value of the Project

This project demonstrates how machine learning can be used to solve real business problems in e-commerce environments.

The final segmentation framework can help businesses:

* Identify high-value customers
* Improve customer retention
* Personalize marketing campaigns
* Detect low-engagement customers
* Optimize recommendation systems
* Increase customer lifetime value
* Improve sales and engagement strategies

---

## Technologies and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy

---

## Evaluation Metrics

The clustering models were evaluated using multiple unsupervised learning metrics:

* Silhouette Score
* Davies-Bouldin Score
* Calinski-Harabasz Score

These metrics were used to compare clustering quality, compactness, and cluster separation across all experiments.

---

## Key Highlights

* Extensive clustering experimentation
* Comparison between K-Means and Agglomerative Clustering
* K-Means clustering analysis
* Hierarchical clustering analysis
* Advanced feature engineering
* Customer-level behavioral modeling
* Separate value and engagement segmentation
* Business-oriented customer intelligence framework
* Real-world e-commerce customer analysis

---

## Final Outcome

The final solution successfully transformed raw transactional data into a structured customer intelligence system capable of generating meaningful customer segments and actionable business insights.

This project demonstrates practical applications of machine learning, customer analytics, feature engineering, and unsupervised learning in real-world e-commerce environments.

---
## Author
Hazem Mohamed | AI Engineer


