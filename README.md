# Data Analysis Case Studies

A portfolio collection by **Abubakar Rabiu Salihawa** demonstrating practical data cleaning, exploratory analysis, predictive modelling and clear communication of results.

## Case studies

### [Car Price Analysis](car-price-analysis/)

Analyses 201 vehicle records to identify the specifications most associated with price and compares linear, ridge, polynomial and random-forest regression models. The random forest achieved approximately **0.94 test R²** with an RMSE of approximately **2,800 price units**.

### [Laptop Price Analysis](laptop-price-analysis/)

Analyses 238 laptop records, explores hardware and manufacturer price relationships, and compares linear, ridge, random-forest and gradient-boosting models. Gradient boosting achieved approximately **0.48 test R²** with an RMSE of approximately **347 price units**.

## Skills demonstrated

- Python, pandas and NumPy
- Data validation and missing-value handling
- Exploratory data analysis and visualisation
- Feature preparation and categorical encoding
- Train/test evaluation using MAE, RMSE and R²
- Linear, regularised, polynomial and ensemble regression
- Reproducible Jupyter notebooks and written conclusions

## Run locally

```bash
git clone https://github.com/abubakar-r-salihawa/data-analysis-case-studies.git
cd data-analysis-case-studies
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

## Repository structure

```text
data-analysis-case-studies/
├── car-price-analysis/
│   ├── data/usedcars.csv
│   ├── car_price_analysis.ipynb
│   └── README.md
├── laptop-price-analysis/
│   ├── data/laptops.csv
│   ├── laptop_price_analysis.ipynb
│   └── README.md
├── ATTRIBUTION.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── requirements.txt
```

## Attribution

These projects originated from learning activities associated with IBM Data Analysis with Python. The analysis has been restructured, corrected, extended and documented as independent portfolio work. See [ATTRIBUTION.md](ATTRIBUTION.md).
