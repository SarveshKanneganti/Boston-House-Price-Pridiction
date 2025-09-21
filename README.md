🏠 Boston House Price Prediction

🚀 Project Highlights

•	Performed EDA & feature engineering on Boston Housing dataset to identify key price drivers (rooms, crime rate, location).

•	Built and compared ML models (Linear Regression, Random Forest, Gradient Boosting) with hyperparameter tuning.

•	Achieved highest accuracy with Gradient Boosting, improving prediction reliability vs. baseline models.

•	Delivered actionable insights for real estate pricing strategies and data-driven decision-making.

📌 Project Overview

This project focuses on predicting housing prices in Boston using Machine Learning models. The goal was to identify key drivers of house prices and build accurate predictive models that can assist in real estate decision-making.

🎯 Objectives

•	Perform Exploratory Data Analysis (EDA) to understand housing trends and influential factors.

•	Apply data preprocessing and feature engineering techniques for better model performance.

•	Compare multiple ML models and select the best-performing one based on evaluation metrics.

•	Deliver insights that can support data-driven real estate pricing strategies.

🛠️ Tech Stack

•	Programming Languages: Python

•	Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly

•	ML Models: Linear Regression, Random Forest, Gradient Boosting

•	Techniques: Data Cleaning, Feature Engineering, Hyperparameter Tuning (GridSearchCV), Model Evaluation

🔎 Methodology

•	Data Collection & Cleaning

•	Loaded Boston Housing dataset.

•	Handled missing values, outliers, and scaled features.

•	Exploratory Data Analysis (EDA)

•	Visualized relationships between features and housing prices.

•	Identified key drivers (average rooms per dwelling, crime rate, location).

•	Feature Engineering

•	Applied transformations and feature selection to improve model accuracy.

•	Model Development

•	Built models: Linear Regression, Random Forest, Gradient Boosting.

•	Tuned hyperparameters using GridSearchCV.

•	Evaluation Metrics: MSE, MAE, R².

•	Gradient Boosting delivered the best predictive accuracy.

📊 Results & Insights

•	Average number of rooms (RM) was the strongest positive driver of housing prices — homes with more rooms had significantly higher median values.

•	Crime rate (CRIM) had a strong negative correlation with house prices — higher crime neighborhoods showed lower valuations.

•	Proximity to employment centers (DIS) positively impacted pricing — houses closer to job hubs had higher values.

•	Pupil–teacher ratio (PTRATIO) in schools influenced prices — lower ratios were associated with higher housing values.

•	Older properties (AGE) in certain zones showed depreciation in price, unless located near business or riverfront areas.

•	Nitric oxide concentration (NOX) and industrial zones (INDUS) were negatively correlated with prices — more pollution and industry lowered value.

•	LSTAT (percentage of lower-status population) was a key inverse predictor — higher values of LSTAT correlated with lower house prices.


•	After testing models, Gradient Boosting outperformed Linear Regression and Random Forest, providing the most reliable predictions (higher R², lower MSE).

•	Outlier analysis revealed a few luxury housing clusters with disproportionately high prices, skewing regression models before transformation.


•	Feature engineering and scaling improved stability of models, particularly reducing the variance in Random Forest predictions.

•	Metrics: MSE, MAE, R².

•	Gradient Boosting delivered the best predictive accuracy.

## Thank You

