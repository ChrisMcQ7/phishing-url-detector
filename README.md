# phishing-url-detector
Machine learning-based phishing URL detection system

This project applies machine learning algorithms to detect phishing URLs using lexical features extracted from publicly available datasets.

## Files

- `final_dataset.py` – preprocesses the raw datasets "url-dataset.csv" and "phishing_url.csv".
- `RF.py` – Random Forest model used for experimenting with features. Earlier test features were removed throughout the project for clarity.
- `RF30.py` – Version of Random Forest testing with the top 30 features.
- `SVM.py` – Support Vector Machine implementation for Model Comparison.
- `DecisionTree.py` – Decision Tree testing for Model comparison.
- `CorrelationHeatmap.py` – Visualises correlation between features to assist in feature reduction.
