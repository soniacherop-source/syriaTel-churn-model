# syriaTel-churn-model
# SyriaTel Customer Churn Prediction

## Project Overview
This project aims to predict customer churn for a telecom company (SyriaTel). The goal is to identify customers likely to leave and understand the key factors driving churn.

## Objectives
- Build machine learning models to predict churn
- Compare model performance
- Identify key drivers of churn
- Provide actionable business recommendations

## Models Used
- Logistic Regression (baseline)
- Decision Tree
- Pipeline (Logistic Regression + Scaling)
- Random Forest (Ensemble model)

## Key Findings
- Random Forest achieved the best performance across accuracy and AUC.
- Customer service calls and international plans are strong predictors of churn.
- Voice mail plans are associated with lower churn.

## Business Recommendations
- Improve customer service experience
- Review international plan pricing
- Target high-risk customers using predictive models

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Project Structure

```text
data/
notebooks/
requirements.txt
README.md
```