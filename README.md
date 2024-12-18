# deposit-prediction-model
# Bank Marketing Campaign Analysis

## Project Background
Analysis of a European bank's direct marketing campaigns for term deposits. The goal is to predict customer subscription success and identify key customer segments for targeting.

## Business Problem
- Predict if a customer will subscribe to a term deposit
- Identify which customers are more likely to subscribe
- Determine key features influencing subscription decisions
- Achieve 81% or higher prediction accuracy using 5-fold cross validation

## Data Description
Data comes from a European bank's phone-based marketing campaigns:

### Customer Information:
- Demographics (age, job, marital status, education)
- Financial status (balance, loans)
- Contact history (duration, campaign attempts)
- Previous campaign outcomes

### Target Variable:
- Term deposit subscription (yes/no)

## Analysis Performed
1. Data Exploration
   - Customer profile analysis
   - Balance distribution
   - Campaign contact patterns

2. Feature Engineering
   - Balance grouping
   - Age categorization
   - Campaign intensity analysis

3. Predictive Modeling
   - XGBoost classifier
   - Class imbalance handling
   - 5-fold cross-validation
   - Model performance evaluation

## Requirements
- Python 3.10.12

