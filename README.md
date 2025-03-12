# Gold Price Prediction using Random Forest Regressor

This project demonstrates the implementation of a **Random Forest Regressor** to predict gold prices based on historical financial data. The dataset includes various financial indicators such as stock prices, oil prices, silver prices, and currency exchange rates, which are used to train the model and predict future gold prices.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Data Preprocessing](#data-preprocessing)
6. [Model Training](#model-training)
7. [Results](#results)
8. [Visualization](#visualization)
9. [Dependencies](#dependencies)
10. [Contributing](#contributing)
11. [License](#license)

---

## Project Overview
The goal of this project is to predict gold prices using a Random Forest Regressor, a powerful ensemble machine learning algorithm. The project includes data exploration, preprocessing, model training, evaluation, and visualization of actual vs. predicted gold prices.

Key steps include:
- Loading and exploring the dataset.
- Analyzing correlations between features.
- Splitting data into training and testing sets.
- Training a Random Forest Regressor model.
- Evaluating model performance using metrics.
- Visualizing the actual vs. predicted gold prices.

---

## Dataset
The dataset used in this project is `gld_price_data.csv`, which contains the following columns:
- **Date**: The date of the observation.
- **SPX**: S&P 500 stock index.
- **GLD**: Gold price (target variable).
- **USO**: United States Oil Fund price.
- **SLV**: Silver price.
- **EUR/USD**: Euro to US Dollar exchange rate.

### Dataset Summary
- **Number of rows**: 2,290
- **Number of columns**: 6
- **Missing Values**: None (confirmed via `isnull().sum()`)

---

## Installation
To run this project, ensure you have Python installed along with the required libraries. Follow these steps:

1. Clone this repository:
   ```bash
   git clone <repository-url>

