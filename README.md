# Phishing URL Detector using Machine Learning

A mini-project that uses a Random Forest Classifier to detect phishing websites based on URL-based features. Includes feature engineering, SMOTE for class imbalance, and SHAP/feature importance analysis.

## Features
- URL-based feature extraction
- SMOTE balancing
- Random Forest model with 97.76% accuracy
- SHAP-based model interpretability

## Files
- `phishing_model.ipynb`: The notebook with data prep, training, and evaluation
- `phishing_url.csv`: Dataset used (or sample)
- `requirements.txt`: List of dependencies

## Results
- Accuracy: 97.76%
- Precision/Recall: ~98% balanced across classes
- SHAP and Feature Importance explainability

## 🔧 How to Run

```bash
pip install -r requirements.txt
jupyter notebook phishing_model.ipynb
