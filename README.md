# Problem

Understand which physicochemical properties of red wine influence quality ratings, and identify pattern that can help assess wine quality objectively.

# Data Source

Public Wine Quality(Red Wine) dataset from the UCI Machine Learning Repository, provided as a structured CSV file.

# Final Output

Exploratory insights and feature relationships that expalin variations in wine quality ratings and guide future predictive modeling.

# Where  this fits in a Data Science Pipeline

This project represents the exploratory data analysis (EDA) stage, helping validate data quality, uncover pattern, and inform feature selection before model training.

# Wine Quality Analysis- Exploratory Data Analysis & Pipeline Context

This project explores the Wine Quality (Red Wine) dataset using Python and popular data analysis libraries.

## Business Context

Wine quality assessment is often subjective and dependent on expert tasters. By analyzing physicochemical properties of wine, this project aims to identify objective patterns that influence quality ratings, which can support quality control, production decisions, and consistency in wine manufacturing.


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

- Wine quality ratings are concentrated between 5 and 7, indicating class imbalance that must be handled in modeling.
- Alcohol content shows a strong positive relationship with wine quality, while volatile acidity shows a negative relationship.
- Several physicochemical features are right-skewed, suggesting the need for transformations during feature engineering.


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

## Next steps

- Perform feature engineering based on EDA insights.
- Train baseline machine learning models to predict wine quality.
- Evaluate model performance and address class imbalance.

## Assumptions & Constraints

- The quality score provided in the dataset is assumed to be a reliable proxy for overall wine quality.
- The dataset represents red wine samples only; insights may not generalize to white wines.
- External factors such as brand, price, and consumer preference are not included in the dataset.

## Limitations

- The dataset size is limited and may not capture all variability in real-world wine production.
- Quality labels are ordinal but treated numerically during analysis.

