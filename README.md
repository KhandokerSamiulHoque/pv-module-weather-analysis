# Comparative Data Analysis of a PV Module System Considering Weather Parameters

My BSc thesis project at BRAC University (2021), done as a team. We logged two identical PV modules side by side for five months (November to March), one kept clean and one left to collect dust, along with module temperature, wind speed, humidity and air pressure. The thesis compared an artificial neural network, a random forest and linear regression for predicting module current from those readings. This repo holds the neural-network notebook and its results.

A 2026 reanalysis of the same data, with held-out days and month-level confidence intervals, is in [pv-current-estimation](https://github.com/KhandokerSamiulHoque/pv-current-estimation).

## Contents
- `FINAL_Keras_Sequential(3)(1).ipynb`: data loading, Keras model training and evaluation
- `only_<Month>_train.csv`: monthly training data for December, January, February and March
- `ANN_<Month>_<clean|dusty>_<n>.png`: predicted vs. measured output for each month and module
- `accuracy.png`: model accuracy summary

## Run
Open the notebook in Jupyter or Google Colab with the CSV files in the same folder. It needs `pandas`, `numpy`, `matplotlib`, `scikit-learn` and `tensorflow`.
