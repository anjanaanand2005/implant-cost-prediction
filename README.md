# Hospital Implant Cost Prediction — RandomForestRegressor

Predicts the cost of hospital implants from patient demographic, clinical, and admission data, and identifies the strongest cost drivers.

## Dataset
248-patient hospital records dataset, including demographics, admission details, and treatment information.

## Approach
- Cleaned and preprocessed patient records, engineering features including BMI, age groups, ICU-stay ratio, and cost-per-day.
- Trained a RandomForestRegressor to predict implant cost.
- Extracted feature importance to identify the strongest cost drivers.

## Result
**R² = 0.89, MAE ≈ $1,608** on held-out test data. Implant usage type and daily hospitalization cost were identified as the top cost drivers.

## Files
- `implant_cost_prediction.py` — full pipeline: preprocessing, feature engineering, model training, and evaluation
