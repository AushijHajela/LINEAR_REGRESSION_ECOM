***E-Commerce Customer Spending Prediction***
This project builds and evaluates a Linear Regression model to predict how much a customer will spend annually based on their online behavior. The dataset includes customer information for an e-commerce company, and the goal is to help the company understand which factors most influence customer spending.

***Dataset***
The dataset includes 500 observations and the following features:

***Feature	Description***
Avg. Session Length	Average session duration on the website (minutes)
Time on App	Time spent on mobile app (minutes)
Time on Website	Time spent on website (minutes)
Length of Membership	How long the user has been a customer (years)
Yearly Amount Spent	💰 Target variable — total yearly spending by the customer

***Dropped Columns***
These were excluded due to no predictive value:

Email

Address

Avatar

***Objective***
Understand which user behaviors drive yearly spending.

Build a Linear Regression model to predict customer spending.

Evaluate performance using metrics like R², MAE, RMSE.

Explore potential improvements to accuracy.

 Model Training & Evaluation
***Tools Used***
Python (Pandas, NumPy)

Scikit-learn

Matplotlib & Seaborn

***Performance Metrics***
Metric	Score
R² Score	0.92
RMSE	14.35
MAE	11.77

The model explains 92% of the variance in yearly spending — strong performance for a linear model.

***Visualizations***
Scatter plot of Actual vs Predicted spending.

Heatmap of feature correlations.

Boxplots to check for outliers.

***Improvements Suggested***
Use Ridge/Lasso Regression to handle potential multicollinearity.

Add interaction features (e.g., Time on App × Membership Length).

Try Random Forest Regressor or XGBoost for non-linear modeling.

***Author***
Created by AUSHIJ HAJELA.
For queries or feedback, contact at: aushij.hajela32@gmail.com
