# DBSCAN Customer Segmentation Project

This project applies DBSCAN clustering to segment customers based on their spending patterns. The analysis includes exploratory data analysis (EDA), feature scaling, DBSCAN parameter tuning, cluster interpretation, and visualization.

## Directory Structure

```
08-DBSCAN/
├── DBSCAN.ipynb   # Main analysis notebook
├── DATA/
│   └── wholesome_customers_data.csv    # Customer dataset
├── visualisations/                     # Saved plots and figures
│   └── ...
└── README.md                           # Project overview (this file)
```

## Project Steps

1. **Data Loading & EDA**
    - Import and inspect the customer dataset
    - Visualize distributions and relationships between key features
    - Example plots:
        - Boxplots and violin plots of spending by channel or region
        - Heatmaps of average spending by channel/region
        - Pairplots of crucial features colored by region or channel
        - Correlation heatmaps and clustermaps
        - Stacked histograms of spending categories by group
2. **Feature Scaling**
    - Standardize features using StandardScaler for DBSCAN compatibility
3. **DBSCAN Clustering**
    - Systematic tuning of epsilon parameter
    - Outlier detection and analysis
    - Assign cluster labels to each customer
4. **Cluster Analysis & Visualization**
    - Scatterplots of spending pairs colored by DBSCAN cluster
    - Heatmaps of normalized mean spending per cluster
    - Comparison of clusters vs. outliers
    - Additional suggestions:
        - Swarm plots of spending by cluster
        - Parallel coordinates plots for cluster profiles
        - Radar/spider charts of mean spending per cluster
        - Pie charts showing cluster size distribution
        - Bar plots of cluster counts by region or channel

## Getting Started
- Open `03-DBSCAN-Project-Solutions.ipynb` and run the cells in order.
- All plots will be saved in the `visualisations/` directory.
- Data is located in `DATA/wholesome_customers_data.csv`.

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn, scikit-learn

---

**Author:** Shahmeer Shahzad
**Last Updated:** 2025-04-26
