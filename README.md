


# Forecasting Carbon Emissions Using Machine Learning Models

## Overview

This project investigates the application of modern **machine learning (ML) and deep learning (DL) models** to forecast **carbon dioxide (CO₂) emissions** across 93 countries.

Historical CO₂ emissions data from **1970 to 2023** are used to develop and evaluate the forecasting models. The models are trained using data from **1970–2015** and evaluated using data from **2016–2023**. Finally, CO₂ emissions are forecast up to **2030**.

The project focuses on four models:

* Artificial Neural Network (ANN)
* Deep Neural Network (DNN)
* Convolutional Neural Network (CNN)
* Long Short-Term Memory (LSTM)

## Dataset

The dataset was collected from the **World Bank**.

* Number of countries: **93**
* Historical data: **1970–2023**
* Training period: **1970–2015**
* Testing period: **2016–2023**
* Forecasting period: **2024–2030**

The dataset is provided in the repository as:

```text
co2new.xlsx
```

## Methodology

The general workflow of the project is:

```text
CO₂ Emissions Data
        ↓
Data Preprocessing
        ↓
Training: 1970–2015
        ↓
ANN / DNN / CNN / LSTM
        ↓
Model Evaluation
        ↓
Testing: 2016–2023
        ↓
Future Forecasting
        ↓
Forecasts: 2024–2030
```

## Models

### ANN

Artificial Neural Network is used to learn nonlinear patterns in historical CO₂ emissions.

### DNN

Deep Neural Network is used to capture more complex nonlinear relationships using multiple hidden layers.

### CNN

Convolutional Neural Network is applied to identify patterns in the emissions time series.

### LSTM

Long Short-Term Memory is used to capture temporal dependencies and long-term patterns in the CO₂ emissions data.


### Files

**`forecasting_carbon_emission_using_machine_learning.ipynb`**

Contains the Python code for data loading, preprocessing, model development, training, evaluation, and forecasting.

**`co2new.xlsx`**

Contains the historical CO₂ emissions data collected from the World Bank.


## Requirements

The project is implemented in Python and can be run using **Google Colab** or **Jupyter Notebook**.

Main libraries include:

```text
Python
NumPy
Pandas
Matplotlib
Scikit-learn
TensorFlow
```

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload `co2new.xlsx`.
3. Install the required libraries if necessary.
4. Run the notebook cells sequentially.

## Data Source

The CO₂ emissions data were collected from the **World Bank**.

World Bank Data: https://data.worldbank.org/




