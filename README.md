<<<<<<< HEAD
# Cardiovascular Disease Prediction

## Problem
Predict cardiovascular disease risk from patient health metrics using 
5 different classification algorithms and select the best performer.

## Dataset
Cardio Train Dataset — ~70,000 patient records
Features: age, gender, height, weight, blood pressure, cholesterol, 
glucose, smoking, alcohol, physical activity | Target: cardio (0/1)

## Approach
1. Data quality audit — found age in days, impossible height/weight/BP values
2. Cleaning — converted age to years, filtered invalid vitals, engineered
   BMI and pulse pressure features
3. EDA — 10+ visualizations (distributions, violin plots, pairplots, 
   correlation heatmap)
4. Modeling — trained and compared 5 algorithms:
   - Logistic Regression
   - K-Nearest Neighbors
   - Decision Tree
   - Random Forest
   - Support Vector Machine
5. Evaluated using Accuracy, Precision, Recall, F1, AUC, 5-fold CV
6. Hyperparameter tuned the best model with GridSearchCV
7. Saved the final model with joblib for deployment

## Results
| Model | Accuracy |
|---|---|
| (fill in from results_df) | |

Best Model: **[fill in]** — Tuned Accuracy: **[fill in]%**
Top Predictive Feature: **[fill in]**

## Files
- `cardio_disease_prediction.ipynb` — full analysis
- `cardio_clean.csv` — cleaned dataset
- `visuals/` — exported charts (10 total)
- `model/` — saved model, scaler, feature list

## Tools
Python, Pandas, Seaborn, Scikit-learn, Joblib
=======
# cardio-disease-prediction
>>>>>>> 00b16e46c03512a8c0d2b01eedab418de4d31c66
