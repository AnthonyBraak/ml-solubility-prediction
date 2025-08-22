# Solubility Prediction using ML

This project predicts the aqueous solubility (LogS) of molecules using machine learning techniques. 

## Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- scikit-learn
- Matplotlib

## Models Used
- Linear Regression
- Random Forest Regressor

## Evaluation Metrics
- Mean Squared Error (MSE)
- R-squared (R²)

## How to Run
1. Clone the repo
2. Install dependencies:

```
pip install -r requirements.txt
```
3. Run the Jupyter Notebook:
```
jupyter notebook ml_solubility.ipynb
```

## 📁 Data Source
- [Delaney solubility dataset](https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv)

## 📷 Visualizations
- Model prediction scatter plots
- Regression lines for model fits

## Results Summary

Both models were evaluated using Mean Squared Error (MSE) and R-squared (R²) on training and test data.

| Model            | Train R² | Test R² | Train MSE | Test MSE |
|------------------|----------|---------|-----------|----------|
| Linear Regression| 0.72     | 0.65    | 0.25      | 0.30     |
| Random Forest    | 0.95     | 0.78    | 0.05      | 0.20     |

The Random Forest Regressor achieved better overall accuracy, suggesting it captured the data patterns more effectively than Linear Regression.
