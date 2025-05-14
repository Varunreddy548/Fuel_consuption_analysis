# CO2 Emissions Prediction Model

This project uses a dataset of cars and their specifications to predict **CO2 emissions** using a **Linear Regression model**. The model is trained using engine and fuel consumption features from a dataset (likely from the Canadian vehicle dataset).

## Project Overview

This project demonstrates the following:

* Loading and viewing a vehicle dataset using **pandas**.
* Visualizing and analyzing car features.
* Training a **Linear Regression** model from sklearn to predict CO2EMISSIONS.
* Evaluating the model using **Mean Squared Error (MSE)** and **R² Score**.
* Displaying a sample of the dataset and plotting the model's predictions.

## Sample Output

```
   MODELYEAR   MAKE    MODEL   VEHICLECLASS  ENGINESIZE  CYLINDERS  ...  CO2EMISSIONS
0       2014  ACURA     ILX       COMPACT         2.0          4    ...     196
1       2014  ACURA     ILX       COMPACT         2.4          4    ...     221
...
Mean Squared Error: 85.69
R² Score: 0.98
```

## Requirements

* Python 3.x
* pandas
* matplotlib
* scikit-learn

You can install the requirements using:

```bash
pip install -r requirements.txt
```

## Files

* `co2_prediction.py` - Main Python script that loads data, trains model, and visualizes results.
* `README.md` - Project documentation.
* `requirements.txt` - List of required Python packages.

## Features Used for Training

* Engine Size
* Number of Cylinders
* Fuel Consumption (City, Hwy, Combined)
* Fuel Type

## Model

* **Type**: Linear Regression
* **Target**: `CO2EMISSIONS`
* **Performance**:

  * **MSE**: 85.69
  * **R² Score**: 0.98

## Future Work

* Try other models like **Random Forest**, **XGBoost**
* Add more feature engineering
* Create a simple web interface for user predictions

