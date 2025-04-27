# KMeans Clustering Project

This project applies KMeans clustering to country-level data from the CIA World Factbook in order to discover and interpret groups of countries with similar socioeconomic characteristics. The workflow includes exploratory data analysis, data cleaning, feature engineering, clustering, and visualization.

## Directory Structure

```
07-Kmeans-Clustering/
├── 03-Kmeans-Clustering-Project-Solutions.ipynb   # Main analysis notebook
├── DATA/                                         # Datasets (CIA_Country_Facts.csv, country_iso_codes.csv)
├── models/                                       # Saved model files
├── visualisations/                               # Plots and figures
└── README.md                                     # Project overview (this file)
```

## Project Steps

1. **Data Loading & EDA**
    - Import and inspect the dataset
    - Visualize feature distributions and relationships
    - Identify missing values and outliers
2. **Data Cleaning & Preparation**
    - Impute missing values (regional means or zero for small islands)
    - Drop countries with insufficient data
    - Encode categorical variables (Region) as dummies
    - Scale features for clustering
3. **KMeans Clustering**
    - Fit KMeans models for K=2 to K=30
    - Use the elbow method to select optimal K
    - Assign cluster labels and interpret results
4. **Visualization & Interpretation**
    - Plot feature distributions by cluster
    - Visualize clusters on a world map (Plotly choropleth)
    - Analyze which features drive cluster formation

## Example Visualizations
- Histograms and boxplots of key features
- Correlation heatmaps and clustermaps
- Elbow plot of K vs. SSD
- Bar plot of SSD differences
- World map colored by cluster assignment

## Getting Started

1. Install requirements:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn plotly
    ```
2. Open `03-Kmeans-Clustering-Project-Solutions.ipynb` in Jupyter and run the cells sequentially.

---

For details, see the notebook and code comments. Contributions and further exploration are welcome!
