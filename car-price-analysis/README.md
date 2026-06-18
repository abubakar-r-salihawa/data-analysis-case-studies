# Car Price Analysis

This case study analyses **201 automobile records** to identify the specifications most associated with price and compare several regression models.

## Workflow

- Validated data types and missing values.
- Explored relationships between price, engine size, horsepower, curb weight, drive wheels and other specifications.
- Prepared numeric and categorical features for modelling.
- Compared linear regression, ridge regression, polynomial regression and random forest.
- Evaluated the models on held-out test data using MAE, RMSE and R².

## Result

The **Random Forest** model provided the strongest test performance:

- **R²:** 0.936
- **RMSE:** approximately 2,799.90

Open `car_price_analysis.ipynb` for the complete reproducible workflow.
