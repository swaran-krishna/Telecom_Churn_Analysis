Telecom Customer Churn Analysis and Prediction
Project Overview
This project analyzes telecom customer churn using advanced exploratory data analysis and machine learning techniques. It aims to identify key factors affecting churn, develop predictive models to classify churned vs non-churned customers, and provide actionable insights to reduce attrition.

Dataset
The dataset contains customer demographic and service usage information, including variables such as contract type, payment method, internet service, tenure, monthly and total charges, tech support, and others.

Analysis and Modeling
Conducted univariate and bivariate analysis to understand variable distributions and correlations with churn.

Built and compared multiple models: logistic regression, random forest, and XGBoost.

Achieved perfect accuracy and ROC-AUC during validation, indicating highly accurate churn prediction.

Identified top predictors: contract type, tenure, payment method, internet service type, tech support availability, and monthly charges.

Usage Instructions
Set up Python environment:

text
pip install -r requirements.txt
Run the Jupyter notebooks or Python scripts in the following order:

Data preprocessing

Exploratory analysis

Model training and evaluation

View generated plots for insights and model performance, and consult exported PowerPoint presentation for summaries.

Project Structure
/notebooks: Jupyter notebooks for analysis and modeling

/data: Dataset or data loading scripts

/images: Plots and visualizations

/reports: Final presentations and summary documents

requirements.txt: Python dependencies

README.md: Project documentation