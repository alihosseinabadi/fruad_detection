# fruad_detection
based project of kaggle dataset which is leads you work with PCA and already reduce dimansion of data with aspect of super unbalanced fruad into data the goal is how deal with unbalanced data which feature engeering we do what type of evaluation we use F1 AOC-AUC PERSICSION and how the SHAP tell us story behind these results

# Credit Card Fraud Detection

## Project Overview
This project implements machine learning models to detect fraudulent credit card transactions using the Kaggle Credit Card Fraud Detection dataset. The dataset contains 284,807 transactions with 28 PCA-transformed features (V1-V28) along with Time and Amount fields.

## Dataset
- **Source**: Kaggle Credit Card Fraud Detection Dataset
- **Transactions**: 284,807 total
- **Fraud Cases**: 492 (0.17%)
- **Features**: 30 features (Time, V1-V28, Amount)
- **Target**: Class (0 = Legitimate, 1 = Fraudulent)

## Models Implemented
- Logistic Regression
- Decision Tree
- Random Forest
- Isolation Forest
- Gradient Boosting Classifier
- CatBoost

## Feature Engineering
- Standard scaling applied to Time and Amount features
- Feature selection based on 28 PCA-transformed features
- Handled class imbalance using appropriate techniques

## Model Interpretability
Used SHAP (SHapley Additive exPlanations) to analyze feature importance and understand model predictions across all implemented models.

## Results

 Logistic Regression 
 svm
 Decision Tree
 Random Forest 
 Isolation Forest 
 Gradient Boosting 
 CatBoost 

## Key Findings
- Ensemble methods (Random Forest, CatBoost) achieved the best performance
- SHAP analysis identified the most influential features for fraud detection
- [Add 1-2 specific insights from your SHAP analysis]

## Technologies Used
- Python
- scikit-learn
- XGBoost
- CatBoost
- SHAP
- pandas, numpy
- matplotlib, seaborn
- imbalanced-learn

## Installation

```bash
# Clone repository
git clone [repository-url]

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook credit_fraud_detection.ipynb
