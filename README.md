# Bank Marketing Campaign Prediction Model

## Project Overview
A machine learning solution developed to predict customer term deposit subscriptions for a banking marketing campaign, focusing on maximizing customer reach while balancing operational efficiency.

## Business Context
A European banking institution requires an effective approach to:
- Identify potential term deposit customers
- Optimize marketing campaign strategies
- Improve customer targeting accuracy
- Enhance resource allocation

## Dataset Information
- Banking direct marketing campaign data
- 40,000 customer records
- Clean dataset requiring minimal preprocessing

### Features
- **Customer Demographics**: Age, job, marital status, education
- **Financial Indicators**: Account balance, loan status
- **Campaign Information**: Contact duration, attempts, method
- **Target Variable**: Term deposit subscription (Yes/No)

## Model Development

### Data Processing
- Feature engineering for categorical variables
- Standardization of numeric features
- Implementation of balanced binning strategies

### Model Implementation
- Algorithm: XGBoost Classifier
- Validation: 5-fold stratified cross-validation
- Probability calibration for improved predictions

## Key Results

### Model Performance
- ROC-AUC Score: 0.921
- Accuracy: 94%
- False Positive Rate: 12.6% (Advantageous for customer reach maximization)

### Critical Insights
- **Contact Duration Analysis**:
  - Peak Success Rate: 15-30 minutes (63%)
  - Extended Calls (>30 min): 52.4% success
  - Brief Calls (0-5 min): 1-3% success
- **Model Behavior**:
  - Controlled overestimation aligns with business goals
  - Higher false positives support broader customer targeting

### Data Quality Observations
- Well-structured customer information
- Areas for improvement in contact type tracking

## Technical Implementation
- Python 3.10
- Libraries: Scikit-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn

## Business Impact
- Enhanced targeting precision
- Optimized contact strategies
- Data-driven campaign optimization
- Improved resource allocation

## Future Enhancements
- Refined contact duration strategies
- Improved tracking of contact types
- Contact strategy optimization considering operational costs
