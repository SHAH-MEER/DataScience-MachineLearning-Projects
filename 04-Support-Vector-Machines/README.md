# Support Vector Machines (SVM) Project

This project explores the application of Support Vector Machines for classification tasks. The workflow includes data exploration, preprocessing, model training, evaluation, and visualization of results.

## Directory Structure

```
04-Support-Vector-Machines/
├── SVM-Project.ipynb                    # Main analysis notebook
├── DATA/                                # Datasets used for modeling
├── models/                              # Saved model files
├── visualisations/                      # Plots and figures
└── README.md                            # Project overview (this file)
```

## Project Steps

1. **Data Loading & EDA**
    - Import and inspect the dataset
    - Visualize feature distributions and relationships
    - Check for missing values and outliers

2. **Data Preprocessing**
    - Encode categorical variables
    - Feature scaling (important for SVM)

3. **Model Building**
    - Train an SVM classifier
    - Tune hyperparameters (e.g., kernel, C, gamma)

4. **Model Evaluation**
    - Assess performance using accuracy, precision, recall, F1-score, ROC-AUC
    - Visualize confusion matrix and decision boundaries

5. **Interpretation & Visualization**
    - Analyze support vectors and model coefficients
    - Visualize model outputs and decision regions

## Example Visualizations
- Correlation heatmaps
- Confusion matrix and ROC curve plots
- Decision boundary visualizations

## Getting Started
- Open `SVM-Project.ipynb` and run the cells in order.
- Plots and figures are saved in the `visualisations/` directory.
- Data is located in the `DATA/` folder.

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn, scikit-learn

---

**Author:** Shahmeer Shahzad
**Last Updated:** 2025-04-26
