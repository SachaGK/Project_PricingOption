# Option Pricing with Machine Learning

Predict call option prices using XGBoost on AAPL options data.

## Results

| Model | R² | MAE |
|-------|-----|-----|
| Linear Regression | 0.62 | $16.31 |
| Random Forest | 0.85 | $6.50 |
| XGBoost | 0.87 | $6.09 |

## Usage

```
pip install -r requirements.txt
```

Run notebooks in order: 01 → 02 → 03

## Structure

```
notebooks/   # EDA, preprocessing, modeling
figs/        # plots
models/      # config
```

## Data

Not included. Place your options CSV in `data/raw/`.
