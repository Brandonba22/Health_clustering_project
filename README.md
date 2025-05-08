# Health_clustering_project
Unsupervised clustering project using hierarchical and K-Means methods to segment older adults by health and socio-economic status using cross-sectional survey data.


This project applies unsupervised machine learning techniques to cluster older American adults (ages 65–70) based on health and socio-economic indicators. Using both hierarchical clustering and K-Means, individuals were grouped according to income, total assets, years of education, and self-reported health status.

## Objective

The goal is to identify meaningful subgroups in the population without using labeled outcomes, allowing us to explore how health outcomes correlate with socio-economic differences in a data-driven way.

## Dataset

- Cross-sectional dataset with 7,941 observations
- Features used for clustering:
  - Total income
  - Total assets
  - Years of education
  - Self-reported health

## Methods

- **Data Cleaning**: Removed missing values and filtered outliers using the IQR method
- **Feature Scaling**: Standardized numeric features using `StandardScaler`
- **Clustering Algorithms**:
  - Hierarchical Clustering (`scipy.cluster.hierarchy`)
  - K-Means Clustering (`sklearn.cluster.KMeans`)
- **Visualization**:
  - Scatterplots and bar charts using `matplotlib` and `seaborn` to compare cluster characteristics

## Results

Both clustering methods identified distinct socio-economic tiers (lower, middle, upper), with consistent patterns across both techniques. Interestingly, the middle-income group demonstrated the strongest average health outcomes, suggesting a complex relationship between wealth and well-being.

## Tools Used

- Python
- pandas, numpy
- matplotlib, seaborn
- sklearn, scipy
