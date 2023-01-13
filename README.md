# Laptop Price Prediction

This project aims to provide an accurate and reliable model to predict laptop prices using XGBRegressor.

## Dataset

The dataset consist a target variable (Prices_euros) and of 11 features, which are:

| Feature   | Description |
| ----------| ------------|
| Company      | Laptop Manufacturer|
| Product  | Brand and Model |
| TypeName     | Type (Notebook, Ultrabook, Gaming, etc.) |
| Inches      | Screen Size |
| ScreenResolution | Screen Resolution |
| Cpu | Central Processing Unit (CPU) |
|Ram |Laptop RAM |
|Memory |Hard Disk / SSD Memory|
|GPU | Graphics Processing Units (GPU) |
| OpSys | Operating System |
| Weight | Laptop Weight |

Dataset source: [here](https://www.kaggle.com/datasets/muhammetvarl/laptop-price)

## Results

The results are shown below:

| Metric | Training Score | Testing Score |
|--------|----------------|---------------|
| R-Squared | 0.963   | 0.906  |
| RMSE      | 133.88 | 216.17 |

## Requirements

In order to run the python script and notebook, you will need to have the following packages installed:

* matplotlib
* numpy
* pandas
* scikit-learn
* xgboost
