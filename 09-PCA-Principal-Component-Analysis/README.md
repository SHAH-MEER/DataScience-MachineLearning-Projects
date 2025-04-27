# Principal Component Analysis (PCA) Project

This project demonstrates the use of Principal Component Analysis (PCA) for dimensionality reduction and visualization, using a dataset of handwritten digits. The workflow includes data exploration, preprocessing, application of PCA, interpretation of principal components, and a variety of visualizations.

## Directory Structure

```
09-PCA-Principal-Component-Analysis/
├── PCA.ipynb                          # Main analysis notebook
├── DATA/                              # Datasets used for PCA
├── visualisations/                    # Saved plots and figures
└── README.md                          # Project overview (this file)
```

## Project Steps

1. **Data Loading & EDA**
    - Import and inspect the digit dataset
    - Visualize pixel distributions and relationships
2. **Data Preprocessing**
    - Drop label columns to isolate pixel data
    - Scale features using StandardScaler
3. **Applying PCA**
    - Fit PCA to the scaled pixel data
    - Analyze explained variance and select number of components
    - Transform data into 2D and 3D PCA spaces
4. **Visualization & Analysis**
    - Display example digit images
    - Scatterplots of digits in 2D and 3D PCA space, colored by label
    - Density (KDE) plots and pairplots of principal components
    - Cluster overlay plots (e.g., KMeans) in PCA space
    - Interactive 3D visualization using Plotly
5. **Interpretation**
    - Assess which digits are most distinct in PCA space
    - Compare explained variance for different numbers of components

## Example Visualizations
- 2D and 3D scatterplots of PCA results
- KDE density plots by digit class
- Pairplots of principal components
- Cluster overlays in PCA space
- Interactive 3D plots (Plotly)

## Getting Started
- Open `PCA.ipynb` and run the cells in order.
- Plots and figures are saved in the `visualisations/` directory.
- Data is located in the `DATA/` folder.

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn, scikit-learn, plotly

---

**Author:** Shahmeer Shahzad
**Last Updated:** 2025-04-26
