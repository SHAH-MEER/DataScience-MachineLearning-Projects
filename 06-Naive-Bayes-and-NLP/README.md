# Text Classification: Sentiment Analysis of Movie Reviews

This project focuses on building a text classification model to determine the sentiment (positive or negative) of movie reviews. The workflow includes data cleaning, exploratory data analysis (EDA), feature extraction, model training, evaluation, and visualization.

## Directory Structure

```
06-Naive-Bayes-and-NLP/
├── Text-Classification.ipynb             # Main analysis notebook
├── DATA/                                 # Datasets for modeling
├── models/                               # Saved model files
├── visualisations/                       # Plots and figures
└── README.md                             # Project overview (this file)
```

## Project Steps

1. **Data Loading & Cleaning**
    - Import and inspect the dataset
    - Remove missing values and blank reviews
2. **Exploratory Data Analysis (EDA)**
    - Analyze review lengths and sentiment distribution
    - Visualize word frequencies, bigrams, and vocabulary richness
3. **Feature Engineering**
    - Extract features using TF-IDF vectorization
4. **Model Training**
    - Train a supervised learning model (e.g., Multinomial Naive Bayes)
    - Hyperparameter tuning with cross-validation
5. **Model Evaluation**
    - Evaluate performance using accuracy, precision, recall, F1-score
    - Visualize confusion matrix and classification metrics
6. **Interpretation & Next Steps**
    - Interpret results and suggest improvements or extensions

## Example Visualizations
- Distribution of review lengths
- Sentiment class balance
- Word clouds and top n-grams
- Confusion matrix heatmaps

## Getting Started
- Open `Text-Classification.ipynb` and run the cells in order.
- Plots and figures are saved in the `visualisations/` directory.
- Data is located in the `DATA/` folder.

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn, scikit-learn, wordcloud

---

**Author:** Shahmeer Shahzad  
**Last Updated:** 2025-04-27
