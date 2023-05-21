# Taxi Fare Prediction using Dask

## Problem Statement

Predict the taxi fare amount in New York city using Dask-ML. The project aims to leverage the power of Dask, a parallel computing framework, to handle large-scale datasets and accelerate the preprocessing and modeling steps of taxi fare prediction.

## Objectives

* understand how dask handles large dataset over pandas dataframe 
* perform exploratory data analysis on a large dataset (2 Million rows) using dask
* implement linear regression model using dask library and make predictions

## Dataset

The dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. This dataset contains 2M records and 9 features.

## Project Setup
Follow the steps below to set up the project:

1. Clone the project repository or download the project files to your local machine.

2. Open it in the Jupyter Notebook or in Google Colab.

3. Download the dataset uploaded

4. Ensure that you have Dask installed and set up properly on your machine.

## Usage
1. Open the taxi fare prediction file (ipynb file) that contains the code and project implementation.

2. Load the taxi fare dataset into the code using the appropriate file reading function (e.g., pd.read_csv() in the case of a CSV file).

3. Preprocess the dataset by performing any necessary data cleaning, handling missing values, encoding categorical variables, and feature engineering steps. Utilize Dask dataframes for distributed and out-of-core computations.

4. Implement the taxi fare prediction model using Dask-ML or scikit-learn's parallel algorithms. Set the appropriate hyperparameters based on the dataset and problem requirements.

5. Train the taxi fare prediction model using the Dask-based implementation and evaluate its performance using suitable evaluation metrics (e.g., mean squared error, R-squared).

6. Make fare predictions using the trained model and assess the accuracy of the predictions.

## Troubleshooting
1. Ensure that you have properly installed Dask and its required dependencies on your machine.

2. Check for any missing libraries or dependencies and install them using the pip install command if necessary.

3. Ensure that your machine has enough resources (e.g., memory, processing power) to handle the dataset and the parallel computations performed by Dask.
