Project Title
Reqruiting Funnel AI 
(Reqruiting Funnel Analytics & Attrition Prediction)

Problem Statement
Hiring teams often face low offer acceptance and early employee attrition, leading to high recruitment costs and productivity loss. 
This project builds a data-driven analytics pipeline to help hiring managers make better decisions during recruitment and early onboarding.

Tech Stack:
Python (Pandas, NumPy, Scikit-learn)
SQL (SQLite)
Tools : Jupyter Notebook, VS Code.

Solution Overview:
The project analyzes hiring data and builds predictive models to:

1.Estimate the probability that a candidate will accept an offer.
2.Identify employees at risk of leaving within the first 6 months.
3.Provide actionable insights for HR teams to improve hiring efficiency and retention.

Data Overview:
The dataset includes 1,000 simulated candidate records with:
Experience level
Skills score
Communication score
Salary offered
Offer acceptance outcome
Early attrition indicator

Analysis & Modeling

1. Exploratory Analysis:
Analyzed offer acceptance and attrition patterns.
Identified trends by hiring source and candidate profile.

2. SQL Insights:
Built hiring funnel metrics using SQL queries.
Compared acceptance and attrition rates across sources.

3, Machine Learning Models:

Offer Acceptance Model:
Logistic Regression with feature scaling and class balancing.
Outputs probability of offer acceptance.

Early Attrition Model:
Random Forest with class imbalance handling and threshold tuning.
Outputs early attrition risk score.

Project Structure
hiring-funnel-analytics-ml/
│
├── data/
│   └── hiring_data.csv
├── notebooks/
│   ├── 01_data_generation.ipynb
│   ├── 02_data_exploration.ipynb
│   ├── 03_sql_analysis.ipynb
│   └── 04_ml_models.ipynb
└── outputs/
    └── hiring.db


Key Results
Improved recall for offer acceptance and early attrition through probability-based threshold tuning.
Identified salary, experience, and communication as key drivers of early attrition.




