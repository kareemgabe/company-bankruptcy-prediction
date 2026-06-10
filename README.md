# Company Bankruptcy Prediction

This project aims to predict corporate bankruptcy using financial indicators from the Taiwan Economic Journal dataset.

## Dataset
- Source: Taiwan Economic Journal (1999–2009)
- Samples: 6,819 companies
- Features: 95 financial indicators

## Workflow
- Data Understanding
- Exploratory Data Analysis (EDA)
- Handling Class Imbalance
- Logistic Regression
- SMOTE
- Random Forest
- XGBoost
- Model Evaluation
- Feature Importance

## Results

| Model | Accuracy | Precision | Recall | F1 |
|---------|----------|-----------|---------|-----|
| Logistic Regression | 96% | 0.00 | 0.00 | 0.00 |
| Logistic + Class Weight | 75% | 0.05 | 0.36 | 0.09 |
| Logistic + SMOTE | 76% | 0.05 | 0.34 | 0.08 |
| Random Forest | 97% | 0.82 | 0.20 | 0.33 |
| XGBoost | 96% | 0.44 | 0.55 | 0.49 |

## Best Model

XGBoost achieved the best balance between precision and recall.

- ROC-AUC: 0.948
- Precision: 44%
- Recall: 55%
- F1-score: 49%

## Technologies Used

- Python
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
