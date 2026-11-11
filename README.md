# Car Price Prediction

A model that predicts car MSRP with regularized linear regression implemented in NumPy.

## Run

From the project root:

```bash
python -m pip install notebook pandas numpy matplotlib seaborn
python -m jupyter notebook
```

Run all notebook cells. The dataset is included at `data/data.csv`.

## Model

The model cleans the data, splits it into training (60%), validation (20%), and test (20%) sets, and trains on log-transformed MSRP. It uses car specifications and categorical features, then converts predictions back to MSRP values.

The model's saved results show **0.4565 validation RMSE** and **0.4518 test RMSE**, both measured on log-transformed prices. The final cells show a single-car prediction.

Data source: [Car Features and MSRP](https://www.kaggle.com/CooperUnion/cardataset).

## Author

vfb-dev - Building intelligent systems
