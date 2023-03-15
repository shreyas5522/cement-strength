# Cement Strength Prediction

This project uses machine learning to predict the compressive strength of concrete based on its components. The dataset used in this project contains information on the amounts of different materials in a concrete mixture and the age of the concrete, as well as the resulting compressive strength. The goal of this project is to build a model that can accurately predict the strength of concrete based on its components.

## Dataset

The dataset used in this project is the Concrete Compressive Strength It contains 1030 observations and 8 features:

- Cement (kg/m^3): the amount of cement in the concrete mixture
- Blast Furnace Slag (kg/m^3): the amount of blast furnace slag in the concrete mixture
- Fly Ash (kg/m^3): the amount of fly ash in the concrete mixture
- Water (kg/m^3): the amount of water in the concrete mixture
- Superplasticizer (kg/m^3): the amount of superplasticizer in the concrete mixture
- Coarse Aggregate (kg/m^3): the amount of coarse aggregate in the concrete mixture
- Fine Aggregate (kg/m^3): the amount of fine aggregate in the concrete mixture
- Age (day): the age of the concrete in days

The target variable is:

- Concrete Compressive Strength (MPa): the compressive strength of the concrete in megapascals

## Approach

We will be using a linear regression model to predict the concrete compressive strength. The dataset will be split into training and testing sets, and the model will be trained on the training set. The performance of the model will be evaluated on the testing set using the mean squared error and R-squared metrics.

## Requirements

- Python 3
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

## Usage

Clone the repository and run the `cement.ipynb` notebook in Jupyter Notebook. The notebook contains all the code for loading and preprocessing the data, training and testing the model, and evaluating its performance.

## Results

After training the model on the cement dataset, we evaluated the model performance using mean absolute error (MAE), mean absolute percentage error (MAPE), and mean squared error (MSE). The model's MAE was found to be 8.68, the MAPE was 0.31, and the MSE was 120.40.

To predict the compressive strength of concrete for a new set of inputs, we randomly sampled one row from the dataset and defined it as X_new. The model predicted the compressive strength for this new input as 41.73 MPa.



