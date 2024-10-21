# CO2 Emission Predictor

This repository contains the implementation of a machine learning model designed to predict CO2 emissions based on various factors such as vehicle features and fuel consumption. The goal of this project is to provide a reliable and accurate tool for understanding how different vehicle characteristics contribute to CO2 emissions.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction

Climate change is one of the most pressing issues facing our planet, and CO2 emissions are a major contributor to global warming. This project leverages machine learning techniques to predict CO2 emissions based on vehicle characteristics such as fuel type, engine size, and more.

## Dataset

The dataset used in this project includes information on various vehicles, such as:
- **Engine Size** (liters)
- **Fuel Type** (e.g., petrol, diesel)
- **Fuel Consumption** (in L/100 km)
- **CO2 Emissions** (g/km)

You can download the dataset from [here](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64/resource/edba4afa-dc19-480c-bbe4-57992fc9d0d6).
## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Scikit-learn
  - Pandas
  - NumPy
  - Matplotlib

## Model

The model implemented in this project is a linear regression model that predicts CO2 emissions based on vehicle attributes. Future improvements may include experimenting with more advanced models such as Random Forests or Neural Networks to improve accuracy.

## Installation

To run this project locally, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/Oluwadt/CO2-Emission-Predictor.git
    ```

2. Navigate to the project directory:
    ```bash
    cd CO2-Emission-Predictor
    ```

## Usage

To use the CO2 Emission Predictor:

1. Load the dataset into a Jupyter Notebook or Python script.
2. Preprocess the data (feature selection, one-hot encoding, etc.).
3. Train the machine learning model using the training data.
4. Test the model and evaluate its performance using metrics such as Mean Squared Error (MSE).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
