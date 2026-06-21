# Data Analysis Case Studies

A portfolio collection by **Abubakar Rabiu Salihawa** demonstrating practical data cleaning, exploratory analysis, predictive modelling and clear communication of results.

## Case studies

### [Car Price Analysis](car-price-analysis/)

Analyses 201 vehicle records to identify the specifications most associated with price. The notebook explores the data and evaluates a random-forest regression model on held-out records.

**Validated result:** approximately **0.94 test R²** and **2,800 RMSE**.

### [Laptop Price Analysis](laptop-price-analysis/)

Analyses 238 laptop records and investigates how hardware characteristics relate to price using gradient-boosting regression.

**Validated result:** approximately **0.48 test R²** and **347 RMSE**.

## Skills demonstrated

- Python, pandas and Matplotlib
- Data validation and missing-value handling
- Exploratory data analysis
- Feature selection and regression modelling
- Train/test evaluation using MAE, RMSE and R²
- Reproducible Jupyter notebooks
- Clear reporting of findings and limitations

## Repository structure

```text
data-analysis-case-studies/
├── car-price-analysis/
│   ├── car_price_analysis.ipynb
│   └── README.md
├── laptop-price-analysis/
│   ├── laptop_price_analysis.ipynb
│   └── README.md
└── ATTRIBUTION.md
```

The notebooks download their source datasets from the IBM Skills Network data repository when executed.

## Run the projects

1. Clone or download this repository.
2. Open the selected `.ipynb` file in Jupyter Notebook, JupyterLab, VS Code or Google Colab.
3. Run the cells from top to bottom.

Required Python packages: `pandas`, `matplotlib` and `scikit-learn`.

## Attribution

These projects originated from learning activities associated with IBM Data Analysis with Python. The workflows were restructured, corrected, extended and documented as portfolio projects. See [ATTRIBUTION.md](ATTRIBUTION.md).
