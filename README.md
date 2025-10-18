# Customer-segmentation-analysis
# Customer Segmentation Analysis

## Business Problem
Mall wants to segment customers for targeted marketing campaigns to increase revenue by 15%.

## Data Description
- Source: Kaggle Mall Customers Dataset
- 200 customers, 5 features
- Features: CustomerID, Gender, Age, Annual Income, Spending Score

## Methodology
1. **EDA**: Univariate and bivariate analysis
2. **Preprocessing**: Standardization, handling categorical variables
3. **Clustering**: K-Means, DBSCAN, Gaussian Mixture Models
4. **Evaluation**: Silhouette Score, Davies-Bouldin Index
5. **Interpretation**: Business insights and recommendations

## Results
- **Optimal Clusters**: 5 segments identified
- **Best Model**: K-Means (Silhouette Score: 0.55)
- **Key Segments**: 
  - High Income Low Spenders (Target for promotions)
  - Young Trend Followers (Social media campaigns)

## How to Run
```bash
pip install -r requirements.txt
python src/main.py