# Nigerian House Price Prediction

## Overview
Wazobia Real Estate Limited, a prominent real estate company operating in Nigeria, With a vast portfolio of properties, they strive to provide accurate and competitive pricing for houses.
This project is a machine learning model built to predict house prices in Nigeria based on various features. It uses Python and the Scikit-Learn library.

## Table of Contents
- Overview
- Dataset
- Dependencies
- Installation
- Usage
- Model
- Evaluation
- Acknowledgements

## Dataset

The dataset used for training and testing the model is available for download at the link below:
👇👇
https://zindi.africa/competitions/free-ai-classes-in-every-city-hackathon-2023/data
The dataset contains features such as number of bedrooms, number of bathrooms, location, title (type of house), number of parking spaces, and the target (which is only present in the train dataset.).
Please download the dataset and put it in a directory before running your code.

## Dependencies
The following python packages are required to run the code:
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- CatBoost

## Installation
- Clone this repository to your local machine
- Navigate to the project directory
- Install the required dependencies.

To run the model with a new dataset, you can use the python script included in this repo.
Replace the csv file with the path to your dataset. The script will generate predictions for house prices based on the trained model.

## Model
The machine learning model is a regression model trained on the train dataset. The project includes a jupyter notebook: ( http://localhost:8888/notebooks/DSN%20House%20prediction.ipynb) that demonstrates the data preprocessing, model training, and evaluation steps.

## Evaluation
The model's performance is evaluated using the Root Mean Squared Error [RMSE]. The evaluation results can be found inside the pdf report present inside this repo.

## Acknowledgements
The dataset used for this project is sourced from Zindi: (https://zindi.africa/competitions/free-ai-classes-in-every-city-hackathon-2023/data)
