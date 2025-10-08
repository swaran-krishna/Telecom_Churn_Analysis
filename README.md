📊 Telecom Customer Churn Analysis and Prediction
🔍 Project Overview

This project focuses on analyzing telecom customer churn using exploratory data analysis (EDA) and machine learning techniques.
The goal is to identify key drivers of customer churn, build predictive models to classify churned vs. non-churned customers, and deliver actionable insights to minimize attrition.

📁 Dataset

The dataset includes customer demographics and service usage details, such as:

Contract Type

Payment Method

Internet Service Type

Tenure

Monthly & Total Charges

Tech Support Availability

And other relevant customer attributes

⚙️ Analysis & Modeling

Performed univariate and bivariate analysis to explore data distributions and relationships with churn.

Built and compared multiple models:

Logistic Regression

Random Forest

XGBoost

Achieved perfect accuracy and high ROC-AUC on validation data.

Identified top predictors influencing churn:
Contract Type, Tenure, Payment Method, Internet Service Type, Tech Support, and Monthly Charges.

🧠 How to Use

Set up environment:

pip install -r requirements.txt


Run scripts or notebooks in the following order:

Data Preprocessing

Exploratory Analysis

Model Training & Evaluation

View outputs:

Plots for insights and model performance

PowerPoint summary in /reports
