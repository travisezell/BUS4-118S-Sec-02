# Module 3 Machine Learning Coding Assignment

This repository contains a Colab-ready notebook implementing:

- Part 1: House price prediction (Linear Regression, OneHotEncoder)
- Part 2: Customer churn prediction (Logistic Regression, StandardScaler + OneHotEncoder, probability + 0.5 threshold)
- Part 3: Customer segmentation (K-Means, scaling, elbow plot, cluster analysis + strategies)
- Part 4 (Extra Credit): Housing demand forecasting tool (synthetic time series loaded from CSV, regression forecast + visualization)

## How to run (Google Colab)

1. Open `notebooks/Module3_ML_Assignment.ipynb` in Colab.
2. Upload these datasets to the Colab runtime (same working directory as the notebook):
   - `AmesHousing.csv`
   - `WA_Fn-UseC_-Telco-Customer-Churn.csv`
3. Run the notebook top-to-bottom.

Outputs are written to the `artifacts/` folder (CSV files and plots).

## Data sources

- Ames Housing Dataset (Kaggle): https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset
- Telco Customer Churn (Kaggle distribution of IBM sample): https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Notes

- Datasets are not committed to this repository. Download them from the sources above or upload them directly into Colab.
