# Problem
Understand which physicochemical properties of red wine influence quality ratings, and identify pattern that can help assess wine quality objectively.

# Data Source
Public Wine Quality(Red Wine) dataset from the UCI Machine Learning Repository, provided as a structured CSV file.

# Final Output
Exploratory insights and feature relationships that expalin variations in wine quality ratings and guide future predictive modeling.

# Where  this fits in a Data Science Pipeline
This project represents the exploratory data analysis (EDA) stage, helping validate data quality, uncover pattern, and inform feature selection before model training.

# Wine Quality EDA
This project explores the Wine Quality (Red Wine) dataset using Python and popular data analysis libraries.

## Dataset

- [Wine Quality Data (UCI)](https://archive.ics.uci.edu/ml/datasets/wine+quality)
- Contains physicochemical properties of red wine and their quality ratings.

## Steps Performed

1. Data loadading and preview
2. Data cleaning (nulls, duplicates)
3. Target variable analysis
4. Correlation analysis
5. Distribution and visualization (histograms, boxplots, heatmaps, etc.)
6. Group statistics by wine quality

## How to Run

1. Download `winequality-red.csv` and place it in this folder.
2. Open `WineQuality.ipynb` in Jupyter Notebook or VS Code.
3. Run the cells in order.

## Key Findings

- The dataset is imbalanced (most wines rated 5-7).
- Alcohol and volatile acidity are important for wine quality.
- Some features are skewed.

## References


- [UCI Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)

## Data Science Pipeline

1. **Data Source** – Red wine quality dataset provided as a CSV file.
2. **Data Loading** – Dataset loaded into Python for analysis.
3. **Data Cleaning** – Handling missing values, duplicates, and data quality issues.
4. **Exploratory Data Analysis (EDA)** ✅ – Understanding distributions, correlations, and target imbalance.
5. **Feature Engineering (Next)** – Creating meaningful features based on EDA insights.
6. **Model Training (Planned)** – Training machine learning models to predict wine quality.
7. **Evaluation (Planned)** – Measuring model performance using appropriate metrics.
8. **Final Output** – Insights and predictions related to wine quality.

