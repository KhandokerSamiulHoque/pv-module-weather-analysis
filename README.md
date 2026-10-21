# PV module output vs. weather: clean and dusty modules

A Keras neural network that predicts PV module output from weather data, trained separately for a clean module and a dusty module in each of five months (November to March). The comparison shows how much soiling changes the relationship between weather and output.

## Contents
- `FINAL_Keras_Sequential(3)(1).ipynb`: data loading, model training and evaluation
- `only_<Month>_train.csv`: monthly training data for December, January, February and March
- `ANN_<Month>_<clean|dusty>_<n>.png`: predicted vs. measured output for each month and module
- `accuracy.png`: model accuracy summary

## Run
Open the notebook in Jupyter or Google Colab with the CSV files in the same folder. It needs `pandas`, `numpy`, `matplotlib`, `scikit-learn` and `tensorflow`.

Uploaded January 2024.
