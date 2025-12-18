# Predictive Analysis of Consumer Spending

**Authors:** Harrison Hubbard, Levi Sessions, Gabe Anoia  
**Course:** STT-450 — Applied Statistical Methods  
**Institution:** University of North Carolina Wilmington  
**Date:** Fall 2025

---

## Overview

Built an end-to-end ML pipeline to analyze consumer behavior and predict income levels using demographic and purchasing data (2,200+ records, 28 features). This project applies regression and classification techniques to understand consumer spending patterns and predict income brackets.

## Dataset

- **Source:** [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis) (Kaggle)
- **Records:** 2,240 observations
- **Features:** 29 variables including demographics, purchasing behavior, and campaign responses
- **Target Variable:** Income level (continuous for regression, binary for classification)

## Key Contributions

- Performed full EDA with correlation analysis and feature diagnostics
- Built and compared regression models:
  - Simple Linear Regression
  - Multiple Linear Regression
  - Log-transformed Regression
- Implemented and evaluated classifiers:
  - Logistic Regression
  - LDA / QDA
  - KNN (with hyperparameter tuning)
  - Naive Bayes
  - Decision Trees
- Evaluated models using accuracy, sensitivity, specificity, ROC/AUC

## Results Highlights

| Model Type | Best Model | Key Metric |
|------------|------------|------------|
| Regression | Multiple Linear (Log-transformed) | Adjusted R² ≈ 0.75 |
| Classification | XGBoost | AUC ≈ 0.98, Accuracy = 93.05% |
| KNN | k = 7 | Optimal bias-variance balance |

## Repository Structure

\`\`\`
consumer-income-prediction/
├── README.md
├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter notebooks for analysis
├── paper/                 # Technical report (PDF)
├── results/
│   └── figures/
│       ├── classification/
│       ├── EDA/
│       └── regression/
└── slides/                # Presentation slides
\`\`\`

## Tech Stack

- **Languages:** Python, R
- **Libraries:** NumPy, Pandas, scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter / Google Colab
- **R Packages:** Used for regression diagnostics

## Artifacts

- 📄 [Technical Report](paper/Predictive_Analysis_Consumer_Profiles.pdf)
- 📊 [Presentation Slides](slides/Final.pdf)

## License

This project was developed for academic purposes as part of STT-450 at UNCW.
