# Machine Learning Prediction of NGFK   dependency in HNC (Head and Neck Cancer)

## Project Overview:

In this project, we aim to explore the relationship between EGFR CRISPR gene dependency and Head and Neck Cancer (HNC). We will utilize the Random Forest (RF) model, a powerful machine learning algorithm, to predict EGFR gene dependency using Cancer Cell Line Encyclopedia (CCLE) gene expression data. Before training the RF model, we will apply K-means clustering to group the cell lines into 5 clusters based on their gene expression patterns, enabling more focused predictions. By analyzing the data within each cluster, we seek to uncover essential gene expression patterns associated with EGFR dependency in HNC, contributing valuable insights that may aid in developing targeted therapeutic approaches for the disease.

![](https://github.com/chingyaousf/Machine-Learning-Prediction-of-NGFK-dependency-in-HNC-Head-and-Neck-Cancer-/blob/main/plots/filtered_arranged_hnc_table.png?raw=true)

### K-Means 5 clusters:![](https://github.com/chingyaousf/Machine-Learning-Prediction-of-NGFK-dependency-in-HNC-Head-and-Neck-Cancer-/blob/main/plots/filtered_arranged_hnc_table_KMeans_clustering.png?raw=true)

### RF models using K-Means 5 clusters:

![](https://github.com/chingyaousf/Machine-Learning-Prediction-of-NGFK-dependency-in-HNC-Head-and-Neck-Cancer-/blob/main/plots/RF_NGFK_by_KMeans_5_clusters.png?raw=true)

### RF models prediction error values using K-Means 5 clusters:![](https://github.com/chingyaousf/Machine-Learning-Prediction-of-NGFK-dependency-in-HNC-Head-and-Neck-Cancer-/blob/main/plots/RF_HNC_EGFR_error_values.png?raw=true)

## Blog:

<https://ssidmarine.wordpress.com/2023/08/01/machine-learning-prediction-of-ngfk-dependency-in-hnc-head-and-neck-cancer/>

## Access data:

DepMap Public 22Q2 Primary Files

<https://depmap.org/portal/download/all/>

22Q2 CRISPR_gene_effect

CRISPR_gene_dependency.csv

CCLE_expression.csv

**testing data available in the data folder**
