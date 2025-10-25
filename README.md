# University Admission Prediction

## Overview
This project predicts the probability of a student's admission to a university using regression-based machine learning models.

## Steps to Run
1. Open the Jupyter Notebook: `model.ipynb`
2. Ensure the dataset `university_admission.csv` is in the same directory.
3. Run all cells sequentially.
4. Outputs (plots, summary, metrics) will be generated automatically.

## Dependencies
Install required packages using:
```bash
pip install pandas numpy scikit-learn matplotlib
```

## Files
- `university_admission.csv` — Dataset
- `model.ipynb` — Source notebook
- `summary_report.pdf` — Summary report
- `README.md` — This readme file

## Results Summary
| Model | RMSE | MAE | R² | CV RMSE |
|--------|------|-----|-----|---------|
| Linear Regression | 0.062 | 0.043 | 0.806 | 0.062 |
| Random Forest | 0.066 | 0.044 | 0.783 | 0.066 |
| Gradient Boosting | 0.068 | 0.047 | 0.768 | 0.068 |
