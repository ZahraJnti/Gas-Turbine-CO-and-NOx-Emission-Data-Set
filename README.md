# Gas Turbine CO and NOx Emission Prediction

## Overview
This project explores the prediction of **CO** (Carbon Monoxide) and **NOx** (Nitrogen Oxides) emissions in gas turbines using real-world operational data. The dataset is sourced from the UCI Machine Learning Repository and contains measurements from a Turbofan engine under various ambient and control conditions.

## Dataset
- **Source**: [UCI Machine Learning Repository – Gas Turbine CO and NOx Emission](https://archive.ics.uci.edu/ml/datasets/Gas+Turbine+CO+and+NOx+Emission+Data)
- **Fetched using**: [`ucimlrepo`](https://pypi.org/project/ucimlrepo/)
- **Features**: Temperature, ambient pressure, humidity, fuel flow, etc.
- **Targets**: CO and NOx emissions

## Project Structure
- `Gas_Turbine_CO_and_NOx_Emission.ipynb`: Main notebook containing data fetching, merging, and basic data inspection.

## Setup Instructions
### Requirements
Ensure Python 3.8+ and install dependencies:
```bash
pip install ucimlrepo pandas
```

### Run the Notebook
```bash
jupyter notebook Gas_Turbine_CO_and_NOx_Emission.ipynb
```

## Key Steps Performed

1. Dataset was fetched programmatically from the UCI repository.
2. Features (`X`) and targets (`y`) were merged into a single `pandas` DataFrame.
3. Initial data inspection using `.info()` to verify structure and types.

## Future Work (Optional Suggestions)

- Feature engineering and correlation analysis.
- Train ML regression models (e.g. Linear Regression, Random Forest, XGBoost).
- Evaluate prediction performance (MAE, RMSE, R²).
- Visualize emission trends under different operating conditions.

