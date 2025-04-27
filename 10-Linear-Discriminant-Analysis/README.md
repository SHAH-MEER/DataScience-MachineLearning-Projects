# Breast Cancer Detection Using Linear Discriminant Analysis (LDA)

## Overview

This project applies Linear Discriminant Analysis (LDA) to the Breast Cancer Wisconsin (Diagnostic) dataset to classify tumors as benign or malignant. The workflow includes exploratory data analysis (EDA), data preprocessing, model training, evaluation, visualization, and model persistence.

## Dataset

- **Source:** [UCI Machine Learning Repository – Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Description:** The dataset contains 30 features computed from digitized images of fine needle aspirate (FNA) of breast masses, along with a binary target variable indicating benign or malignant diagnosis.

## Steps

1. **Exploratory Data Analysis (EDA)**
   - Visualize class distribution and key feature distributions
   - Analyze correlations and relationships between features

2. **Data Preparation**
   - Split data into features (X) and target (y)
   - Scale features using StandardScaler
   - Split data into training and testing sets

3. **Model Training**
   - Apply LDA to the training data

4. **Model Evaluation**
   - Evaluate model performance using accuracy, F1-score, confusion matrix, and classification report

5. **Visualization**
   - Visualize LDA component(s) to assess class separation

6. **Model Persistence**
   - Save the trained LDA model and scaler using `joblib` for future use

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib

Install dependencies with:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository and navigate to the project directory.
2. Place the dataset in the appropriate folder (e.g., `DATA/cancer_tumor_data_features.csv`).
3. Run the Jupyter notebook `LDA.ipynb` to reproduce the analysis, training, evaluation, and visualizations.
4. The trained model and scaler will be saved in the `models/` directory.

## Results

- LDA achieved high accuracy in separating benign and malignant tumors.
- Visualizations confirm clear class separation along the first LDA component.
- The model and scaler are persisted for future inference.

## Next Steps

- Apply cross-validation for more robust evaluation.
- Compare LDA with other classifiers such as QDA and Logistic Regression.
- Explore additional feature engineering or dimensionality reduction techniques.


**Author:** Shahmeer Shahzad
**Last Updated:** 2025-04-26