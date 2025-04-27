# Logistic Regression Project

This project explores logistic regression techniques for binary classification using the heart disease dataset. The workflow includes data exploration, preprocessing, model training, evaluation, and visualization of results.

## Directory Structure

```
02-Logistic-Regression-Models/
├── Logistic-Regression-Project.ipynb   # Main analysis notebook
├── DATA/
│   └── heart.csv                      # Dataset used for modeling
├── models/                            # Saved model files
├── visualisations/                    # Plots and figures
└── README.md                          # Project overview (this file)
```

## Project Steps

1. **Data Loading & EDA**
    - Import and inspect the heart disease dataset
    - Visualize feature distributions and relationships
    - Check for missing values and outliers
2. **Data Preprocessing**
    - Handle missing values 
    - Encode categorical variables
    - Feature scaling 
3. **Model Building**
    - Train a logistic regression model for binary classification
    - Optionally, experiment with regularization and hyperparameter tuning
4. **Model Evaluation**
    - Assess performance using accuracy, precision, recall, F1-score, ROC-AUC
    - Visualize confusion matrix and ROC curve
5. **Interpretation & Visualization**
    - Analyze feature coefficients and their impact on predictions
    - Visualize important features and model outputs

## Example Visualizations
- Histograms and boxplots of key features
- Correlation heatmaps
- Confusion matrix and ROC curve plots
- Bar plots of feature importances

## Getting Started
- Open `Logistic-Regression-Project.ipynb` and run the cells in order.
- Plots and figures are saved in the `visualisations/` directory.
- Data is located in `DATA/heart.csv`.

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn, scikit-learn

---

**Author:** Shahmeer Shahzad
**Last Updated:** 2025-04-26
