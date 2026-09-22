# Olist E-Commerce Analytics

Portfolio analysis of the Olist Brazilian e-commerce dataset, covering data preparation, customer-satisfaction classification, transaction-based customer clustering, and visualisations.

## Repository structure

```text
.
├── data/       # Source Olist CSV datasets used by the notebook
├── notebooks/  # Exploratory analysis and modelling
│   └── Olist_Customer_Analytics.ipynb
└── src/        # Reusable Python code (currently no standalone modules)
```

## Notebook

Open [Olist_Customer_Analytics.ipynb](notebooks/Olist_Customer_Analytics.ipynb) in Jupyter or Google Colab.

The notebook reads the CSV files from `data/`, relative to the repository root. In Jupyter, start the server from the repository root. In Google Colab, clone this repository and change into its root before running the cells:

```python
!git clone <your-repository-url>
%cd olist-ecommerce-analytics
```

The analysis uses PySpark; ensure a compatible Spark environment is available before execution. The notebook writes generated outputs (`olist_processed.parquet/` and `olist_processed_csv/`) to the repository root; these outputs are intentionally ignored by Git.
