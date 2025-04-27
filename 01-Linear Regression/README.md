# Linear Regression Project

This project uses linear regression to predict house prices using the Ames Housing dataset. The workflow includes exploratory data analysis (EDA), data preprocessing, model training, evaluation, and interpretation of results.

## Directory Structure

```
01-Linear Regression/
├── Linear-Regression.ipynb           # Main analysis notebook
├── DATA/                             # Dataset (Ames_Housing_Data.csv)
├── models/                           # Saved model files
├── visualisations/                   # Plots and figures
└── README.md                         # Project overview (this file)
```

## Project Steps

1. **Data Loading & EDA**
    - Import and inspect the Ames Housing dataset
    - Visualize feature distributions and relationships
    - Identify missing values and outliers
2. **Data Preprocessing**
    - Handle missing values
    - Encode categorical variables
    - Feature scaling (if required)
3. **Model Building**
    - Train linear regression model(s) (OLS, regularized variants if applicable)
    - Feature selection and engineering
4. **Model Evaluation**
    - Assess performance using RMSE, MAE, R²
    - Visualize residuals and predictions
5. **Interpretation & Visualization**
    - Analyze model coefficients and feature impacts
    - Visualize relationships and model outputs

## Example Visualizations
- Histograms and boxplots of key features
- Correlation heatmaps
- Scatterplots of features vs. SalePrice
- Residual plots
- Predicted vs. actual sale price plots

## Getting Started

1. Install requirements:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
2. Open `Linear-Regression.ipynb` in Jupyter and run the cells sequentially.

---

For details, see the notebook and code comments. Contributions and further exploration are welcome!
