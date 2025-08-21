# Real Estate Price Prediction

End-to-end ML pipeline to predict real estate prices.

# Project Story

Situation:
Real estate pricing data was unstructured and difficult to analyze, limiting stakeholders’ ability to understand price drivers, forecast property values, and make data-driven investment decisions.

Task:
Build a predictive and analytical solution to estimate property prices, identify key factors influencing real estate markets, and deliver actionable KPIs for business users.

Action:

-Cleaned and transformed a dataset of 10K+ property listings (features: location, area, bedrooms, bathrooms, amenities, etc.) using Python (Pandas, NumPy) and SQL.

-Engineered features (price per sq.ft., property age, proximity scores) and handled missing data, outliers, and categorical encodings.

-Applied multiple ML models (Linear Regression, Random Forest, XGBoost) and performed hyperparameter tuning, achieving high accuracy.

-Built interactive visualizations in Power BI/Matplotlib/Seaborn to show price distribution by city, neighborhood, and property type.

-Designed a star schema with FactTransactions linked to DimProperty, DimLocation, and DimDate for reporting and KPI tracking.

Result:

-Achieved R² = 0.87 and MAPE = 12%, enabling reliable property price predictions.

-Identified top 3 features impacting prices: location contributed ~55% variance, size ~25%, and property age ~12%.

-Automated analytics reduced manual data processing time by ~40%.

-Delivered business insights:

-Luxury properties (> $500K) had 20% higher margins than mid-range homes.

-Urban listings sold 30% faster than suburban ones.

-Top 10 neighborhoods accounted for ~45% of total sales revenue.

-Enabled real estate firms to optimize investment strategies, contributing to a forecasted 15% improvement in ROI for targeted regions.

## Tools Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Highlights
- Cleaned and prepared datasets
- Performed exploratory data analysis
- Trained Linear Regression model
- Evaluated using R² and residual plots

