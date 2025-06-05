# 📊 Marketing-ML-Project

This end-to-end machine learning solution is designed to **optimize direct mail catalog campaigns** by predicting customer responses and estimating potential revenue. It supports marketing teams in targeting high-value customers more effectively, reducing costs, and maximizing return on investment.

## 🔍 Step-by-Step Summary

1. **Business Objective**  
   Developed a predictive system to target catalog recipients likely to respond and spend. Aimed to improve marketing ROI by 15–25%.

2. **Data Collection & Feature Engineering**  
   Used 12 months of transaction data, demographic information, third-party enrichment, and campaign history. Created 25,000+ features, later reduced to ~200 through Lasso and XGBoost importance.

3. **Modeling**  
   - **Response Model**: XGBoost classifier predicting purchase likelihood (ROC-AUC: 0.763).  
   - **Revenue Model**: LightGBM regressor estimating expected revenue (R² Score: 0.242).

4. **Evaluation**  
   Achieved a 23% increase in campaign ROI while targeting only the top 30% of customers by predicted value.

5. **Deployment**  
   Built a scoring pipeline integrating both models to calculate expected value and guide catalog targeting decisions.

## ⚙️ Technical Stack

- Python, Pandas, NumPy, Scikit-learn  
- XGBoost, LightGBM, LassoCV  
- Bayesian Optimization  
- SQL for data extraction and preprocessing

## 🚀 Key Features

- Predictive analytics for catalog response and revenue  
- Over 200 engineered features including RFM, seasonality, and behavior  
- Real-time scoring pipeline with cost-value optimization  
- Clean UI and HTML documentation

## 📈 Business Impact

This solution enabled the business to:
- **Reduce marketing costs** by avoiding low-probability customers  
- **Maximize revenue** by targeting high responders  
- **Improve ROI** by 15–25% across multiple campaigns

## 🌐 View the Interactive Report
[View Live HTML Page](https://dkanawat.github.io/Marketing-ML-Project/catalog_ml_project.html)

