# Stock Market Prediction: Using ARIMA, LSTM & TCN

This project involves predicting stock market trends using a combination of machine learning models, including ARIMA (AutoRegressive Integrated Moving Average), LSTM (Long Short-Term Memory), and TCN (Temporal Convolutional Network). The goal is to evaluate the effectiveness of these models in forecasting stock prices and identify the best approach for accurate market predictions.

## Table of Contents

1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Aim and Objectives](#aim-and-objectives)
4. [Technologies Used](#technologies-used)
5. [Dataset](#dataset)
6. [Models Implemented](#models-implemented)
7. [Evaluation Metrics](#evaluation-metrics)
8. [Installation](#installation)
9. [Usage](#usage)
10. [Results](#results)
11. [Recommendations](#recommendations)
12. [Contributors](#contributors)
13. [Acknowledgements](#acknowledgements)

## Introduction

The stock market plays a crucial role in global economies, and accurate prediction of stock prices is a valuable asset for investors. This project seeks to leverage machine learning techniques to enhance prediction accuracy and assist in informed decision-making.

## Problem Statement

The project addresses the challenge of predicting stock market trends using machine learning models, given the complex and volatile nature of the market. Prior studies have often focused on limited methods, creating a need for comparative analysis of diverse approaches to improve prediction accuracy.

## Aim and Objectives

### Aim
To perform an in-depth comparative analysis of various machine learning models for stock market prediction, with the goal of enhancing prediction accuracy and understanding model effectiveness.

### Objectives
- Conduct a comprehensive literature review on stock market prediction.
- Explore optimal data preprocessing techniques.
- Evaluate machine learning models (ARIMA, LSTM, and TCN) for predicting stock prices.
- Compare performance metrics to determine the most effective model.

## Technologies Used

- **Python**: Main programming language.
- **Jupyter Notebook**: For data analysis and visualization.
- **PyCharm**: IDE for model implementation and code management.
- **Libraries**:
  - `TensorFlow` for deep learning models.
  - `NumPy` for numerical computations.
  - `Pandas` for data manipulation.
  - `Scikit-learn` for data preprocessing and evaluation.
  - `Keras` for building deep learning models.

## Dataset

The dataset was sourced from Yahoo Finance, using the `yfinance` Python library. It includes historical and real-time stock market data such as prices and trading volumes.

## Models Implemented

1. **ARIMA**: Used for modeling linear relationships and stationary data.
2. **LSTM**: Suitable for capturing long-term dependencies in sequential data.
3. **TCN**: Effective for managing complex patterns and high-frequency trends.

## Evaluation Metrics

The performance of the models is evaluated using:
- **MAPE (Mean Absolute Percentage Error)**
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**

## Installation

To set up the environment, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/d1vv1/Stock-Market-Price-Prediction.git
    ```
2. Alternatively, download the .ipynb files onto your machine.

## Usage

1. Run the Jupyter Notebook to explore data analysis and model training:
    ```bash
    jupyter notebook
    ```
2. Import the files `ARIMA.ipynb `, `LSTM.ipynb`, `TCN.ipynb`, and `ensemble.ipynb` into your jupyter notebook terminal, and run the files

## Results

The project includes a comparative analysis of the implemented models:
- **ARIMA**: Best for capturing linear trends.
- **LSTM**: Excels at managing sequential dependencies.
- **TCN**: Performs well in recognizing complex patterns.
- **Ensemble Approach**: A combination of the above models to enhance prediction accuracy.

## Recommendations

- Consider incorporating additional features like economic indicators or sentiment analysis.
- Use dynamic or adaptive models to handle sudden market shifts.
- Implement error monitoring to improve the robustness of predictions.

## Contributors

- **Divyanshu Mahi**
- **Sujay Naidu Dhulipudi**
- **Sarath Chandra P.V**

---

Feel free to modify any sections to better fit the specifics of your project or add additional instructions if needed!
