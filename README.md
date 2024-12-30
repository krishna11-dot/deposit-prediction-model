# Bank Marketing Campaign Prediction Model 

## Project Overview
A comprehensive machine learning solution to predict customer term deposit subscriptions using advanced data science techniques.

##  Business Problem
The project addresses critical marketing challenges:
- Predicting customer likelihood of subscribing to term deposits
- Identifying high-potential customer segments
- Optimizing marketing campaign strategies
- Achieving high-precision predictive modeling

##  Dataset Characteristics
### Data Source
- European bank's direct marketing campaign dataset
- Contains comprehensive customer interaction records

### Key Features
- Demographics
  - Age
  - Job category
  - Marital status
  - Education level

- Financial Indicators
  - Account balance
  - Loan status
  - Previous banking interactions

- Campaign Metrics
  - Contact duration
  - Number of campaign attempts
  - Contact method

### Target Variable
- Term deposit subscription (Binary: Yes/No)

##  Methodology

### 1. Data Preprocessing
- Handling missing values
- Categorical variable encoding
- Feature scaling
- Balanced binning techniques

### 2. Feature Engineering
- Job category standardization
- Age group categorization
- Balance distribution analysis
- Campaign contact intensity mapping

### 3. Model Development
- Algorithm: XGBoost Classifier
- Cross-validation strategy: 5-fold stratified
- Hyperparameter tuning
- Probability calibration

### 4. Model Evaluation
- Performance Metrics
  - ROC-AUC
  - Precision
  - Recall
  - F1-Score
- Confusion matrix analysis
- Feature importance ranking

##  Key Achievements
Through rigorous model development and evaluation,delivered a highly accurate and reliable predictive solution for the bank's marketing challenges:

- Prediction Accuracy: 94%
- ROC-AUC Score: 0.921
- Identified critical customer segments
- Developed actionable marketing recommendations

##  Key Insights
- Optimal call duration: 10-15 minutes
- Highest conversion segments
  - Age group: 26-35
  - Job category: Technical professionals
  - Best contact strategies revealed

##  Technical Stack
- Python 3.10
- Libraries:
  - Scikit-learn
  - XGBoost
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn

##  Potential Business Impact
- Improved marketing targeting
- Enhanced campaign efficiency
- Reduced customer acquisition costs
- Data-driven decision making
