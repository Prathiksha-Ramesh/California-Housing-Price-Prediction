# California Housing Price Prediction

This project uses the California Housing Dataset to build and evaluate a regression model to predict housing prices.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [License](#license)

## Introduction

This project aims to develop a machine learning model to predict housing prices in California using the California Housing Dataset. The dataset includes information about various factors such as median income, housing age, and population which can be used to predict the median house value.

## Dataset

The California Housing Dataset contains information collected from the 1990 California census. The data is available from the [scikit-learn](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset) library.

## Requirements

The project requires the following Python libraries:

- pandas
- numpy
- matplotlib
- scikit-learn
- seaborn

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```

## Installation

1. Clone the repository and navigate to the project directory:

```bash
git clone <repository-url>
cd <repository-name>
```
2. Install the required Python packages:

```bash
pip install -r requirements.txt

```

## Usage
1. Load the California Housing Dataset.
2. Preprocess the data (handle missing values, feature scaling, etc.).
3. Split the data into training and testing sets.
4. Train a regression model using the training set.
5. Evaluate the model using the testing set.

## Model Training
The model is trained using the Linear Regression algorithm from the scikit-learn library. Other regression algorithms such as Decision Trees or Random Forests can also be explored for better performance.

## Evaluation
The performance of the model is evaluated using metrics such as Mean Squared Error (MSE), R^2 and adjusted R^2

## License
This project is licensed under the MIT `License` - see the LICENSE file for details.

