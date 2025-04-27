# Tree-Based Methods Project

This project applies tree-based machine learning methods to the Telco Customer Churn dataset, with the goal of predicting customer churn and interpreting the factors that drive these predictions. The workflow includes exploratory data analysis, data preprocessing, model training (Decision Trees, Random Forests, Gradient Boosting), evaluation, and visualization.

## Directory Structure

```
05-Tree-Based-Methods/
├── Tree-Methods.ipynb                 # Main analysis notebook
├── DATA/                              # Dataset (Telco-Customer-Churn.csv)
├── models/                            # Saved model files
├── visualisations/                    # Plots and figures
└── README.md                          # Project overview (this file)
```

## Project Steps

1. **Data Loading & EDA**
    - Import and inspect the Telco Customer Churn dataset
    - Visualize feature distributions and relationships
    - Identify missing values and outliers
2. **Data Preprocessing**
    - Handle missing values
    - Encode categorical variables
    - Feature scaling (if required)
3. **Model Building**
    - Train Decision Tree, Random Forest, and Gradient Boosting classifiers
    - Tune hyperparameters for each model
4. **Model Evaluation**
    - Assess performance using accuracy, precision, recall, F1-score, ROC-AUC
    - Visualize confusion matrix and feature importances
5. **Interpretation & Visualization**
    - Analyze feature importances and decision paths
    - Visualize model outputs and decision boundaries

## Example Visualizations
- Histograms and boxplots of key features
- Correlation heatmaps
- Feature importance plots
- Confusion matrix and ROC curve plots
- Customer churn rate by tenure, contract type, and internet service

## Getting Started

1. Install requirements:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
2. Open `Tree-Methods.ipynb` in Jupyter and run the cells sequentially.

---

For details, see the notebook and code comments. Contributions and further exploration are welcome!
