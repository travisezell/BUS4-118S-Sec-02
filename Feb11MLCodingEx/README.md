# Feb11MLCodingEx (Module 3 ML Coding Exercise)

This repo contains a Colab-ready notebook that meets the Module 3 checklist and rubric requirements:

- Part 1: House price prediction (Linear Regression, OneHotEncoder for location)
- Part 2: Customer churn prediction (Logistic Regression, StandardScaler + OneHotEncoder, churn probability + 0.5 threshold)
- Part 3: Customer segmentation (K-Means, scaling, elbow plot, cluster analysis and marketing strategies)
- Part 4 (Extra Credit): Housing demand forecasting (synthetic time series saved to CSV, regression forecast + visualization)

## Repository structure

- `notebooks/` contains the notebook
- `data/` contains the input datasets used by the notebook
- `artifacts/` is created when you run the notebook and stores generated outputs (CSVs and plots)
- `docs/` contains the assignment checklist and grading rubric for reference

## How to run (Google Colab)

1. Open `notebooks/Coding_Exercise_ML_Basics_Final_Deliv.ipynb` in Colab.
2. Run the notebook top-to-bottom.

The notebook reads datasets from `data/`:
- `data/AmesHousing.csv`
- `data/WA_Fn-UseC_-Telco-Customer-Churn.csv`

Outputs are written to `artifacts/` (created automatically).

## Data sources (also cited in notebook comments)

- Ames Housing Dataset (Kaggle): https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset
- Telco Customer Churn (Kaggle distribution of IBM sample): https://www.kaggle.com/datasets/blastchar/telco-customer-churn
