# MSCS 634: Advanced Data Mining Final Project

## Project Overview
This project applies advanced data mining techniques to the **UCI Online Retail dataset** to uncover meaningful insights, build predictive models, and provide practical business recommendations. The workflow integrates data preprocessing, exploratory data analysis (EDA), regression, classification, clustering, and association rule mining.

## Dataset Summary
- **Dataset**: UCI Online Retail
- **Records**: 541,909 rows, 8 attributes
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- **Reason for Selection**: Real-world transactional dataset ideal for pattern discovery and predictive modeling.

## Project Steps
1. **Data Preprocessing & EDA**: 
   - Cleaned data by removing missing and duplicate records, handled outliers.
   - Performed exploratory analysis with visualizations to understand data distribution and relationships.

2. **Regression Modeling**:
   - Built Linear and Ridge Regression models to predict customer spending.
   - Ridge Regression slightly improved generalization and reduced overfitting.

3. **Classification Modeling**:
   - Implemented Decision Tree and k-NN classifiers to identify high-value customers.
   - Applied hyperparameter tuning (GridSearchCV) for optimal k-NN performance.

4. **Clustering**:
   - Used K-Means clustering to segment customers into meaningful groups for targeted marketing strategies.

5. **Association Rule Mining**:
   - Discovered frequent itemsets and association rules using the Apriori algorithm for cross-selling opportunities.

## 📈 Key Findings
- **Regression Analysis**: TotalQuantity and NumPurchases are strong predictors of customer spending.
- **Classification**: Tuned k-NN achieved higher accuracy than Decision Tree.
- **Clustering**: Identified three distinct customer segments with unique purchasing behaviors.
- **Pattern Mining**: Revealed common product bundles suitable for marketing campaigns.

## Practical Recommendations
- **Customer Retention**: Focus on high-value clusters for loyalty programs.
- **Cross-Selling**: Leverage association rules to suggest complementary products.
- **Churn Prevention**: Monitor mid-tier customer clusters to prevent attrition.

## Ethical Considerations
- **Privacy**: Anonymized customer IDs to protect sensitive information.
- **Fairness**: Addressed potential dataset bias due to regional transaction dominance (UK).
- **Bias Mitigation**: Applied stratified sampling techniques during modeling.

## Repository Contents
- `Final_Project_Insights_Cleaned.ipynb`: Consolidated notebook with full analysis and visualizations.
- `Final_Project_Report.pdf`: Comprehensive report detailing methods, results, insights, and recommendations.
- `README.md`: Project summary and key insights.

## Video Presentation
Please refer to the separate submission for the **5-7 minute project presentation**, which includes a summary of the project journey and key takeaways.
