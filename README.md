# Clustering-Based-Cardiac-Health-Risk-Profiling
This project analyzes a cardiac health dataset using unsupervised learning techniques specifically K-Means and Hierarchical Clustering. The goal is to group patients based on similar health characteristics and assess potential heart risk levels, enabling early intervention and data-driven public health strategies.

## Dataset

The dataset (`Modified_Heart_failure_data.csv`) includes clinical features such as:
- Age
- Anaemia (Yes/No)
- Diabetes (Yes/No)
- High Blood Pressure (Yes/No)
- Platelet Count
- Serum Creatinine
- Serum Sodium
- Ejection Fraction
- Creatinine Phosphokinase
- Smoking (Yes/No)
- Death Event (used only for insight, not as a label)

These indicators help uncover hidden patterns and form meaningful patient clusters for health risk stratification.

## Objectives

- Preprocess and normalize the cardiac dataset.
- Apply K-Means and Hierarchical Clustering algorithms.
- Use PCA to reduce dimensions for better visualization.
- Evaluate cluster quality using silhouette scores.
- Interpret results in a healthcare risk assessment context.

## Tools & Libraries

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Scipy
- PCA (Principal Component Analysis)

## Key Insights

- Identified clusters revealed distinct patient groups with high vs. low cardiac risk factors.
- Clustering helped stratify patients without needing labeled data.
- Evaluation metrics confirmed that both models produced interpretable and consistent clusters.
## How to Run
- Clone the repository
- Install dependencies: pip install -r requirements.txt
- Run the notebook in notebooks/ to see preprocessing, modeling, and results
- -------------------------------------------------------------------------------------
Note: This project is for educational purposes and not clinical use.
